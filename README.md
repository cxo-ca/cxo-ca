# 정호영 | Data & AI

> 데이터를 분석하는 것에서 끝나지 않고,
> **AI와 소프트웨어를 활용해 실제 사용자가 쓸 수 있는 서비스로 구현하는 과정**에 관심이 있습니다.

Python과 SQL을 기반으로 데이터 분석을 공부했으며,
최근에는 AI 모델과 데이터, 프론트엔드·백엔드를 연결하는 프로젝트를 진행하고 있습니다.

---

## English Summary

Data & AI enthusiast focused on turning **data and machine learning into practical products**.

Experienced with **Python, SQL, FastAPI, React, and React Native**, with projects covering data analytics, computer vision, LLM applications, and accessibility-focused AI services.

Currently exploring **end-to-end AI product development**, from problem definition and data processing to model integration and user-facing applications.

---

## About Me

* Data Analysis → AI → Application으로 이어지는 **End-to-End 프로젝트**에 관심이 있습니다.
* Python과 SQL을 활용한 데이터 처리 및 분석 경험이 있습니다.
* FastAPI, React / React Native를 활용해 AI 기능을 실제 서비스 형태로 구현하고 있습니다.
* 단순한 모델 성능보다 **사용자가 어떤 문제를 겪고 있으며 기술이 이를 어떻게 해결할 수 있는지**를 중요하게 생각합니다.
* 프로젝트에서 문제 정의와 기능 구현뿐만 아니라 **서비스 기획, 우선순위 설정, 의사결정 과정**에도 적극적으로 참여합니다.

---

## Current Focus

```text
Problem Definition
        ↓
Data Collection / Analysis
        ↓
AI / ML
        ↓
API & Backend
        ↓
Application
        ↓
User Validation
```

현재는 데이터 분석 역량을 기반으로
**AI 기반 서비스의 기획 → 데이터 → 모델 → 제품 구현 과정 전체를 경험하는 것**에 집중하고 있습니다.

---

# Featured Projects

## 1. Ear Dream

**한손 수어 기반 실시간 의사소통 보조 서비스**

🔗 https://github.com/Ear-Dream/Ear-Dream-Core

### 프로젝트 개요

두 손을 모두 사용하기 어려운 상황에서도
농인과 청인이 보다 즉각적으로 의사소통할 수 있도록 돕는 AI 기반 서비스입니다.

기존 수어 인식 시스템은 주로 양손 수어를 전제로 하기 때문에,
이동 중 스마트폰을 들고 있는 상황처럼 한 손만 사용할 수 있을 때 활용하기 어렵다는 문제에서 출발했습니다.

### 서비스 흐름

```text
한손 수어 입력
      ↓
손·얼굴 Landmark 추출
      ↓
수어 인식
      ↓
후보 단어 추천
      ↓
문장 구성
      ↓
텍스트 / 음성 전달
```

### 담당 및 경험

* React Native / Expo 기반 애플리케이션 개발
* MediaPipe 기반 손·얼굴 Landmark 추출 환경 구성
* 수어 인식 결과 기반 후보 단어 UI 구현
* 후보 선택 기반 문장 조합 UX 개발
* FastAPI API와 프론트엔드 간 연결 구조 이해 및 구현
* 실제 사용자 문제를 기반으로 서비스 기능과 사용자 흐름 구체화

### Tech

`React Native` `Expo` `TypeScript` `FastAPI` `Python` `MediaPipe` `OpenAPI`

**SKT FLY AI 9기 Team Project**

---

## 2. 편해질지도 | Barrier-Free Travel

**이동약자를 위한 무장애 여행 경로 추천 서비스**

🔗 https://github.com/gkfla2020-bit/barrier-free-travel

### 프로젝트 개요

이동약자가 여행을 계획할 때 겪는 접근성 문제를 해결하기 위해 진행한 해커톤 프로젝트입니다.

일반적인 지도 서비스가 최단거리와 이동시간 중심으로 경로를 제공하는 것과 달리,
이동약자에게는 계단, 경사로, 엘리베이터, 장애인 화장실, 저상버스 등 접근성 정보가 실제 이동 가능 여부를 결정하는 중요한 요소라는 점에 주목했습니다.

### 담당 역할 — Team Leader / PM

* 팀장으로서 프로젝트의 **문제 정의, 방향 설정 및 주요 의사결정** 담당
* 사용자 관점에서 핵심 문제를 정의하고 **서비스 컨셉과 핵심 기능 기획**
* 팀원별 역할 및 작업 우선순위를 조율하며 프로젝트 진행 관리
* 기능 후보를 검토하고 **MVP 범위와 구현 우선순위 결정**
* 기획·디자인·개발 과정에서 발생하는 이슈를 조율하고 최종 의사결정 수행
* 사용자 시나리오와 서비스 흐름을 구체화해 개발팀에 요구사항 전달
* 제한된 해커톤 기간 안에서 구현 가능성과 사용자 가치를 기준으로 기능 범위 조정

### 주요 서비스 아이디어

* 이동 제약 조건을 고려한 장소 추천
* 계단·경사 등 접근성을 반영한 이동 경로 제공
* 엘리베이터, 장애인 화장실 등 무장애 편의시설 정보 제공
* 저상버스 등 이동수단 접근성 정보 활용
* 사용자 조건에 맞는 여행 일정 및 이동 경로 추천

**TECH4GOOD Hackathon · Team 삼박자**

---

## 3. Seoul Traffic EDA Dashboard

**서울 출퇴근 교통 데이터 분석 및 Streamlit Dashboard**

🔗 https://github.com/cxo-ca/project-eda-dashboard

### 프로젝트 개요

서울 도로 교통 데이터를 활용해 출퇴근 시간대의 교통 흐름을 분석하고,
분석 결과를 사용자가 직관적으로 확인할 수 있도록 Streamlit 대시보드로 구현한 프로젝트입니다.

### 주요 작업

* 데이터 구조 및 결측치 분석
* 데이터 정제 및 전처리
* 출퇴근 시간대 기준 정의
* AM / PM 평균 속도 등 주요 지표 설계
* Python / Pandas 기반 탐색적 데이터 분석
* SQLite 데이터 조회
* Streamlit 기반 데이터 시각화 및 Dashboard 구현

### Tech

`Python` `Pandas` `SQLite` `Streamlit` `EDA` `Data Visualization`

---

## 4. Seoul Traffic ETL Pipeline

**서울 도로속도 데이터 ETL Pipeline**

🔗 https://github.com/cxo-ca/project-etl-sql

### 프로젝트 개요

원천 교통 데이터를 분석 가능한 형태로 정제하고 데이터베이스에 저장하는
ETL 파이프라인을 구현한 프로젝트입니다.

단순히 데이터를 분석하는 것에서 그치지 않고,
원천 데이터가 분석과 시각화 단계까지 안정적으로 연결될 수 있도록 데이터 흐름을 구성하는 것을 목표로 했습니다.

### Pipeline

```text
Raw Data
   ↓
Cleaning
   ↓
Standard Schema
   ↓
SQLite
   ↓
EDA / Dashboard
```

### 주요 작업

* 원천 데이터 구조 분석
* 데이터 정제 및 결측치 처리
* 분석 목적에 맞는 표준 스키마 구성
* Python / Pandas 기반 ETL 처리
* SQLite 데이터베이스 적재
* SQL을 활용한 데이터 조회 및 검증
* EDA 및 Dashboard 프로젝트와 연결 가능한 데이터 구조 설계

### Tech

`Python` `Pandas` `SQL` `SQLite` `ETL`

---

# Tech Stack

### Data / AI

`Python` `SQL` `Pandas` `NumPy`
`scikit-learn` `EDA` `Data Preprocessing` `Machine Learning`

### AI / Computer Vision

`MediaPipe` `Computer Vision` `LLM API`

### Backend

`FastAPI` `REST API` `OpenAPI` `SQLite` `MySQL`

### Frontend / App

`React` `React Native` `Expo` `TypeScript` `Streamlit`

### Tools

`Git` `GitHub` `VS Code` `pnpm`

---

# Currently Learning

현재 다음 영역을 중심으로 역량을 확장하고 있습니다.

* Machine Learning / Data Science
* Computer Vision
* AI 서비스 설계
* LLM Application
* 데이터 기반 제품 개발
* End-to-End AI Pipeline
* AI Model과 Application 간 Integration

---

# Interests

```text
Data Analysis
      +
Machine Learning
      +
AI Application
      +
Product Development
```

데이터에서 의미 있는 정보를 발견하는 것뿐만 아니라,
이를 **사용자가 실제로 사용할 수 있는 제품과 서비스로 연결하는 과정**에 관심이 있습니다.

장기적으로는 데이터 분석 및 머신러닝 역량과 서비스 구현 경험을 함께 갖춘
**Data Scientist / AI Engineer**로 성장하는 것을 목표로 하고 있습니다.

---

# Contact

* **Email**: [2012hy5@naver.com](mailto:2012hy5@naver.com)
* **Portfolio**: https://sites.google.com/view/cxo-ca
* **GitHub**: https://github.com/cxo-ca
* **LinkedIn**: https://www.linkedin.com/in/호영-정-26356b388
