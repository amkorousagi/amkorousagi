# 박세찬 · Sechan Park

**AI/ML Engineer · On-Device Computer Vision · NLP · 추론 최적화 (ONNX Runtime · C++)**

<a href="https://amkorousagi.github.io"><img src="https://img.shields.io/badge/CV-amkorousagi.github.io-222222?style=flat-square&logo=githubpages&logoColor=white"/></a> <a href="https://linkedin.com/in/se-chan-park-5a4b84192"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg=="/></a> <a href="https://scholar.google.co.kr/citations?user=V2_eA3cAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white"/></a> <a href="mailto:hasmi5452@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>

온디바이스 Computer Vision·NLP 시스템을 설계·개발해 제품에 배포해 온 AI/ML 엔지니어입니다.
[식약처 품목허가](https://www.etoday.co.kr/news/view/2626050) 소아 근시 디지털 치료기기 **MyoHabit**의 시선 추적 파이프라인을 Android·iOS 온디바이스로 설계·개발하고 운영하며, React Native·Unity 공용 C++ 추론 SDK와 추론 최적화를 구현했습니다. PTSD 치료 앱에서는 감정 분류와 문장 임베딩을 결합한 유사도 검색 기반 치료 문장 추천 시스템을 설계·구현해 프로덕션에 배포했습니다.

## 경력

- **2024.01 – 현재** · 에스알파테라퓨틱스 — AI Center 연구원 (Manager, 2024.12–) · Research & Science Team Head (2024.04–12) · Unity/AI 개발자 (2024.01–04)  
  온디바이스 시선 추적, C++ 추론 SDK, 임상 데이터 모델링, NLP 추천
- **2022.03 – 2024.02** · 경북대학교 소프트웨어 테스팅 연구실 석사과정 연구원 — 강화학습 게임 테스트 자동화, 섬유 물성 예측 ML

## 하이라이트

- **시선 파이프라인 구조 개선** — 실기기 프로파일링으로 병목이 연산량이 아니라 GPU→CPU 결과 전달임을 찾아 출력·백엔드 구조를 바꿈
- **C++ 추론 SDK** — 렌더링과 분리된 전용 스레드에서 도는 네이티브 코어(ONNX Runtime·TFLite)를 C API로 감싸 React Native·Unity에 같은 API로 제공
- **출력이 같은 최적화** — 그래프 정리·런타임 선택·전처리 재구성으로 결과값을 바꾸지 않고 추론 시간 단축, 정확도가 바뀌는 양자화는 측정 후 기각
- **실데이터 기반 모델 개선** — 홍채 직경 기반 거리 추정 재설계, 피험자 단위 교차검증으로 판정 모델 재적합

## 학력

- **경북대학교 대학원 컴퓨터학부 석사** · 2022.03 – 2024.02 · GPA 4.38/4.5
- **경북대학교 컴퓨터학부 학사** · 2018.03 – 2022.02

## 논문 · 수상

논문 10편 · 수상 11건 — 전체 목록은 [Google Scholar](https://scholar.google.co.kr/citations?user=V2_eA3cAAAAJ) · [LinkedIn](https://linkedin.com/in/se-chan-park-5a4b84192)

- **APOIS 2026** · 소아 근시 치료 중 맥락막 두께 변화 예측 디지털 바이오마커 (3저자)
- **정보과학회논문지 2024** · UnityPGTA, 강화학습을 이용한 게임 테스팅 자동화 (1저자)
- **KIPS TSDE 2022** · 데이터 불균형과 측정 오차를 고려한 섬유 강신도 예측 (1저자)
- **KCC 2023 최우수논문상** · **KIPS-AOH 2022 논문아이디어상** · **KIPS ASK 2022 우수논문상**
- **K-water 빅데이터 공모전 최우수상(사장상)** · **대경권 대학생 프로그래밍 경진대회 최우수상** · NAVER AI RUSH 2021 1라운드 8위

## 오픈소스 · 프로젝트

- [microsoft/onnxruntime#24096](https://github.com/microsoft/onnxruntime/issues/24096) — onnxruntime-node + Transformers.js segfault 최소 재현·제보 ([재현 코드](https://github.com/amkorousagi/onnxruntime_segfault_example))
- [onnxruntime_flutter (fork)](https://github.com/amkorousagi/onnxruntime_flutter) — 매 프레임 입력 flatten·중간 복사 제거, 프레임당 **14–20ms** 단축
- [MobileCameraPlacementDB](https://github.com/amkorousagi/MobileCameraPlacementDB) — 태블릿·모바일 기기별 전면 카메라 위치 DB
- [UnityPGTA](https://github.com/amkorousagi/UnityPGTA) — 강화학습 게임 테스트 자동화, 오픈소스 게임 3종에서 에러 72건 탐지 (KCC 2023 최우수논문상)
- [KOJ](https://github.com/amkorousagi/KOJ) — 프로그래밍 강의용 온라인 채점 시스템 (조교 시절 구축)

## 기술

**추론 · 온디바이스**  
<img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white"/> <img src="https://img.shields.io/badge/TFLite_(XNNPACK)-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/Android_NDK%2FJNI-34A853?style=flat-square&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/Compute_Shader-5586A4?style=flat-square&logo=opengl&logoColor=white"/>

**ML · 데이터**  
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white"/>

**언어 · 플랫폼**  
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/> <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white"/> <img src="https://img.shields.io/badge/SQL_(MySQL)-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white"/>

**엔지니어링**  
<img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
