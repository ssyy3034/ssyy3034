# Kwon Dongha (권동하)

> **"OS 레벨의 원리 이해를 바탕으로, 견고하고 최적화된 웹 애플리케이션을 설계하는 프론트엔드 엔지니어"**

단순한 기능 구현을 넘어 시스템의 **가용성(Availability)**과 **유지보수성(Maintainability)**을 최우선 가치로 둡니다.
복잡한 데이터를 시각화하고, 이질적인 데이터 소스를 통합하여 일관된 사용자 경험(UX)을 제공하는 문제 해결에 집중합니다.

<div align="left">
  <a href="mailto:ansqhrl3037@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-4a3b31?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://velog.io/@ansqhrl3037"><img src="https://img.shields.io/badge/Tech_Blog-Velog-8c8279?style=flat-square&logo=velog&logoColor=white" /></a>
  <a href="https://github.com/ssyy3034"><img src="https://img.shields.io/badge/GitHub-Profile-24201e?style=flat-square&logo=github&logoColor=white" /></a>
</div>

---

## 🏗️ Engineering Impact (Projects)

### [StoLink (Project Authorius)](https://github.com/ssyy3034/YOUR_REPO_LINK_HERE)
**작가용 지능형 웹 에디터 및 세계관 시각화 서비스**
> *Role: Frontend Lead & System Design*

* **Problem:** MongoDB(비정형)와 RDB(정형) 간의 데이터 스키마 불일치로 인한 프론트엔드 상태 관리 복잡도 증가 및 대규모 그래프 렌더링 시 프레임 드랍 발생.
* **Solution:**
    * **Adapter Pattern 적용:** 데이터 계층(Data Layer)과 뷰 계층(View Layer) 사이에 정규화된 어댑터를 설계하여 **데이터 처리 로직의 응집도** 향상.
    * **비동기 처리 최적화:** RabbitMQ 및 WebSocket을 도입하여 대용량 텍스트 처리 시 UI 블로킹(Blocking) 없는 실시간 동기화 구현.
* **Tech Stack:** React, Next.js, TypeScript, Recoil, D3.js

### [Knowledge Garden](https://github.com/ssyy3034/my-knowledge-garden)
**개인 지식 관리(PKM) 데이터 시각화 파이프라인**
> *Role: Sole Developer*

* **Engineering Focus:** Obsidian의 Markdown 데이터를 파싱하여 Next.js 환경에서 인터랙티브 그래프로 시각화.
* **Performance:** D3.js의 Force Simulation 연산 최적화를 통해 노드 [000]개 이상의 그래프에서도 안정적인 **60 FPS** 유지.
* **Tech Stack:** Next.js, D3.js, Web Worker

---

## 💻 Technical Philosophy & Skills

프론트엔드 기술뿐만 아니라 **Computer Science (OS, Network)** 기초를 기반으로 문제의 본질(Root Cause)을 파악합니다.

### 🛠 Tech Stack
| Domain | Stack |
| :--- | :--- |
| **Frontend Core** | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) |
| **Data & Visual** | ![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat-square&logo=d3.js&logoColor=white) ![Recoil](https://img.shields.io/badge/-Recoil-3578E5?style=flat-square&logo=recoil&logoColor=white) |
| **CS Foundation** | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |

### 🧠 Core Competencies

**1. Deep Dive into System (OS & Memory)**
* **KAIST Pintos Project:** 가상 메모리(Virtual Memory)의 Paging 기법과 스레드 스케줄링(Scheduling)을 C언어로 직접 구현.
* 이러한 Low-level 경험을 바탕으로 브라우저의 **메모리 누수(Memory Leak) 디버깅** 및 **JS 실행 컨텍스트(Execution Context)** 최적화에 강점이 있음.

**2. Single Source of Truth (SSOT) Architecture**
* 복잡한 비즈니스 로직을 UI 컴포넌트와 분리하고, 예측 가능한 상태 관리(State Management) 시스템을 구축하여 유지보수 비용을 최소화함.

---

## 🚀 Problem Solving
<a href="https://solved.ac/ssyy3034">
  <img src="http://mazandi.herokuapp.com/api?handle=ssyy3034&theme=warm" height="110" alt="Solved.ac Badge"/>
</a>
