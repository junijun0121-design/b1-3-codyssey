# AI 도구 학습 #
## 노코드 자동화 기초: 워크플로우 설계 ##

<br></br>

## [프로젝트 1] 자동화 도구 비교 구현 ##
### 0. 설문조사 ###
- OO고등학교 정보 교과 질문 접수 시스템

<br></br>

### 1. 공통 요구 사항 ###
- **Trigger**: Google Forms (Watch Responses) 배치 → 구글 계정 및 폼 연결
- **Router**: Trigger 다음에 Router 설치 → Action 2개 생성
- **Filter**
  - **Action 1**: 'Basic Operators: Exists' 조건 → 설문 응답이 오면 Action 1 실행
  - **Action 2**: 'Basic Operators: Exists' 조건 → 설문 응답이 오면 Action 2 실행
- **Action**
  - **Google Sheets** (Action 1): 설문 응답이 오면 Add a Row로 항목별 응답 추가
  - **Discord** (Action 2): 설문 응답이 오면 Webhook Bot으로 "New response 발생!" 문구 전송


<br></br>

### 2. Make 구현 ###

<br></br>

## [프로젝트 2] 자유 주제 자동화 설계 및 구현 ##
