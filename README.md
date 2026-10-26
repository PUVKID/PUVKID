<div align="center">

<img src="assets/shuckle-avatar.png" width="112" alt="코딩하는 단단지" />

# 안녕하세요, 곽윤석입니다

**Kwak Yunsuk · PUVKID**

컴퓨터 비전과 딥러닝을 연구하고, 아이디어를 소프트웨어로 구현합니다.<br>
논문에서 다룬 방법을 코드와 연결하고, 실험 조건과 결과를 함께 기록합니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white)

[컴퓨터 비전](#computer-vision) · [비전·언어 연결](#vision-language) · [자연어 처리](#nlp) · [추천 시스템](#recommenders) · [시계열 ML](#time-series)<br>
[임베디드·IoT](#embedded) · [데스크톱](#desktop) · [Android 자동화](#android) · [게임](#game)

<img src="assets/shuckle-coding-friends.png" width="100%" alt="코딩하는 단단지와 친구들" />

</div>

---

<a name="computer-vision"></a>

## 컴퓨터 비전

### 딥러닝 영상 분류

**[폐암 영상 분류와 프라이버시 변환 실험](https://github.com/PUVKID/Lung-CT-Privacy-Project)** — 입력·특징 변환과 프라이버시 평가  
처리: EfficientNetV2-S·ResNet50 분류, 블러·블록 변환, 구조 유사도 비교.  
산출물: 조건별 분류 지표·Privacy Score·그래프.

**[카메라 모듈 정상·불량 영상 분류](https://github.com/PUVKID/Camera-Module-Anomaly-Project)** — CNN·Vision Transformer 비교  
처리: 원고에서 YOLO·ViT·CNN 분류 성능과 처리시간 비교.  
산출물: F1·처리시간 비교표와 그래프.

### 딥러닝 객체 검출

**[볼 결함 탐지와 영상 필터 비교](https://github.com/PUVKID/Ball-Defect-Detection-Project)** — 소형 객체·전처리 강건성  
처리: YOLOv8n, 단일·복합 필터, 중복 그룹 분할·다중 시드 비교.  
산출물: 검출 지표·Strict Acc·별도 OK/NG 판정.

**[SafeWalk 보행환경 객체 탐지](https://github.com/PUVKID/SafeWalk-Object-Detection-Project)** — 다중 데이터셋·8클래스 통합  
처리: 클래스 ID 통합, YOLOv8x 클래스별 학습과 전체 미세조정.  
산출물: 8클래스 탐지·평가·영상 데모.

### 객체 검출·추적

**[클린뷰 불법투기 쓰레기 탐지](https://github.com/PUVKID/Illegal-Dumping-Detection-Project)** — 정지·주변 사람 조건의 이벤트 후보  
처리: YOLO 검출과 IoU 연결, 정지 시간·사람 이탈 조건.  
산출물: 검토 후보·결과 영상·CSV·보고서.

### 기하 정렬·영상 처리

**[카메라 모듈 갭 검출](https://github.com/PUVKID/Camera-Module-Gap-Detection-Project)** — ROI·이진화·1차원 갭 측정  
처리: 기준 위치 검출·ROI 정렬, 영역별 필터·임계값, 주사선 길이 측정.  
산출물: 갭 위치·길이와 검사 지표.

폐 CT 연구는 EfficientNetV2-S 하계 연구와 ResNet50 후속 연구를 한 저장소 안에서 구분합니다. 기하 정렬·임계값 기반 측정과 딥러닝 분류·검출도 각각의 방법으로 설명합니다.

<a name="vision-language"></a>

## 컴퓨터 비전·자연어 처리 연결

### 검출·언어 모델 연결

**[그림 객체 탐지와 AI 분석 리포트](https://github.com/PUVKID/Drawing-Analysis-Project)** — 그림 탐지 요약→대화·PDF  
처리: YOLO 탐지 여부 요약을 GPT-4o-mini 텍스트 요청에 연결.  
산출물: 대화 메시지·입력 그림을 담은 PDF.

**[그림 객체 탐지와 미술치료 대화 프로토타입](https://github.com/PUVKID/Art-Therapy-Dialogue-Project)** — 그림 대화 원고·평가 시각화  
처리: YOLO 탐지 요약·LLM 대화·PDF, 점수 기술통계.  
산출물: 대화 앱·논문·평가 그래프.

두 저장소는 같은 연구 계열입니다. 첫 번째는 데이터 생성·학습·API를 포함한 Python 구현, 두 번째는 최종 원고·대화 앱·점수 시각화 자료를 보관합니다.

<a name="nlp"></a>

## 자연어 처리

### 감성·콘텐츠 분류

**[포켓몬 30주년·브랜드 리뷰 감성 분석](https://github.com/PUVKID/Pokemon-Brand-Analysis-Project)** — 규칙·다국어 모델과 검수  
처리: 규칙 또는 선택 언어 모델·다국어 감성 분류, 통계와 검수.  
산출물: 분류 CSV·Excel·비교 그래프.

<a name="recommenders"></a>

## 추천 시스템

### 사례 기반 추론

**[ADHD 청소년 디지털 놀이치료 추천](https://github.com/PUVKID/ADHD-Play-Therapy-Project)** — 유사 사례의 게임 추천  
처리: 유사 사례 검색과 CBR 추천 알고리즘 설계.  
산출물: 디지털 놀이치료 콘텐츠 추천 절차.

### 그래프 신호 처리

**[사용자 평점 기반 그래프 추천](https://github.com/PUVKID/Rating-Aware-Recommendation-Project)** — 평점 반영 이중 그래프 필터  
처리: HiGSP 기반 두 그래프·필터 점수 결합.  
산출물: 추천 순위와 NDCG·MRR 지표.

<a name="time-series"></a>

## 시계열 머신러닝

### 트리 앙상블

**[업비트 5종목 모의투자 연구](https://github.com/PUVKID/Upbit-Paper-Trading-Project)** — XGBoost·확률 보정·모의체결  
처리: 시계열 특성·구간 분리, XGBoost·보정·모델 선택.  
산출물: 모의계좌·평가·대시보드.

<a name="embedded"></a>

## 임베디드·IoT

### 센서 통신

**[아두이노 실내공기질 모니터링](https://github.com/PUVKID/Indoor-Air-Monitor-Project)** — I²C·UART·표시·CSV  
처리: Arduino I²C 센싱·LCD·LED, UART 수신 검사.  
산출물: 측정 화면·RGB 표시·타임스탬프 CSV.

[ICT-IndoorAD](https://github.com/ICT-IndoorAD) 공동 프로젝트에서 제가 작성한 Arduino 측정·LCD·LED 표시와 Python CSV 기록 부분입니다. [개인 담당 저장소](https://github.com/ICT-IndoorAD/Yunsuk-Kwak)로도 연결됩니다.

<a name="desktop"></a>

## 데스크톱 소프트웨어

### Windows Forms·브라우저 자동화

**[EXP 번장 상품 등록·관리](https://github.com/PUVKID/EXP-Product-Manager-Project)** — Selenium·예약·상태 관리  
처리: WinForms 편집, Selenium 등록, 진행·라이선스·사용량 제어.  
산출물: 상품 처리 상태·등록 결과·운영 기록.

### Qt·문서 처리

**[플립링 파일 변환·PDF 도구](https://github.com/PUVKID/FlipRing-File-Converter-Project)** — 파일 변환·PDF·OCR  
처리: PySide6 UI, 변환 엔진·외부 도구, 페이지 편집·Tesseract OCR.  
산출물: 새 형식 파일·편집 PDF·인식 문서.

<a name="android"></a>

## Android 자동화

### 접근성·화면 인식

**[PXE 안드로이드 터치 매크로](https://github.com/PUVKID/PXE-Touch-Macro-Project)** — OCR·조건 기반 터치 실행  
처리: AccessibilityService·ML Kit OCR·글자 조건·제스처.  
산출물: 터치 실행·플로팅 상태·로그.

<a name="game"></a>

## 게임 프로그래밍

### Unity 게임플레이

**[Hole It 흡수·성장 게임](https://github.com/PUVKID/Hole-It-Game-Project)** — 물리·흡수·성장·상태  
처리: Unity 이동·충돌·흡수, 성장·레벨·로컬 보상.  
산출물: 게임 화면·진행 상태·로컬 저장.

---

<div align="center">

**구현한 방법과 확인한 결과를 함께 남깁니다.**

</div>
