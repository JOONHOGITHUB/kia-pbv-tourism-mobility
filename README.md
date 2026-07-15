# 기아 PBV 기반 관광 모빌리티 서비스 (Tourism_Mobility)

> PBV의 공간 활용성과 디지털 콘텐츠를 결합해 이동 시간을 관광 경험으로 확장한 서비스 기획 프로젝트입니다.

## 프로젝트 개요

- **진행 기간:** 2024.12 – 2025.02
- **형태:** 2~3인 팀 공모전 프로젝트
- **담당 역할:** PBV 공간 활용, 관광 서비스 흐름 및 문화 콘텐츠 제공 방식 기획
- **프로젝트 범위:** 서비스 기획, 사용자 시나리오, 차량 공간 및 디스플레이 UX 설계

> 본 저장소는 개인 포트폴리오 목적으로 프로젝트의 공개 가능한 내용만 정리했습니다.  
> 기아의 공식 제품이나 상용 서비스를 의미하지 않습니다.

## 문제 정의

기존 관광 이동 서비스는 목적지까지의 운송에 집중되어 있어, 이동 시간이 관광 경험과 단절되는 문제가 있습니다.

본 프로젝트는 PBV의 넓은 실내 공간과 디스플레이를 활용해 이동 중에도 관광지의 역사·문화 정보를 경험할 수 있는 이동형 관광 체험 공간을 제안했습니다.

## 핵심 제안

### 이동형 관광 체험 공간

- 4인 중심의 대화형 좌석 구조
- 관광지와 문화재 사전 콘텐츠 제공
- 이동 경험과 현장 관광 경험 연결

### 공동 경험과 개인 맞춤 기능

- 공유 디스플레이를 통한 문화·관광 콘텐츠 시청
- 개인 패드를 통한 언어 및 관광 코스 선택
- 좌석, 냉난방, 조명 등 차량 환경 제어

### 지역 관광 생태계 연계

- 전통시장, 음식점, 카페 및 숙박시설 추천
- 관광지 방문을 지역 상권과 생활문화 경험으로 확장
- 대형 짐을 위한 루프 리프트 및 실내 공간 최적화

## 사용자 경험 흐름

1. 관광객이 언어와 여행 코스를 선택합니다.
2. 차량 이동 중 목적지의 역사·문화 콘텐츠를 시청합니다.
3. 개인 패드로 좌석과 차량 환경을 조절합니다.
4. 목적지 주변의 음식점과 편의시설을 추천받습니다.
5. 사전 정보와 현장 관광 경험을 연결합니다.

## 주요 설계
### 저장소 구조

```text
kia-pbv-tourism-mobility/
├── README.md
└── assets/
    ├── vehicle-exterior.png
    ├── interior-layout.png
    ├── shared-display-retracted.png
    ├── shared-display-deployed.png
    ├── shared-display-active.png
    ├── personal-display-overview.png
    ├── personal-display-detail.png
    ├── rear-seats-folded.png
    ├── rear-seats-deployed.png
    ├── rotating-front-seats.png
    ├── roof-lift-closed.png
    └── roof-lift-open.png
```

### 차량 외관 및 내부 공간

<p align="center">
  <img src="assets/vehicle-exterior.png" width="48%" alt="차량 외관">
  <img src="assets/interior-layout.png" width="48%" alt="차량 내부 공간">
</p>

<p align="center">
  <sub>차량 외관과 4인 중심의 실내 공간 구성</sub>
</p>

---

### 공유 디스플레이 수납 및 전개

<p align="center">
  <img src="assets/shared-display-retracted.png" width="48%" alt="공유 디스플레이 수납 상태">
  <img src="assets/shared-display-deployed.png" width="48%" alt="공유 디스플레이 전개 상태">
</p>

<p align="center">
  <sub>공유 디스플레이 수납 상태(왼쪽)와 전개 상태(오른쪽)</sub>
</p>

---

### 공유 및 개인 디스플레이

<p align="center">
  <img src="assets/shared-display-active.png" width="48%" alt="공유 디스플레이 실행 화면">
  <img src="assets/personal-display-detail.png" width="48%" alt="개인 디스플레이 상세 화면">
</p>

<p align="center">
  <sub>공동 관광 콘텐츠와 개인 맞춤형 차량 제어 화면</sub>
</p>

---

### 개인 디스플레이 배치

<p align="center">
  <img src="assets/personal-display-overview.png" width="48%" alt="개인 디스플레이 전체 배치">
  <img src="assets/rotating-front-seats.png" width="48%" alt="회전형 앞좌석 구조">
</p>

<p align="center">
  <sub>좌석별 개인 디스플레이와 가변형 실내 좌석 구조</sub>
</p>

---

### 가변형 뒷좌석

<p align="center">
  <img src="assets/rear-seats-folded.png" width="48%" alt="뒷좌석 수납 상태">
  <img src="assets/rear-seats-deployed.png" width="48%" alt="뒷좌석 전개 상태">
</p>

<p align="center">
  <sub>뒷좌석 수납 상태(왼쪽)와 전개 상태(오른쪽)</sub>
</p>

---

### 루프 리프트

<p align="center">
  <img src="assets/roof-lift-closed.png" width="48%" alt="루프 리프트 수납 상태">
  <img src="assets/roof-lift-open.png" width="48%" alt="루프 리프트 적재 상태">
</p>

<p align="center">
  <sub>루프 리프트 수납 상태(왼쪽)와 짐 적재 상태(오른쪽)</sub>
</p>

## 개인 기여

- PBV의 가변형 공간을 활용한 관광 서비스 아이디어 구체화
- 관광객 중심의 서비스 이용 흐름과 사용자 시나리오 설계
- 공유 디스플레이와 개인 관광 가이드 패드 기능 기획
- 이동 중 문화 콘텐츠 제공 방식과 지역 관광 정보 연계 기획
- 팀 기획 회의 및 발표 자료 제작 참여

## 프로젝트를 통해 배운 점

- 차량 플랫폼의 기술적 특징을 사용자 경험과 연결하는 방법
- 이동 과정 전체를 기준으로 사용자 문제와 요구사항을 분석하는 방법
- 기술 구현 가능성, 사용자 편의성 및 서비스 확장성을 함께 고려하는 방법
- AI·SW 기술을 실제 서비스 가치로 연결하기 위한 기획의 중요성
