# 정호영 | Data Science & AI

> 데이터를 분석하는 데서 끝나지 않고, AI 모델과 소프트웨어를 연결해 실제 사용자가 사용할 수 있는 서비스로 구현하는 과정에 관심이 있습니다.

Python과 SQL 기반의 데이터 분석을 시작으로
Machine Learning, Computer Vision, FastAPI, React Native까지 경험하며
**Data → AI → Application**으로 이어지는 End-to-End 프로젝트를 만들어가고 있습니다.

---

## About Me

* Python / SQL 기반 데이터 처리 및 분석
* Machine Learning 및 Computer Vision 기반 AI 서비스 구현
* FastAPI를 활용한 AI inference API 연동
* React / React Native 기반 사용자 애플리케이션 구현
* 문제 정의, UX 설계, 기능 우선순위 및 프로젝트 의사결정 참여
* 알고리즘과 자료구조를 Python으로 지속적으로 학습

현재 **Data Scientist / AI Engineer** 직무를 중심으로 역량을 확장하고 있습니다.

---

# Featured Projects

## 1. Ear-Dream | 손결

### 한손 수어 기반 AI 의사소통 보조 서비스

**SKT FLY AI 9기 Team Project**

스마트폰을 들고 있거나 이동 중인 상황처럼 두 손을 자유롭게 사용하기 어려울 때도
농인과 청인이 의사소통할 수 있도록 만든 한손 수어 기반 AI 서비스입니다.

### Service Flow

```text
Sign Language
    ↓
MediaPipe Landmark Extraction
    ↓
Sign Recognition
    ↓
Top-K Word Candidates
    ↓
Sentence Composition
    ↓
Text / Speech
```

반대 방향에서는

```text
Speech / Text
    ↓
STT
    ↓
Sentence Decomposition
    ↓
Sign Sequence
    ↓
Sign-language Avatar
```

형태로 청인의 음성을 수어 표현으로 전달합니다.

### My Contributions

* React Native 기반 수어 입력 및 결과 화면 구현
* 인식된 단어를 누적해 문장을 만드는 Sentence Composer 구현
* Top-K 후보 기반 오인식 수정 UX 구현
* 실제 microphone level과 연동되는 음성 입력 waveform 구현
* Figma 최종 디자인을 애플리케이션 UI에 반영
* 300개 수어 단어 픽토그램을 후보 카드 및 단어 UI에 적용
* 모바일 화면 비율 및 카메라 입력 UX 개선
* FastAPI / OpenAPI 기반 API 연동 구조 작업
* 사용자 시나리오와 서비스 흐름 설계 및 기능 우선순위 논의

### Tech

`Python` `FastAPI` `MediaPipe` `React Native` `Expo` `TypeScript` `OpenAPI`

---

## 2. Seoul Traffic Data Pipeline & Dashboard

### 서울 출퇴근 교통 데이터 분석

서울 도로속도 데이터를 이용해

```text
Raw Data
   ↓
Cleaning / Preprocessing
   ↓
Standard Schema
   ↓
SQLite
   ↓
EDA
   ↓
KPI
   ↓
Streamlit Dashboard
```

형태의 데이터 파이프라인을 구현했습니다.

### What I Did

* 원천 데이터 구조 및 결측치 분석
* Python / Pandas 기반 전처리
* 분석용 표준 스키마 설계
* SQLite 데이터 적재
* SQL 기반 데이터 검증 및 조회
* 출퇴근 시간대 KPI 정의
* Streamlit 데이터 대시보드 구현

### Tech

`Python` `SQL` `Pandas` `SQLite` `Streamlit` `EDA` `ETL`

---

## 3. 편해질지도 | Barrier-Free Travel

### 이동약자를 위한 무장애 여행 서비스

TECH4GOOD Hackathon에서 진행한 이동약자 여행 지원 서비스입니다.

### Role — Team Leader / PM

* 사용자 문제 정의
* 서비스 방향 및 핵심 기능 결정
* 팀원 역할 및 우선순위 조율
* MVP 범위 결정
* 사용자 시나리오 및 서비스 플로우 설계
* 기획 / 디자인 / 개발 간 의사결정 수행

기술 자체보다 **사용자에게 어떤 문제가 있고 어떤 기능부터 해결해야 하는가**를 중심으로 프로젝트를 운영했습니다.

---

# Algorithm & Problem Solving

Python을 이용해 LeetCode 문제를 풀며 자료구조와 알고리즘 기본기를 학습하고 있습니다.

현재 주요 학습 영역:

`Array` `Hash Table` `Stack` `Queue`
`Linked List` `Tree` `Graph`
`DFS` `BFS` `Union-Find`
`Dynamic Programming` `Greedy`
`Binary Search` `Sliding Window`
`Backtracking`

단순 정답 제출보다 문제의 패턴을 구분하고
시간복잡도와 자료구조 선택 근거를 이해하는 것을 목표로 하고 있습니다.

---

# Tech Stack

### Data

`Python` `SQL` `Pandas` `NumPy` `EDA` `ETL` `Data Preprocessing`

### Machine Learning / AI

`scikit-learn` `Machine Learning` `MediaPipe` `Computer Vision` `LLM API`

### Backend

`FastAPI` `REST API` `OpenAPI` `SQLite` `MySQL`

### Frontend / Application

`React` `React Native` `Expo` `TypeScript` `Streamlit`

### Tools

`Git` `GitHub` `VS Code` `pnpm`

---

# What I'm Building Toward

```text
Problem Definition
        ↓
Data Collection / Analysis
        ↓
Machine Learning / AI
        ↓
API
        ↓
Application
        ↓
User Validation
```

데이터 분석 역량을 기반으로 모델을 만드는 것뿐 아니라
**데이터와 AI를 실제 제품과 서비스로 연결할 수 있는 Data Scientist / AI Engineer**로 성장하는 것을 목표로 하고 있습니다.

---

# Contact

* **Email**: [2012hy5@naver.com](mailto:2012hy5@naver.com)
* **Portfolio**: https://sites.google.com/view/cxo-ca
* **GitHub**: https://github.com/cxo-ca
* **LinkedIn**: https://www.linkedin.com/in/호영-정-26356b388
