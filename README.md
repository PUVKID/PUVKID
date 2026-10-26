<div align="center">

<img src="assets/shuckle-avatar.png" width="112" alt="코딩하는 단단지" />

# Kwak Yunsuk · 곽윤석

### 폐 CT 영상 변환 · 제조 영상 검사 · 그림 분석 대화

블러·블록 재배열에 따른 폐 CT 분류 변화와 제조 영상의 볼·갭 검출을 연구합니다.<br>
센서 측정·CSV 기록, 파일 변환과 화면 인식·터치 자동화 프로그램도 만들고 있습니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white)

[폐 CT](#lung) · [제조 검사](#inspection) · [그림 대화](#drawing) · [추천](#recommendation) · [공기질](#air) · [거리 영상](#street)<br>
[콘텐츠 감성](#content) · [모의투자](#trading) · [Windows 도구](#windows) · [Android 자동화](#android) · [Unity 게임](#unity)

<img src="assets/shuckle-coding-friends.png" width="100%" alt="코딩하는 단단지와 친구들" />

</div>

---

<a name="lung"></a>

## 🫁 폐 CT 영상 변환·딥러닝 분류

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [폐암 영상 분류와 프라이버시 변환 실험](https://github.com/PUVKID/Lung-CT-Privacy-Project) | ResNet50·블러·블록 재배열 조건의 폐 CT 분류와 MS-SSIM 기반 비유사도 분석 |

EfficientNetV2-S 하계 연구와 ResNet50 후속 연구를 한 프로젝트 안에서 연구 단계별로 연결합니다. 영상 비유사도 지표와 복원 공격에 대한 안전성은 구분하여 설명합니다.

<a name="inspection"></a>

## 🔎 카메라 모듈 검사·볼 결함 판정

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [볼 결함 탐지와 영상 필터 비교](https://github.com/PUVKID/Ball-Defect-Detection-Project) | YOLOv8n 볼 검출의 단일·복합 필터, 중복 그룹 분할·다중 시드·노이즈 비교와 별도 OK/NG 판정 코드 |
| [카메라 모듈 정상·불량 영상 분류](https://github.com/PUVKID/Camera-Module-Anomaly-Project) | YOLO·Vision Transformer·CNN의 카메라 모듈 정상·불량 분류 비교 원고 |
| [카메라 모듈 갭 검출](https://github.com/PUVKID/Camera-Module-Gap-Detection-Project) | 동적 ROI 정렬, 영역별 영상 필터·이진화와 주사선 기반 갭 측정 연구 원고 |

<a name="drawing"></a>

## 🎨 그림 객체 검출·공감형 대화

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [그림 객체 탐지와 AI 분석 리포트](https://github.com/PUVKID/Drawing-Analysis-Project) | 그림 생성·YOLO 학습·대화·PDF·API 진입점을 보관한 Python 구현 저장소 |
| [그림 객체 탐지와 미술치료 대화 프로토타입](https://github.com/PUVKID/Art-Therapy-Dialogue-Project) | 같은 그림 분석 연구의 최종 원고, 대화 앱과 점수 시각화 노트북을 모은 논문·분석 저장소 |

<a name="recommendation"></a>

## 🧩 CBR 게임 추천·평점 그래프 필터

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [ADHD 청소년 디지털 놀이치료 추천](https://github.com/PUVKID/ADHD-Play-Therapy-Project) | CBR 사례 유사도를 이용한 놀이치료 콘텐츠 추천 알고리즘의 학술대회 원고 |
| [사용자 평점 기반 그래프 추천](https://github.com/PUVKID/Rating-Aware-Recommendation-Project) | 사용자 평점을 반영한 이중 그래프 필터링과 추천 순위 지표 비교 원고 |

<a name="air"></a>

## 🌿 공기질 측정·CSV 기록

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [아두이노 실내공기질 모니터링](https://github.com/PUVKID/Indoor-Air-Monitor-Project) | DHT11·AM1008W-K 측정값을 LCD·RGB LED로 표시하고 Python으로 CSV 기록 |

[ICT-IndoorAD](https://github.com/ICT-IndoorAD) 공동 프로젝트에서 제가 작성한 Arduino 측정·LCD·LED 표시와 Python CSV 기록 부분입니다. [공동 프로젝트의 개인 담당 저장소](https://github.com/ICT-IndoorAD/Yunsuk-Kwak)에서도 해당 범위를 확인할 수 있습니다.

<a name="street"></a>

## 🚶 보행환경·방치 쓰레기 객체 탐지

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [SafeWalk 보행환경 객체 탐지](https://github.com/PUVKID/SafeWalk-Object-Detection-Project) | 보행자·횡단보도·계단·차량 등 8개 클래스의 YOLO 학습과 데이터 통합 실험 |
| [클린뷰 불법투기 쓰레기 탐지](https://github.com/PUVKID/Illegal-Dumping-Detection-Project) | 쓰레기 탐지 데이터 준비·YOLO 학습·영상 추론·로컬 확인 화면을 연결한 컴퓨터 비전 프로젝트 |

<a name="content"></a>

## 💬 포켓몬 콘텐츠·브랜드 감성

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [포켓몬 30주년·브랜드 리뷰 감성 분석](https://github.com/PUVKID/Pokemon-Brand-Analysis-Project) | 브랜드 리뷰와 포켓몬 30주년 콘텐츠의 수집·감성 점수·소셜 NPS 시각화 노트북 |

<a name="trading"></a>

## 📈 시세 예측·모의투자

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [업비트 5종목 모의투자 연구](https://github.com/PUVKID/Upbit-Paper-Trading-Project) | 공개 시세 수집, XGBoost 학습, 현물 모의투자와 대시보드를 연결한 연구 시스템 |

<a name="windows"></a>

## 🪟 Windows 상품 등록·파일 변환

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [EXP 번장 상품 등록·관리](https://github.com/PUVKID/EXP-Product-Manager-Project) | C# Windows 앱에서 상품 등록 흐름과 라이선스·사용량 관리를 구성한 EXP 프로젝트 |
| [플립링 파일 변환·PDF 도구](https://github.com/PUVKID/FlipRing-File-Converter-Project) | 원형 메뉴와 트레이에서 이미지·문서·미디어 변환 및 PDF 도구를 사용하는 Windows 앱 |

<a name="android"></a>

## 📱 Android 화면 인식·터치 자동화

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [PXE 안드로이드 터치 매크로](https://github.com/PUVKID/PXE-Touch-Macro-Project) | 터치 동작 편집·재생과 플로팅 컨트롤을 제공하는 Android Java 앱 |

<a name="unity"></a>

## 🎮 Unity 흡수·성장 게임

| 프로젝트 | 다루는 내용 |
| :--- | :--- |
| [Hole It 흡수·성장 게임](https://github.com/PUVKID/Hole-It-Game-Project) | 물체를 흡수하며 성장하는 홀과 레벨·미션·점수 시스템을 구현한 Unity 게임 |

---

<div align="center">

**무엇을 구현했고, 어떤 조건에서 비교했는지 기록합니다.**

</div>
