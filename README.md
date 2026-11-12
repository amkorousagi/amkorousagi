# 박세찬 · Sechan Park

**AI/ML Engineer · On-Device Computer Vision · 추론 최적화 (ONNX Runtime · C++)**

<p>
  <a href="mailto:hasmi5452@gmail.com"><img src="https://img.shields.io/badge/Email-hasmi5452@gmail.com-informational?style=flat&logo=gmail"/></a>
  <a href="https://linkedin.com/in/se-chan-park-5a4b84192"><img src="https://img.shields.io/badge/LinkedIn-Sechan_Park-0A66C2?style=flat&logo=linkedin"/></a>
  <a href="https://scholar.google.co.kr/citations?user=V2_eA3cAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-10_papers-4285F4?style=flat&logo=googlescholar"/></a>
</p>

Vision 모델을 실제 제품의 기기 안에서 빠르고 정확하게 돌게 만드는 ML 엔지니어입니다.
[식약처 품목허가](https://www.etoday.co.kr/news/view/2626050) 소아 근시 디지털 치료기기 **MyoHabit**의 시선 추적 파이프라인을 Android·iOS 온디바이스로 설계·운영하고 있습니다.

## 하이라이트

- **시선 갱신 주기 120–300ms → 42–48ms** — 실기기 계측으로 병목이 연산량이 아니라 GPU→CPU 결과 전달임을 찾아 구조 변경
- **C++ 추론 SDK** — ONNX Runtime·TFLite 네이티브 코어를 C API로 감싸 React Native·Unity에 같은 API로 제공. 전용 스레드로 분리해 Galaxy Tab S7 추론 1회 **42.4 → 15.1ms** (화면 47 → 60fps)
- **모델 그래프 최적화** — 레이아웃 통일·양눈 배치 추론·출력 병합으로 갱신 주기 **2~4배**, 모델 크기 **-40%**
- **모델 재설계** — 거리 추정을 홍채 직경 + 초점거리 기준으로 바꿔 최대 오차 **±10cm → 1.1–2.5cm**
- **임상 데이터 모델링** — 임상시험 시선 로그 약 18만 건으로 피처 설계·회귀 모델링 (APOIS 2026 발표)
- **NLP 서빙** — 감정 분류 + 문장 임베딩 추천을 ONNX로 변환해 프로덕션 배포, 추론 **11.33 → 2.61ms**
- **CI/CD** — Jenkins로 Google Play 자동 배포, LLM PR 리뷰봇, 시선 회귀 테스트 49/49 CI 게이트

## 오픈소스 · 프로젝트

- [microsoft/onnxruntime#24096](https://github.com/microsoft/onnxruntime/issues/24096) — onnxruntime-node + Transformers.js segfault 최소 재현·제보 ([재현 코드](https://github.com/amkorousagi/onnxruntime_segfault_example))
- [onnxruntime_flutter (fork)](https://github.com/amkorousagi/onnxruntime_flutter) — 매 프레임 입력 flatten·중간 복사 제거, 프레임당 **14–20ms** 단축
- [UnityPGTA](https://github.com/amkorousagi/UnityPGTA) — 강화학습 게임 테스트 자동화, 오픈소스 게임 3종에서 에러 72건 탐지 (KCC 2023 최우수논문상)
- [KOJ](https://github.com/amkorousagi/KOJ) — 프로그래밍 강의용 온라인 채점 시스템 (조교 시절 구축)

## 기술

**추론 · 온디바이스**  
<img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white"/> <img src="https://img.shields.io/badge/TFLite_(XNNPACK)-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/Android_NDK%2FJNI-34A853?style=flat-square&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/iOS_(Swift)-F05138?style=flat-square&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white"/> <img src="https://img.shields.io/badge/Compute_Shader-5586A4?style=flat-square&logo=opengl&logoColor=white"/>

**ML**  
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>

**엔지니어링**  
<img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

## 연구

논문 10편 · 수상 11건 — 경북대 컴퓨터학부 석사 (GPA 4.38/4.5)
- APOIS 2026 · 소아 근시 치료 중 맥락막 두께 변화 예측 (3저자)
- 정보과학회논문지 2024 · 강화학습을 이용한 게임 테스팅 자동화 (1저자)
- KCC 2023 최우수논문상 · KIPS ASK 2022 우수논문상
