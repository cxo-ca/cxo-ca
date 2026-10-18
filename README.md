# 정호영 | Data Science & AI Engineering

> 데이터에서 근거를 찾고, AI와 소프트웨어를 연결해 사용자가 쓸 수 있는 서비스로 만듭니다.

Python·SQL 기반 데이터 처리에서 출발해, **통계 분석의 재현성**과 **AI 서비스의 실제 동작**을 함께 고민하고 있습니다. 최근에는 대장암 GWAS·eQTL 공위치 분석과 선박 업무 지원 앱 **해답(SEA THE ANSWER)**의 백엔드·LLM 연동을 진행했습니다.

**관심 직무:** Data Scientist / AI Engineer

**관심 영역:** 데이터 파이프라인 · 통계 분석 · 근거 기반 AI 응답 · API와 애플리케이션 연동

## Recent Work

| 프로젝트 | 최근 진행 내용 | 확인할 자료 |
|---|---|---|
| **해답 — SEA THE ANSWER** | MVP 구현, FastAPI·PostgreSQL 전환, OpenAI 호환 LLM 연동 및 공급자별 인증키 분리 | [팀 저장소](https://github.com/dudco/sea-the-answer) · [병합 PR #7](https://github.com/dudco/sea-the-answer/pull/7) · [병합 PR #13](https://github.com/dudco/sea-the-answer/pull/13) |
| **대장암 GWAS·eQTL 분석** | 공개 자료 후보 탐색부터 실제 공위치 분석, 사전확률 민감도·누락 점검, 최종 보고서까지 정리 | [코드·분석 결과](https://github.com/cxo-ca/crc-gwas-eqtl) · [최종 보고서](https://github.com/cxo-ca/crc-gwas-eqtl/blob/main/reports/final_report.md) |

## Featured Projects

### 1. 해답 — SEA THE ANSWER

**선내 문서 근거와 운항 기록을 함께 다루는 선박 업무 지원 앱 · 팀 프로젝트**

문서 검색, 운항 정보 조회·계산, 보고서 초안 작성과 승인 흐름을 하나의 웹 앱으로 연결합니다.

**My Contributions**

- 문서 검색·근거 확인·보고서 저장·계산 도구를 연결한 [초기 MVP 구현](https://github.com/dudco/sea-the-answer/pull/1)
- 기존 API를 **FastAPI**로 이전하고 **PostgreSQL** 초기 스키마·SQLite 이전 도구 및 `uv` 기반 실행 환경 구성
- 백업·복구, 동시 수정 충돌 감지, 허용 호스트·권한 재확인 등 백엔드 동작 보완
- OpenAI 호환 Chat Completions 설정과 공급자별 인증키 분리 구현
- 모델 응답의 JSON·인용 검증 및 실패 시 근거 원문 발췌로 전환하는 흐름 유지·검증
- 백엔드·프런트엔드·Docker Compose e2e 검증 워크플로를 [별도 PR #14](https://github.com/dudco/sea-the-answer/pull/14)로 제안 — **검토 중**

현재 팀 앱은 **Next.js / FastAPI / PostgreSQL / Docker Compose**로 구성됩니다. 문서 검색은 키워드 기반이며, 벡터·하이브리드 RAG와 공식 CII 계산은 후속 통합 범위입니다. LLM 호환 호출은 모의 HTTP로 검증했으며, PR #13의 실제 외부 모델 호출 검증과는 구분합니다.

`Python` `FastAPI` `PostgreSQL` `uv` `LLM API` `pytest` `Docker Compose`

[팀 저장소·실행 안내](https://github.com/dudco/sea-the-answer) · [개인 작업·PR 안내](https://github.com/cxo-ca/sea-the-answer)

### 2. 대장암 GWAS·eQTL 기반 유전자 후보 탐색

**공개 유전체 자료를 활용한 통계 분석 · 연구 프로젝트**

대장암 GWAS 변이와 GTEx v8 대장 조직 eQTL을 연결하고, 구간 요약통계를 정렬해 `coloc`으로 공위치 근거를 평가했습니다.

- 공개 API 자료 수집, rsID·좌표·대립유전자 정렬, 중복·결측 QC
- 초기 **102개 후보 유전자**를 보존하고, 자료가 확보된 **100개 유전자·144개 유전자–조직 조합** 분석
- 사전확률 3개 설정으로 **432회 공위치 분석**, 별도 Python 계산으로 posterior 검증
- 기본 사전확률에서 18개 유전자가 PP.H4 ≥ 0.8을 충족했고, 세 설정 모두에서 기준을 유지한 조건부 후보는 9개
- 입력 체크섬·분석 환경·후보표·해석 제한을 보고서에 기록

분석 수치는 **2026-09-23 최종 보고서 기준**입니다. 현재 자료와 분석 구간에 조건부인 탐색적 결과이며, 인과 유전자 확정이나 독립·기능 검증을 의미하지 않습니다.

`R` `Python` `coloc` `GWAS` `eQTL` `Data QC` `Reproducible Analysis`

[저장소](https://github.com/cxo-ca/crc-gwas-eqtl) · [최종 보고서](https://github.com/cxo-ca/crc-gwas-eqtl/blob/main/reports/final_report.md) · [분석 방법·제한](https://github.com/cxo-ca/crc-gwas-eqtl/blob/main/docs/COLOC_RESULTS.md)

### 3. Ear-Dream | 손결

**한손 수어 기반 AI 의사소통 보조 서비스 · SKT FLY AI 9기 팀 프로젝트**

두 손을 자유롭게 쓰기 어려운 상황에서도 농인과 청인이 의사소통할 수 있도록, 수어 인식 결과를 문장·텍스트·음성으로 연결하는 서비스입니다.

**My Contributions**

- React Native 기반 수어 입력·인식 결과 화면과 카메라 입력 UX 구현
- 인식 단어를 문장으로 누적하는 Sentence Composer 및 Top-K 후보 기반 오인식 수정 UX 구현
- 실제 마이크 입력 수준에 연동한 음성 waveform 구현
- Figma 디자인과 300개 수어 단어 픽토그램을 모바일 UI에 적용
- FastAPI / OpenAPI 기반 API 연동 구조 작업 및 사용자 시나리오·기능 우선순위 논의

`React Native` `Expo` `TypeScript` `FastAPI` `OpenAPI` `MediaPipe`

### 4. Seoul Traffic Data Pipeline & Dashboard

**서울 출퇴근 도로속도 데이터 처리를 위한 ETL·EDA 프로젝트**

CSV 데이터를 `date / hour / speed` 스키마로 정규화해 SQLite에 적재하고, Streamlit에서 출근(07–09시)·퇴근(17–19시) 평균속도를 비교합니다.

- Python / Pandas 기반 컬럼 정규화와 SQLite upsert
- CSV/XLSX 업로드 기반 기본 통계·숫자형 차트
- SQLite의 `logs_road`를 조회하는 AM/PM KPI 카드와 비교 차트
- DB 또는 `logs_road` 테이블이 없는 경우 대시보드에서 시연용 샘플 생성

**공공데이터 API 수집기는 엔드포인트·키·응답 형식 설정이 필요한 템플릿 단계**입니다. 대시보드의 자동 생성 샘플과 실제 관측 자료를 구분합니다.

`Python` `SQL` `Pandas` `SQLite` `Streamlit` `ETL` `EDA`

[ETL 코드](https://github.com/cxo-ca/project-etl-sql) · [대시보드 코드](https://github.com/cxo-ca/project-eda-dashboard)

### 5. 편해질지도 | Barrier-Free Travel

**이동약자를 위한 무장애 여행 서비스 · TECH4GOOD Hackathon**

**Team Leader / PM**으로 사용자 문제 정의, 핵심 기능 선정, 팀원 역할·우선순위 조율, MVP 범위와 사용자 흐름 설계를 맡았습니다. 기획·디자인·개발 사이의 의사결정을 조율하며 사용자에게 필요한 기능부터 구현하도록 프로젝트를 운영했습니다.

## Learning & Practice

| 저장소 | 내용 |
|---|---|
| [LeetCode_HY](https://github.com/cxo-ca/LeetCode_HY) | Python 자료구조·알고리즘 풀이: Tree / Graph, DFS / BFS, DP, Greedy, Binary Search, Sliding Window 등 |
| [mysql-practice](https://github.com/cxo-ca/mysql-practice) | CRUD, 집계, JOIN, 서브쿼리, 관계·데이터 모델링 실습 |
| [commento-frontend-intro](https://github.com/cxo-ca/commento-frontend-intro) | HTML / CSS / JavaScript 과제와 GitHub Pages 배포 |
| [guestbook](https://github.com/cxo-ca/guestbook) | Node.js / Express 방명록과 Azure App Service·컨테이너 배포 실습 |
| [ai-future-society-2025](https://github.com/cxo-ca/ai-future-society-2025) | AI의 사회·윤리·산업 영향에 관한 강의 노트·과제 |

문제의 패턴, 자료구조 선택 이유, 시간복잡도를 이해하고 기록하는 것을 목표로 합니다.

## Tech Stack

| 영역 | 사용 경험 |
|---|---|
| Data & Statistics | Python, SQL, R, Pandas, NumPy, SQLite, MySQL, GWAS / eQTL, coloc |
| AI | scikit-learn, MediaPipe, Computer Vision, LLM API |
| Backend | FastAPI, PostgreSQL, REST API, OpenAPI |
| Frontend & Application | React, React Native, Expo, TypeScript, Streamlit, HTML / CSS / JavaScript |
| Development & Validation | Git, GitHub, uv, pytest, Docker Compose, GitHub Actions |

## Contact

- **Email:** [2012hy5@naver.com](mailto:2012hy5@naver.com)
- **Portfolio:** [cxo-ca](https://sites.google.com/view/cxo-ca)
- **GitHub:** [@cxo-ca](https://github.com/cxo-ca)
- **LinkedIn:** [프로필](https://www.linkedin.com/in/호영-정-26356b388)

<sub>프로젝트 상태 확인: 2026-10-18 · 팀 프로젝트는 개인 기여와 전체 구현 범위를 구분해 기록합니다.</sub>
