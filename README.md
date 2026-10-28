<div align="center">

<img src="assets/shuckle-avatar.png" width="112" alt="코딩하는 단단지" />

# 👋 안녕하세요, 곽윤석입니다

**Kwak Yunsuk · PUVKID**

이미지 속 작은 차이를 찾고, 궁금한 아이디어를 코드로 직접 만들어 봅니다.<br>
컴퓨터 비전과 딥러닝을 중심으로 연구하며, 센서부터 데스크톱 앱과 게임까지 관심을 넓혀 가고 있습니다.

🔬 논문에서 시작한 질문을 실험으로 확인하고,<br>
💻 어떤 방법을 구현했는지, 결과는 어땠는지 코드와 함께 남깁니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white)

[👁️ 컴퓨터 비전](#computer-vision) · [💬 비전·언어 연결](#vision-language) · [📝 자연어 처리](#nlp) · [🧭 추천 시스템](#recommenders) · [📈 시계열 ML](#time-series)<br>
[🌿 임베디드·IoT](#embedded) · [🖥️ 데스크톱](#desktop) · [📱 Android 자동화](#android) · [🎮 게임](#game)

<img src="assets/shuckle-coding-friends.png" width="100%" alt="코딩하는 단단지와 친구들" />

</div>

---

<a name="computer-vision"></a>

## 👁️ 컴퓨터 비전

이미지를 분류하고, 작은 객체를 찾고, 위치와 움직임을 살펴봅니다. 프로젝트마다 어떤 문제를 어떤 방법으로 풀었는지 나누어 정리했습니다.

### 🧠 딥러닝 영상 분류

**[🫁 폐암 영상 분류와 프라이버시 변환 실험](https://github.com/PUVKID/Lung-CT-Privacy-Project)**  
영상을 흐리게 하거나 블록을 재배열하면 분류 성능은 얼마나 달라질까요? EfficientNetV2-S 하계 연구와 ResNet50 후속 연구를 구분해, 입력·특징 변환에 따른 분류 지표와 Privacy Score, 구조 유사도를 살펴봅니다. 조건별 비교 그래프와 연구 단계별 설명을 함께 읽을 수 있습니다.

**[🏭 카메라 모듈 정상·불량 영상 분류](https://github.com/PUVKID/Camera-Module-Anomaly-Project)**  
카메라 모듈의 정상·불량을 구분하는 원고입니다. YOLO·ViT·CNN의 분류 성능과 처리시간을 비교하며, F1과 시간 지표를 표와 그래프로 정리했습니다.

### 🎯 딥러닝 객체 검출

**[🔎 볼 결함 탐지와 영상 필터 비교](https://github.com/PUVKID/Ball-Defect-Detection-Project)**  
작은 볼 결함을 더 잘 찾기 위해 YOLOv8n과 단일·복합 영상 필터를 비교합니다. 중복 그룹을 고려한 데이터 분할과 다중 시드 실험을 다루며, 검출 지표·Strict Acc·별도의 OK/NG 판정을 구분해 설명합니다.

**[🚶 SafeWalk 보행환경 객체 탐지](https://github.com/PUVKID/SafeWalk-Object-Detection-Project)**  
여러 데이터셋의 클래스 ID를 하나로 맞춰 보행환경의 8개 클래스를 탐지합니다. YOLOv8x의 클래스별 학습부터 전체 미세조정까지, 데이터 통합·학습·평가·영상 데모의 흐름을 담았습니다.

### 🎬 객체 검출·추적

**[🧹 클린뷰 불법투기 쓰레기 탐지](https://github.com/PUVKID/Illegal-Dumping-Detection-Project)**  
영상에서 물체를 찾은 뒤, 같은 물체가 멈춰 있는 시간과 주변 사람의 이탈 조건을 함께 살펴봅니다. YOLO 검출과 IoU 연결로 검토할 이벤트 후보를 만들고, 결과 영상·CSV·보고서로 확인합니다.

### 📐 기하 정렬·영상 처리

**[📏 카메라 모듈 갭 검출](https://github.com/PUVKID/Camera-Module-Gap-Detection-Project)**  
기준 위치를 찾고 ROI를 정렬한 뒤, 영역별 필터와 이진화로 틈을 측정합니다. 주사선에서 얻은 갭의 위치·길이와 검사 지표를 다루는 영상 처리 원고입니다.

<a name="vision-language"></a>

## 💬 컴퓨터 비전·자연어 처리 연결

### 🖼️ 검출 결과를 대화로 연결하기

**[🎨 그림 객체 탐지와 AI 분석 리포트](https://github.com/PUVKID/Drawing-Analysis-Project)**  
YOLO가 찾은 객체의 유무를 텍스트로 요약하고, GPT-4o-mini 요청에 연결합니다. 데이터 생성·학습·API를 포함한 Python 구현과, 대화 메시지·입력 그림을 담는 PDF 생성 흐름을 볼 수 있습니다.

**[🗨️ 그림 객체 탐지와 미술치료 대화 프로토타입](https://github.com/PUVKID/Art-Therapy-Dialogue-Project)**  
같은 연구 계열의 최종 원고와 대화 앱, 평가 점수 시각화를 모았습니다. YOLO 탐지 요약을 LLM 대화에 연결하는 방법과 점수의 기술통계를 함께 살펴볼 수 있습니다.

두 저장소는 구현 자료와 원고·평가 자료를 나누어 보관합니다. 이미지 자체를 언어 모델에 직접 넣는 방식과 구별해, 탐지 요약이 대화로 이어지는 과정을 설명합니다.

<a name="nlp"></a>

## 📝 자연어 처리

### 💭 감성·콘텐츠 분류

**[⚡ 포켓몬 30주년·브랜드 리뷰 감성 분석](https://github.com/PUVKID/Pokemon-Brand-Analysis-Project)**  
리뷰와 콘텐츠를 분류하고, 결과를 통계와 그래프로 살펴봅니다. 규칙 기반 처리와 선택적으로 사용하는 언어 모델·다국어 감성 분류를 구분하며, CSV·Excel 결과를 사람이 검수하는 흐름도 담았습니다.

<a name="recommenders"></a>

## 🧭 추천 시스템

### 🧩 사례 기반 추론

**[🕹️ ADHD 청소년 디지털 놀이치료 추천](https://github.com/PUVKID/ADHD-Play-Therapy-Project)**  
비슷한 사례를 찾아 디지털 놀이치료 콘텐츠를 추천하는 방법을 설계한 원고입니다. 사례 기반 추론(CBR)으로 유사 사례를 검색하고 게임을 추천하는 절차를 따라갈 수 있습니다.

### 🕸️ 그래프 신호 처리

**[⭐ 사용자 평점 기반 그래프 추천](https://github.com/PUVKID/Rating-Aware-Recommendation-Project)**  
HiGSP를 바탕으로 두 그래프의 필터 점수를 결합해 추천 순위를 만드는 연구입니다. 사용자 평점을 반영하는 방식과 NDCG·MRR 평가를 설명합니다. 그래프 신호 처리 방법으로, GNN과 구분해 정리했습니다.

<a name="time-series"></a>

## 📈 시계열 머신러닝

### 🌳 트리 앙상블

**[🪙 업비트 5종목 모의투자 연구](https://github.com/PUVKID/Upbit-Paper-Trading-Project)**  
시계열 특성을 만들고 구간을 나누어 XGBoost 모델과 확률 보정을 살펴봅니다. 모델 선택·평가부터 주문장 기반 모의체결, 모의계좌와 대시보드까지 연결한 프로젝트입니다.

<a name="embedded"></a>

## 🌿 임베디드·IoT

### 🔌 센서 통신

**[🍃 아두이노 실내공기질 모니터링](https://github.com/PUVKID/Indoor-Air-Monitor-Project)**  
Arduino가 I²C 센서를 읽고, LCD와 RGB LED로 실내 환경을 보여줍니다. PC에서는 UART 데이터를 검사해 수신 시각과 함께 CSV로 기록합니다.

🤝 [ICT-IndoorAD](https://github.com/ICT-IndoorAD) 공동 프로젝트에서 제가 작성한 Arduino 측정·LCD·LED 표시와 Python CSV 기록 부분입니다. [개인 담당 저장소](https://github.com/ICT-IndoorAD/Yunsuk-Kwak)에서도 확인하실 수 있습니다.

<a name="desktop"></a>

## 🖥️ 데스크톱 소프트웨어

### 🛍️ Windows Forms·브라우저 자동화

**[📦 EXP 번장 상품 등록·관리](https://github.com/PUVKID/EXP-Product-Manager-Project)**  
WinForms에서 상품을 편집하고 Selenium으로 등록 흐름을 연결합니다. 예약·진행 상태·라이선스·사용량 관리가 차수별로 어떻게 바뀌었는지, 상품 처리 결과와 운영 기록을 어떻게 다루는지 정리했습니다.

### 📄 Qt·문서 처리

**[🔄 플립링 파일 변환·PDF 도구](https://github.com/PUVKID/FlipRing-File-Converter-Project)**  
PySide6 화면에서 파일을 변환하고 PDF 페이지를 편집합니다. 변환 엔진·외부 도구와 Tesseract OCR을 연결해 새 형식의 파일, 편집 PDF, 인식 문서를 만드는 Windows 앱입니다.

<a name="android"></a>

## 📱 Android 자동화

### 👆 접근성·화면 인식

**[🤖 PXE 안드로이드 터치 매크로](https://github.com/PUVKID/PXE-Touch-Macro-Project)**  
AccessibilityService와 ML Kit OCR로 화면의 글자를 확인하고, 조건에 맞는 터치를 실행합니다. 제스처 실행과 플로팅 상태 표시, 로그가 이어지는 과정을 차수별 코드와 함께 볼 수 있습니다.

<a name="game"></a>

## 🎮 게임 프로그래밍

### 🕹️ Unity 게임플레이

**[🕳️ Hole It 흡수·성장 게임](https://github.com/PUVKID/Hole-It-Game-Project)**  
이동하고, 부딪히고, 물체를 흡수하며 성장하는 Unity 게임입니다. 이동·충돌·흡수 로직부터 성장·레벨·로컬 보상과 저장까지, 게임의 진행 흐름을 코드와 기존 화면으로 살펴볼 수 있습니다.

---

<div align="center">

**🌱 궁금한 것은 실험하고, 배운 것은 코드로 남깁니다.**<br>
프로젝트를 열면 사용한 방법과 차수별 변화, 확인한 결과를 함께 보실 수 있습니다.

</div>
