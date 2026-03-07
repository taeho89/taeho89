## 안녕하세요! 개발자 곽태호입니다. 👋

## 🎓 Education & Activities

- **경기대학교 (Kyeonggi University)** | 컴퓨터공학과 재학 중
- **42 Gyeongsan** | Common Core (공통 교육 과정) 수료, Transcendence 수행 중

## 🛠️ Tech Stack

### 🔹 Languages
<img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" /> <img src="https://img.shields.io/badge/Assembly-000000?style=for-the-badge&logo=assemblyscript&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white" />

### 🔹 AI & Backend
<img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white" /> <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" /> <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" /> <img src="https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white" />

### 🔹 Frontend & Mobile
<img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" /> <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" /> <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" />

### 🔹 Infrastructure & Tools
<img src="https://img.shields.io/badge/AWS_Amplify-FF9900?style=for-the-badge&logo=aws-amplify&logoColor=white" /> <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" /> <img src="https://img.shields.io/badge/Git_LFS-F05032?style=for-the-badge&logo=git&logoColor=white" />

---

## 🚀 Featured Projects

### 🗄️ [Locker Checker (AI 사물함 상태 판별 시스템)](https://github.com/42-Gy/ft_cabinet_AI)
- **개요:** 딥러닝(EfficientNetV2-S)을 활용하여 사물함의 점유 상태(EMPTY / OCCUPIED / INVALID)를 식별하는 API 서비스.
- **주요 성과:** 데이터 증강(22종) 및 80% Center Crop 전처리를 통해 **전체 정확도 98.7% (EMPTY 100%)** 달성. Grad-CAM을 적용하여 모델의 판단 근거 시각화.
- **아키텍처:** FastAPI를 이용해 평균 15ms 추론 속도의 예측 API를 구축하고, Spring Boot 기반의 테스트 웹앱을 연동하여 데이터 수집 및 UI 테스트 환경 마련. (Git LFS로 모델 파일 파이프라인 구축)

### 📱 [실시간 데이팅 앱 (Flutter & AWS Amplify)](https://github.com/taeho89/Pick)
- **개요:** AI 사용자 얼굴 인식 및 실시간 채팅 기능을 제공하는 모바일 애플리케이션.
- **아키텍처 유연성:** 초기 Clean Architecture 도입 후, 팀원 피드백을 수용하여 **MVVM 패턴으로 간소화 (코드 복잡도 20% 절감, 버그 수정 시간 단축)**.
- **인프라 마이그레이션:** Firebase 한계 극복을 위해 **AWS Amplify(AppSync, Lambda)**로 전환하고, WebSocket 기반 실시간 통신 시스템 구축.

### 🏓 [Pong Service (풀스택 실시간 멀티플레이어 웹)](https://github.com/taeho89/pongservice)
- **개요:** 유저 간 실시간 탁구 게임 및 채팅 시스템을 제공하는 SPA 기반 웹 서비스.
- **주요 기술:** Vite + TypeScript 프론트엔드, Node.js + Express + Prisma 백엔드, WebSocket(Socket.io) 실시간 동기화.

### ⚙️ 시스템 및 네트워크 코어 구현 (C / Assembly)
- **[ft_ping](https://github.com/taeho89/ft_ping) & [ft_traceroute](https://github.com/taeho89/ft_traceroute)**: RFC 1071 표준 ICMP 체크섬 구현 및 Raw Socket 통신 분석 도구 직접 개발.
- **[minishell](https://github.com/taeho89/minishell)**: 프로세스 제어와 IPC 메커니즘을 C언어로 재현한 UNIX 쉘 프로젝트.
- **[libasm](https://github.com/taeho89/libasm)**: x86-64 어셈블리어로 표준 C 라이브러리 재구현.
- **[ft_ls](https://github.com/taeho89/ft_ls)**: 파일 시스템 API를 활용한 디렉토리 탐색 및 메타데이터 출력 로직 구현.

<br>

<div align="left">
  <a href="https://solved.ac/taeho0809">
    <img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=taeho0809" alt="Baekjoon Tier" height="150" />
  </a>
</div>

<br>


