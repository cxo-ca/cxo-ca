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

> 두 손을 모두 사용하기 어려운 상황에서도
> 농인과 청인이 보다 즉각적으로 소통할 수 있도록 돕는 AI 서비스

🔗 https://github.com/Ear-Dream/Ear-Dream-Core

### Problem

기존 수어 인식 시스템은 주로 양손 수어를 전제로 하기 때문에
이동 중 스마트폰을 들고 있는 상황처럼 한 손만 사용할 수 있을 때 활용하기 어렵습니다.

### Solution

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

### What I Work On

* React Native / Expo 기반 애플리케이션 개발
* MediaPipe 기반 손·얼굴 Landmark 추출
* 수어 인식 결과 후보 단어 UI
* 후보 선택 기반 문장 조합 UX
* FastAPI API와 프론트엔드 연결 구조 이해 및 구현

### Tech

`React Native` `Expo` `TypeScript` `FastAPI` `Python` `MediaPipe` `OpenAPI`

**SKT FLY AI 9기 Team Project**

---

## 2. 편해질지도 | Barrier-Free Travel

**이동약자가 직접 설계하는 장벽 없는 여행**

🔗 https://github.com/gkfla2020-bit/barrier-free-travel

### Problem

일반적인 지도 서비스는 최단 경로를 제공하지만,

* 계단
* 경사로
* 엘리베이터
* 장애인 화장실
* 저상버스

등 이동약자에게 중요한 정보를 충분히 고려하지 못하는 경우가 있습니다.

### Solution

사용자의 이동 조건을 입력받아 접근 가능한 장소를 필터링하고,
이동 난이도를 고려해 실제 이동 가능한 여행 코스를 만드는 서비스를 구현했습니다.

### Key Features

* 한국관광공사 무장애 관광 데이터 활용
* 사용자 이동 조건 기반 장소 필터링
* 계단 회피 보행 경로
* 구간별 이동 난이도 계산
* 저상버스 정보 연동
* LLM 기반 여행 코스 추천
* 접근성 정보를 보수적으로 판정하는 데이터 처리 로직

### Tech

`React` `Vite` `FastAPI` `Python` `Tmap API` `TourAPI` `Claude API`

**TECH4GOOD Hackathon · Team 삼박자**

---

## 3. Seoul Traffic EDA Dashboard

**서울 출퇴근 교통 데이터 분석 및 Streamlit Dashboard**

🔗 https://github.com/cxo-ca/project-eda-dashboard

출퇴근 시간대 교통 데이터를 분석하고
AM/PM 평균속도 등의 KPI를 정의하여 대시보드로 시각화한 프로젝트입니다.

### What I Did

* 데이터 구조 및 결측치 분석
* 출퇴근 시간대 지표 정의
* Python / Pandas 기반 EDA
* SQLite 데이터 조회
* Streamlit Dashboard 구현

### Tech

`Python` `Pandas` `SQLite` `Streamlit`

---

## 4. Seoul Traffic ETL Pipeline

**서울 도로속도 데이터 ETL Pipeline**

🔗 https://github.com/cxo-ca/project-etl-sql

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

데이터 수집과 분석을 분리하지 않고
재사용 가능한 데이터 파이프라인 형태로 구현하는 것을 목표로 진행했습니다.

### Tech

`Python` `Pandas` `SQLite` `ETL`

---

# Tech Stack

### Data / AI

`Python` `SQL` `Pandas` `NumPy` `scikit-learn`
`EDA` `Data Preprocessing` `Machine Learning`

### Backend

`FastAPI` `SQLite` `MySQL` `REST API` `OpenAPI`

### Frontend / App

`React` `React Native` `Expo` `TypeScript`
`Streamlit`

### AI / Computer Vision

`MediaPipe` `Computer Vision` `LLM API`

### Tools

`Git` `GitHub` `VS Code` `pnpm`

---

# What I'm Learning

현재 다음 영역을 중심으로 역량을 확장하고 있습니다.

* Machine Learning / Data Science
* AI 서비스 설계
* Computer Vision
* LLM Application
* 데이터 기반 제품 개발
* End-to-End AI Pipeline

---

# Contact

* **Email**: [2012hy5@naver.com](mailto:2012hy5@naver.com)
* **Portfolio**: https://sites.google.com/view/cxo-ca
* **LinkedIn**: https://www.linkedin.com/in/호영-정-26356b388
