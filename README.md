# Dku-educational-platform
플랫폼 구성 요소

### 📊 시스템 유스케이스 다이어그램 (기능 클릭 가능)

```mermaid
graph TD
    subgraph 고등학교 교육 플랫폼
        %% 1. 임수민 그룹
        StudentC[임수민 하위권] --> C_UC1(FR-01: 학사 일정 및 시간표 동기화)
        StudentC --> C_UC2(FR-02: 문제 이미지 인식 및 해설 제공)
        StudentC --> C_UC3(FR-03: 맞춤형 학습 로드맵 추천)
        StudentC --> C_UC4(FR-04: 취약 단원 시각적 리포트 조회)
        StudentC --> C_UC5(FR-05: 고난도 변형 문제 큐레이션)

        %% 2. 이정훈 그룹
        StudentB[이정훈 중위권] --> B_UC1(FR-01: 학사 일정 및 시간표 동기화)
        StudentB --> B_UC2(FR-02: 문제 이미지 인식 및 해설 제공)
        StudentB --> B_UC3(FR-03: 맞춤형 학습 로드맵 추천)
        StudentB --> B_UC4(FR-04: 취약 단원 시각적 리포트 조회)
        StudentB --> B_UC5(FR-05: 고난도 변형 문제 큐레이션)

        %% 3. 안치용 그룹
        StudentA[안치용 상위권] --> A_UC1(FR-01: 학사 일정 및 시간표 동기화)
        StudentA --> A_UC2(FR-02: 문제 이미지 인식 및 해설 제공)
        StudentA --> A_UC3(FR-03: 맞춤형 학습 로드맵 추천)
        StudentA --> A_UC4(FR-04: 취약 단원 시각적 리포트 조회)
        StudentA --> A_UC5(FR-05: 고난도 변형 문제 큐레이션)
    end

    %% 클릭 시 아래 상세 정보 링크로 이동하는 설정
    click C_UC1 "#-fr-01-학사-일정-및-시간표-동기화"
    click C_UC2 "#-fr-02-문제-이미지-인식-및-해설-제공"
    click C_UC3 "#-fr-03-맞춤형-학습-로드맵-추천"
    click C_UC4 "#-fr-04-취약-단원-시각적-리포트-조회"
    click C_UC5 "#-fr-05-고난도-변형-문제-큐레이션"

    click B_UC1 "#-fr-01-학사-일정-및-시간표-동기화"
    click B_UC2 "#-fr-02-문제-이미지-인식-및-해설-제공"
    click B_UC3 "#-fr-03-맞춤형-학습-로드맵-추천"
    click B_UC4 "#-fr-04-취약-단원-시각적-리포트-조회"
    click B_UC5 "#-fr-05-고난도-변형-문제-큐레이션"

    click A_UC1 "#-fr-01-학사-일정-및-시간표-동기화"
    click A_UC2 "#-fr-02-문제-이미지-인식-및-해설-제공"
    click A_UC3 "#-fr-03-맞춤형-학습-로드맵-추천"
    click A_UC4 "#-fr-04-취약-단원-시각적-리포트-조회"
    click A_UC5 "#-fr-05-고난도-변형-문제-큐레이션"
