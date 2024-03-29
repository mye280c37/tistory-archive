# [멘토특강] 기획력 향상 특강 (잘하는 기획, 잘쓴 기획서)

> 22.05.05
> 박수현 멘토님

## 프로젝트

- 일정한 기간 , 일정한 목적, 수행하는 업무 묶음
- 정해진 기간, 배정된 금액 등 제약된 조건 하에 일정한 요구사항을 수행하는 것

## PLC

프로젝트 라이프 사이클

PMBOK 5단계 프로세스 그룹

### 1. 프로젝트 착수
    
광범위한 프로젝트 범위 정의
    
### 2. 프로젝트 계획
    
프로젝트 관리의 핵심. 팀원이 따라야 할 로드맵 개발

- 범위 기획
- 작업 분류 (WBS)
- 마일스톤
- 간트 차트 (Gantt)

...
    
### 3. 프로젝트 실행

- 킥오프 미팅
- 자원할당, 관리계획 실행, 조달 관리, 추적시스템 설정, 작업 할당, 상태 회의, 프로젝트 일정 업데이트


### 4. 프로젝트 통제

- 진척 상황 모니터링
- 성과측정
- KPI(Key Performance Indicator)
- 성과보고
- 통합된 변경 통제

### 5. 프로젝트 종료

프로젝트 종료

## SDLC

Software Development Life Cycle

<ol>
<li> Planning </li>
<li> analysis </li>
</ol>

⇒ SDLC < PLC

## 프로젝트

- B2C
- Agile (↔ Waterfall)
    - Scrum Framework
        - Sprint Planning의 요구사항은 절대 건드리지 않는다
        - 새로운 요구사항이 추가되면 BackLog Planning에 넣기
- 기능 우선순위 필수로 정하기
- 목적 꼭 정하기
- 하나의 스프린트가 끝날 때마다 리뷰하기
    - 다 끝내지못해도, 더 해도 일정산정을 못한 것이므로 이또한 회고의 대상
- (품질에 대한) 기준을 못 맞춘 기능 배포하지 말 것
    - validation
    - verification
- 이해관계자(stakeholder)와 계속 소통하기

### 실패하는 프로젝트

- 요구사항 이 제대로 정의되었는가
- 요구사항에 대한 부실한 변경 관리

⇒ SRS(약식), WBS, Gantt

즉, 문서화는 필수

### 묻고 또 묻기

WHY

- 왜하는지
- 누구에게 도움이 되는지
- 꼭 필요한지

## SRS

프로젝트 기획에서 기능 명세는 필수

- 무엇을
- 어떻게
- 인터페이스 규약
- 기능/비기능 요구사항

## WBS

→ 업무를 쪼갬

(계층 tree 구조)

- Project
- Coding
- Phase
- Work Package

### 소마에서 WBS

- 3명이서 5-6개월
- 30~50개의 task로 구성

## Gantt

시간순으로 일정 수립

- MS project → 비용, 어려움
- Excel (X)
- Asana

→ 3명 뿐이고 모두 개발을 하기 때문에 현실적을 PM 역할을 한 명이 하는건 불가능

→ 깃랩 쓰기

### Gantt Process

1. task를 정하고
2. task간의 dependencies를 정함(병령 수행이 되는 게 있고, step-by-step도 있음)
3. Baselines ⇒ 비용 계산(ex. task가 밀릴 경우 비용의 변화)
4. task 할당

## 기획

- 없으면 안되는 것(pain point) vs. 있으면 좋은 것(wow point)
- 고객 문제
- 5 why → 더 큰 demands를 찾아야 한다(궁극적 니즈)

### 기획이란?

- 서비스 이해
    - 해당 분야, 서비스 이해
    - pain point 정의
- 시장조사
    - 고객 니즈 발굴
    - 유사 분야 조사
- 구매 포인트

### 사업계획서 작성하기

- Executive Summary
    <div class="inbox">
    간단하게 요약할 수 있도록, 한 번에 이해되게
    </div>
- Problem (Customer Needs)
    - 고객의 pain point
    - 현재 시험에서 고객이 해당 이슈를 어떻게 해결하는지
    - TAM, SAM, SOM
- Competition
    - 경쟁자 리스트
    - 우리의 강점
- Financial Projection
- Team

### User Story

- Persona
    - 가상의 타겟(고객)

### 실패하는 기획서

- why와 how가 없음
    - 아이템에 대한 소개와 기술 소개만 많은 기획서
- 기술적 전문용어 도배
    <div class="inbox">
    ⇒ 문제 해결에 초점을 맞추기
    </div>

⇒ 눈에 잘 띄고, 청중의 수준에 맞추어

### 좋은 기획서

- 왜
- 누구를 위해서
- 어떤 문제를
- 어떻게 해결
- 주요 기능
- 수익 모델
- 누구와 언제까지 무엇을 어떻게

### 기획서는?

- What to do+ How to do
- Why to do that + Schedule/Cost/Staff
- 아웃라인, 디테일, 시각화
- 들어올 약점 질문에 대비

⇒ 기획 = 고객 + 문제 + 해결

⇒ 마인드맵, 브레인스토밍(많은양)

## 자료조사

- 정량적 조사(설문조사) : 100~200개 정도
- 정성적 조사(포커스 그룹) : 잠재그룹에 대한 인터뷰
- 공식 간행물(통계자료)

## 분석

거시 환경 분석(통제가 불가능한 요인을 파악)(PEST) → 기업 내부 분석 (7S), 기업 외부 분석 (5Forces) → SWOT

## 마케팅

≠ 홍보

고객이 원하는 것을 찾아내고 이를 만족시키기 위한 전략 수립

### 마케팅 프로세스

- 환경분석 : 3C
- 마케팅 전략수립 : S-T-P
    <div class="inbox">
    ⇒ (Targeting) 비용,품질을 축(포지셔닝맵)으로 나는 어느 쪽에 갈지 정해야함
    </div>
    - 경쟁자를 알 수 있음
- 실행계획수립 : 4P&PLC
- 실행 및 평가

## Lean Canvas (← 비즈니스 모델 캔버스)

비즈니스 모델 캔버스를 IT 사업에 적용한 것

⇒ 다양한 아이템에 대해 작성해볼 것

⇒ 한 주제에 대해 여러 개일 수도 있음