# 원티드 프리온보딩 정보보안 2024년 6월 사전과제
### 아래 질문에 대해 최대한 아는 선에서 답변해 보세요.
### 답변은 GitHub Issue로 올려주시면, 5월 말에 강의 전 표준 답변을 업로드해 드리겠습니다.
#### (아래 질문 중 선별하여 강의시간에 추가 설명할 예정입니다.)

#### 1 시스템 보안의 기본 원리는 무엇인가요? 
-> C I A
보안성 confidentiality
무결성 Integrity
가용성 Availability 
#### 2 시스템 취약점을 어떻게 식별하나요?
취약점은 보안 감사, 취약점 스캔 등을 통해 식별가능
#### 3 리눅스 시스템에서 덤프 파일을 생성하는 방법에는 무엇이 있는지 설명하세요.
코어덤프 크기 변경 설정

해당 주석 밑에 내용 추가 

시스템 재시작
#### 4 서버 취약점 점검을 한다고 했을 때, 가장 먼저 무엇을 어떻게 할 건가요?
데이터 백업을 하고 현재 가동중인 서비스, 열려있는 포트를 파악하며 
다운될 시의 조치방법을 준비해둠

#### 5 DB 트랜잭션이 무엇인지 설명하세요.
db 의 상태를 변환시키는 하나의 논리적 기능을 수행하기 위한 작업의 단위 또는 한꺼번에 수행되어야 할 일련의 연산들

#### 6 랜섬웨어에 감염됐을 때 대처법은 무엇인가요?
네트워크 연결 해제->
감염된 시스템, 미감염 시스템 점검->
감염된 시스템 완전 격리 후 복구 시도
#### 7 ARP 스푸핑에 대해 설명해주세요.

arp 정보
arp 를 속이는 기법으로 주로 스니핑에 사용되는 기법

#### 8 피싱, 스미싱, 파밍 세 개의 특징과 차이점은 무엇인가요?
피싱
스미싱 
파밍
#### 9 APT 공격이 무엇인지 간략하게 설명해주세요.
지능형 지속 공격으로 특정 대상을 다양하고 지능적으로 공격하는 방식
#### 10 SQL 인젝션 공격이란 무엇이며, 이를 방지하기 위한 스크립트 언어의 역할은 무엇인가요?
말그대로 악의적인 SQL 구문을 심는 공격이며 
이를 방지하기 위해 스크립트 언어로 입력 데이터의 검증 및 sanitizing 처리를 함
#### 11 MySQL에서 max_connections 설정 방법을 설명하세요.

#### 12 HTTP Method와 각각이 사용되는 경우에 대해서 설명해주세요.
GET
POST
PUT
#### 13 대칭키, 비대칭키 암호화 방식에 대해 설명해주세요.
대칭키
비대칭키 예시 RSA
#### 14 클라우드 보안과 전통적인 IT 보안의 주요 차이점은 무엇인가요?

#### 15 클라우드 보안 사고 대응 계획에는 어떤 요소가 포함되어야 하나요?
