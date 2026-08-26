<div align="center">

# 👋 From Data to AI

### 업무 데이터를 연결하고, 분석하고, AI로 확장하는 개발자

**Data Engineering · Business System · AI Application**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/qkrwlfjddl)

</div>

---

## About Me

업무 데이터를 실제 서비스와 업무 시스템으로 연결하는 개발자입니다.

SAP HANA, GA4 등의 데이터를 **BigQuery 기반 데이터 플랫폼으로 통합**하고,
이를 기반으로 **업무용 대시보드와 AI 분석 기능**을 구축해왔습니다.

단순한 데이터 분석을 넘어

**데이터 수집 → 파이프라인 → 분석 → AI → 서비스 운영**

까지 하나의 흐름으로 설계하고 구현하는 것을 목표로 합니다.

### What I Do

- 업무 시스템의 데이터 구조 분석 및 요구사항 정의
- SAP HANA → BigQuery 데이터 파이프라인 구축
- Airflow 기반 데이터 적재 및 배치 자동화
- BigQuery 기반 데이터 모델링 및 분석
- 업무용 Dashboard / Analytics 시스템 개발
- Vertex AI / Gemini 기반 AI 기능 구현
- RAG 기반 업무 지식 검색 시스템 구축
- Cloud Run / Docker 기반 서비스 배포 및 운영

---

## 🚀 Featured Projects

<table>
<tr>

<td width="50%" valign="top">

### 📈 Business Data & AI Dashboard

**통합 성과 분석 · AI 리포트 · RAG 기반 업무 플랫폼**

분산되어 있던 매출·마케팅·콘텐츠 데이터를 BigQuery로 통합하고,
성과 분석부터 AI 리포트, 과거 리포트 비교, RAG 검색까지 연결한
업무용 데이터 분석 플랫폼입니다.

**Key Features**

- SAP / GA4 / 콘텐츠 데이터 통합
- BigQuery 기반 통합 분석
- AI 성과 분석 리포트
- 비동기 AI 처리
- 과거 리포트 비교
- RAG 기반 자연어 검색
- Google OAuth 및 권한 관리

**Tech**

`Python` `SQL` `BigQuery` `Streamlit`
`Cloud Run` `Vertex AI` `Gemini` `RAG`

<br/>

👉 [View Project](https://github.com/qkrwlfjddl/Business-Data-AI-Dashboard)

</td>

<td width="50%" valign="top">

### 🔄 SAP HANA → BigQuery Pipeline

**Airflow 기반 데이터 적재 자동화**

SAP HANA 데이터를 BigQuery로 적재하기 위한
Cloud Composer(Apache Airflow) 기반 데이터 파이프라인입니다.

**Key Features**

- Dynamic DAG 생성
- YAML 기반 테이블 설정
- SQL 기반 데이터 추출
- Cloud Run 공통 Loader
- Staging → Target 적재 구조
- Chunk 단위 데이터 처리
- 실패 작업 재시도 및 운영 관리

**핵심 설계**

> 신규 테이블 추가 시  
> **YAML 1개 + SQL 1개**

코드 수정이나 컨테이너 재빌드 없이
새로운 적재 작업을 추가할 수 있도록 구성했습니다.

**Tech**

`Apache Airflow` `Cloud Composer`
`SAP HANA` `BigQuery` `Cloud Run` `Python`

<br/>

👉 [View Project](https://github.com/qkrwlfjddl/HANA-BQ-ApacheAirflow)

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 📊 Marketing KPI & AI Insight

**GA4 기반 마케팅 성과 분석 시스템**

GA4 데이터를 기반으로 유입·전환·매체별 성과를 분석하고
AI를 활용해 주요 변화와 인사이트를 도출하는 분석 시스템입니다.

**Key Features**

- GA4 데이터 분석
- 채널 / 매체별 KPI 분석
- 전환 성과 분석
- 기간별 성과 비교
- AI 기반 성과 해석

👉 [View Project](https://github.com/qkrwlfjddl/Marketing-KPI-AI-Insight)

</td>

<td width="50%" valign="top">

### 🎓 LMS Student Analysis

**학습 데이터 기반 교육과정 추천 연구**

학생 학습 데이터를 분석하고
학생 특성 및 학습 패턴을 기반으로
교육과정을 추천하는 데이터 분석 프로젝트입니다.

🏆 **대학혁신지원사업 우수 연구 사례**

👉 [View Project](https://github.com/qkrwlfjddl/UNIV_STD_Curriculum_Rec)

</td>

</tr>
</table>

---

## 🏗️ Engineering Focus

제가 가장 관심을 가지고 있는 영역입니다.

```text
Business Data
      ↓
SAP / GA4 / External API
      ↓
Data Pipeline
      ↓
Airflow · Cloud Run
      ↓
BigQuery
      ↓
Analytics / Dashboard
      ↓
AI Analysis
      ↓
RAG · Natural Language Search
      ↓
Business Application
