# Taehoon Jang

풀스택 엔지니어 · AI 시스템 · 보안 데이터 플랫폼  
서울대학교 의과대학 Biomedical Informatics Lab · 2010 – present  
Software Engineering since 2000

의료데이터 플랫폼, 의료 AI 시스템, 프라이버시 보호형 데이터 분석 환경, 블록체인 기반 신뢰 인프라를 설계하고 구현해온 연구개발 엔지니어입니다.  
실제 서비스와 연구 시스템에서 백엔드, 프론트엔드, 데이터 파이프라인, 검색 시스템, 보안 실행 환경까지 폭넓게 개발해왔습니다.

---

## Engineering & Research Areas

- 의료데이터 플랫폼
- 의료 AI 시스템
- 프라이버시 보호형 데이터 분석
- 블록체인 및 신뢰 인프라
- 보안 실행 환경 및 분석 플랫폼

---

## Selected Projects

아래 프로젝트들은 제가 의료데이터 플랫폼, AI 시스템, 보안 컴퓨팅 환경 분야에서 수행해온 대표 시스템들입니다.  
대부분의 프로젝트에서 시스템 설계와 핵심 구현을 직접 주도했으며, 일부는 백엔드 핵심 구조와 주요 기능 개발을 중심으로 참여했습니다.

### Core Technology Stack

`Oracle Cloud` · `Docker` · `Nginx` · `Python` · `Java` · `Spring Boot` · `React TypeScript` · `MySQL`

---

# 🧠 KryptoBrain

개인정보 보호형 안전 분석 플랫폼  
Secure Analysis Platform for Privacy-Preserving Data Processing

### Project Tech Stack

`Kubernetes` · `Blockchain` · `Smart Contracts` · `Solidity` · `Remix` · `Chrome Extension` · `AES/RSA Encryption` · `PostgreSQL` · `Secure Data Processing` · `CDM (OMOP)` · `PHR Integration` · `RabbitMQ` · `STOMP WebSocket`

## 📌 Overview

KryptoBrain은 개인정보 및 의료데이터와 같은 민감 데이터를 안전하게 분석하기 위한 **Secure Analysis Platform**입니다.  
데이터를 중앙에 수집하는 방식이 아니라, **분석 실행 환경 자체를 안전하게 생성하고 통제하는 구조**로 설계했습니다.

CDM 기반 의료데이터, 개인 건강 데이터(PHR), Chrome Extension을 통해 수집되는 사용자 로그 및 Life Log 데이터 등을 실제 분석 환경에서 연동·처리할 수 있도록 구현하고 테스트했습니다.  
분석은 **Kubernetes 기반 Analysis Pod**에서 수행되며, 원본 데이터가 외부 환경으로 직접 전달되지 않도록 설계했습니다.

또한 연구 생성, 참여, 결과 기록 과정은 **Blockchain 기반 Smart Contract**와 **DAO 거버넌스** 구조를 통해 관리되며, 분석 과정과 결과의 무결성과 투명성을 검증 가능하도록 구성했습니다.

## 👨‍💻 My Role

- 프로젝트 **전체 설계 및 핵심 구현 대부분을 직접 수행**
- 분석 요청부터 안전한 실행 환경 생성, 데이터 처리, 결과 관리까지 주요 흐름 개발
- 백엔드, 데이터 처리, 보안 구조, Chrome Extension 연계, 분석 실행 환경 제어 등 전체 핵심 기능 주도

## 🎬 Demo Video

[![KryptoBrain Demo](docs/kryptobrain.png)](https://youtu.be/lnJUO_6_bFI)

*System concept, architecture, and demo video produced by Taehoon Jang.*

---

# 🪪 RhymeCard

블록체인 기반 분산 신원 및 커뮤니티 멤버십 플랫폼  
Decentralized Identity Platform for Digital Identity & Community Membership

### Project Tech Stack

`Blockchain` · `DID (Decentralized Identifier)` · `Verifiable Credentials` · `Verifiable Presentation` · `Mobile App` · `QR Code Authentication` · `Identity Management` · `Smart Contracts` · `RabbitMQ` · `STOMP WebSocket` · `Kakao AlimTalk API` · `NICE Identity Verification` · `NHIS Eligibility Verification API` · `Kakao Pay Transfer API`

## 📌 Overview

RhymeCard는 블록체인 기반 **Decentralized Identity Platform**으로, 개인의 신원 인증과 커뮤니티 멤버십 관리를 안전하게 수행하기 위한 **디지털 신분증 서비스**입니다.

기존 중앙 서버 기반 계정 체계와 달리, 사용자의 신원은 **DID(Decentralized Identifier)** 기반으로 관리되며 개인이 자신의 신원 정보와 인증 데이터를 직접 통제할 수 있도록 설계했습니다.  
또한 사용자의 자격 정보는 **Verifiable Credential (VC)** 형태로 발급되고, 필요 시 **Verifiable Presentation (VP)** 방식으로 선택적 증명이 가능하도록 구현했습니다.

모바일 앱 기반으로 발급되며, **QR 코드 및 NFC 방식**을 통해 병원, 커뮤니티, 행사 등 다양한 환경에서 개인 인증, 회원 관리, 서비스 접근 제어를 지원할 수 있도록 설계했습니다.

## 👨‍💻 My Role

- 프로젝트 전체 기준 약 **30% 수준 참여**
- 다만 **백엔드 핵심 구조와 주요 기능 구현은 대부분 직접 담당**
- 인증 흐름, 데이터 처리, 주요 서버 기능 및 시스템 연동 핵심 파트 중심으로 개발

## 🎬 Demo

![RhymeCard](docs/rhymecard.png)

---

# 🏥 Health Avatar Project

개인 의료데이터 통합 관리 플랫폼  
Personal Healthcare Data Platform for Integrated Medical Data Management

### Project Tech Stack

`Healthcare Data Platform` · `EMR Integration` · `PHR Integration` · `Clinical Data Systems` · `Mobile Healthcare Apps (Android)` · `Mobile Healthcare Apps (iOS)` · `Mobile Healthcare Apps (iPadOS)` · `Medical Data Interoperability` · `Clinical Research Systems`

## 📌 Overview

Health Avatar Project는 개인의 의료 데이터를 통합 관리하고 활용하기 위한 **Personal Healthcare Data Platform**입니다.  
병원 **EMR(Electronic Medical Record)** 시스템과 개인의 **PHR(Personal Health Record)** 데이터를 연결하여 환자 중심의 의료데이터 관리 환경을 제공하도록 설계되었습니다.

플랫폼은 의료기관 시스템, 연구 플랫폼, 환자용 모바일 서비스 등 다양한 의료 애플리케이션이 상호 연동될 수 있도록 구성되어 있습니다.  
의료진은 **XNet, DialysisNet, RehabilitationNet**과 같은 전문 의료 애플리케이션을 통해 환자 데이터를 관리할 수 있고, 환자는 **Beans 모바일 앱**을 통해 자신의 건강 정보를 확인하고 관리할 수 있습니다.

또한 **PGxCDS, DOPPS, CKD 연구 관리 시스템**과 연계되어 임상 연구와 의료데이터 분석을 위한 기반 인프라로 활용될 수 있도록 구성했습니다.

## 👨‍💻 My Role

- 프로젝트 핵심 구조와 주요 기능 개발에 깊게 참여
- **전체의 80% 이상 제 손을 거친 프로젝트들 중 하나**
- 플랫폼 핵심 서버, 데이터 연동, 주요 기능 구현을 중심으로 주도적 역할 수행

## 🎬 Demo

![Health Avatar](docs/healthavatarproject.png)

---

# 📊 Clinical Trial Search System

ClinicalTrials.gov 기반 임상연구 데이터 탐색 플랫폼  
Clinical Research Data Exploration Platform based on ClinicalTrials.gov

### Project Tech Stack

`Flask API` · `Elasticsearch` · `SBERT` · `Word2Vec` · `ETL Pipeline` · `JSON Data Processing` · `Vector Search` · `Data Visualization` · `ClinicalTrials.gov Data Processing` · `Large-scale Data Indexing`

## 📌 Overview

Clinical Trial Search System은 **ClinicalTrials.gov** 기반 대규모 임상시험 데이터를 수집·정규화하여 검색, 필터링, 통계 분석, 시각화를 제공하는 **Clinical Research Data Exploration Platform**입니다.

수십만 건 규모의 JSON 임상시험 데이터를 **ETL 파이프라인으로 처리**하여 데이터베이스에 저장하고, 연구자가 실제로 활용할 수 있는 조건 중심 검색 구조를 설계했습니다.  
사용자는 질환, 임상 단계, 국가, 연구 상태, 개입 방식 등 다양한 조건을 기반으로 임상시험 데이터를 탐색할 수 있습니다.

또한 데이터는 **MySQL 기반 구조화 데이터베이스**와 **Elasticsearch 검색 인덱스**를 통해 관리되며, 대규모 임상 데이터에 대한 효율적인 검색과 분석이 가능하도록 구현했습니다.  
REST API와 통계 View 구조를 함께 설계하여 연구 데이터 탐색, 분석, 시각화의 기반 인프라로 활용할 수 있도록 개발했습니다.

## 👨‍💻 My Role

- 프로젝트 **전체 설계 및 구현 100% 직접 수행**
- 데이터 수집, ETL, DB 설계, 검색 인덱싱, API, 시각화 연동까지 전 과정 개발

## 🎬 Demo

![Clinical Trial Search](docs/clinical-trial.png)

---

# 🔎 JGC Search System

의미 기반 학술 논문 검색 시스템  
Context-Aware Academic Paper Search based on Semantic Analysis

### Project Tech Stack

`Elasticsearch` · `SBERT` · `Vector Search` · `BM25` · `Hybrid Search` · `MeSH Vocabulary` · `PubMed API (NCBI E-utilities)` · `PDF Processing` · `NLP` · `Evidence Extraction` · `Local LLM` · `Academic Data Processing`

## 📌 Overview

JGC Search System은 학술 논문의 메타데이터와 전문(full-text)을 기반으로 의미 중심 검색을 제공하는 **Academic Paper Search Platform**입니다.

단순 키워드 검색이 아니라, 논문 문장 단위의 의미를 분석하여 연구 주제와 관련된 논문을 탐색할 수 있도록 설계했습니다.  
논문 데이터는 **PubMed 및 학술 데이터 소스**에서 수집되며, 텍스트 파싱과 데이터 정규화를 통해 검색 가능한 구조로 변환됩니다.

또한 **SBERT 기반 임베딩과 Vector Search 구조**, **BM25 기반 키워드 검색**, **Hybrid Search**, **MeSH Vocabulary 매핑** 등을 활용하여 보다 정교한 학술 검색이 가능하도록 구현했습니다.  
검색 결과에서는 논문 전체가 아니라 **관련 근거 문장(Evidence Snippet)** 을 함께 제공하며, 최근에는 **Local LLM 기반 질의응답 기능**까지 확장하여 검색 결과 요약과 컨텍스트 기반 응답이 가능하도록 발전시켰습니다.

## 👨‍💻 My Role

- 프로젝트 **전체 설계 및 구현 100% 직접 수행**
- 논문 데이터 처리, 검색 구조 설계, 임베딩 기반 검색, Evidence 추출, Local LLM 연계까지 전체 개발

## 🎬 Demo

![JGC Search System](docs/jgc-chatbot.png)

---

## Notes

이 GitHub는 의료데이터 플랫폼, 의료 AI 시스템, 보안 실행 환경, 검색 시스템과 관련된 주요 프로젝트와 기술 아카이브를 정리하기 위한 공개 포트폴리오입니다.  
일부 프로젝트는 보안 또는 연구 환경 특성상 전체 소스 대신 공개 가능한 범위 내에서 구조와 핵심 내용을 정리하여 제공합니다.
