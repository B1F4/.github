 
## 🎀 개요
![image](https://github.com/user-attachments/assets/f6f64f40-94f3-4cf9-9f6b-88f21a5b6622)

### MVC 패턴을 활용한 배달 음식 주문 서비스 구현
- 신한투자증권 프로디지털 아카데미 미니미 프로젝트 B1F4팀


### 주요 기능
- **회원가입 및 로그인 기능:** 사용자는 서비스에 회원 가입하고, 로그인을 유지할 수 있습니다.
- **카테고리 기능:** 원하는 배달 음식의 카테고리를 선택할 수 있습니다.
- **식당 선택 기능:** 해당 카테고리에 등록된 식당을 보고, 선택할 수 있습니다.
- **메뉴 주문 기능:** 해당 식당의 메뉴를 선택하여 주문할 수 있습니다.
- **리뷰 작성 기능:** 주문이 완료된 후, 해당 주문에 대한 리뷰를 작성할 수 있습니다.

<br>

## 👨‍👩‍👧‍👦 Team : B1F4

|<img src="https://avatars.githubusercontent.com/u/122499274?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/164446778?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/127959482?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/101380919?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/83602306?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|:-:|
|[@hyuna333](https://github.com/hyuna333)|박찬란<br/>[@colde99](https://github.com/colde99)|lemonticsoul<br/>[@lemonticsoul](https://github.com/lemonticsoul)|JinHyeok<br/>[@YangJinHyeok](https://github.com/YangJinHyeok)|Mo Joon Woo<br/>[@ijustwannabeme](https://github.com/ijustwannabeme)|
|가게|리뷰|주문|유저|메뉴|

<br>

## 👑 프로젝트 목표
- MVC 패턴을 학습하기 위해, spring을 차용하지 않고 MVC 규칙을 지키는 서비스를 java로 구현한다.
- 배달의 민족 서비스를 가이드라인으로 배달 주문 서비스의 백엔드 틀을 구현한다.
- 설계부터 구현까지 모든 과정을 경험하며, 백엔드 프로젝트 전 과정의 기초를 수행한다.

<br>

## 🛠 설계 계획

![image](https://github.com/user-attachments/assets/155d4c4d-e839-490f-a14d-8b025dbce35b)
### 1. DDD 설계
- 4일의 개발 주기를 고려하여, **설계보다 구현**에 집중하여 빠르게 개발에 착수하였다.
- 통합적인 측면을 고려한 설계보다, **모듈 간 독립성**을 유지하자는 설계 목표에 따라 개발 시간을 단축할 수 있었다.
- 패키지 선정과 기능 선정은 백엔드 리더(서제호)의 설계 하에 진행하였다.

![image](https://github.com/user-attachments/assets/0b6f74b9-9274-4814-9646-9dc529fe240b)
### 2. 프로젝트 관리
- 개발 주기를 고려하여 에자일 방식으로 프로젝트를 관리하고, 이틀간 스크럼 회의를 진행하였다.

### 3. 회의록 작성
![image](https://github.com/user-attachments/assets/66d7eadb-e9d9-4724-891e-5567270d4b2c)

<br>

## 📄 ERD

![image](https://github.com/user-attachments/assets/bd958011-0724-43e3-b27f-7108138fcd9d)

<br>

## 🎨 플로우 차트

- **유저 플로우:** 로그인 -> 카테고리 선택 -> 레스토랑 선택 -> 메뉴 보기 -> 주문 -> 리뷰작성
- **로직:** View 요청 -> Controller에서 요청 및 데이터 받음 -> service 단에서 요청 로직 수행 -> Repository에서 db처리
- 수직적으로 진행되는 유저 플로우를 고려하여, 단계적 호출을 통한 1차적인 로직으로 설계를 진행하였다.

(+) model은 db안의 엔터티를 생성한다. 

<br>

![image](https://github.com/user-attachments/assets/ecdcae9a-de5f-4456-a2a3-5e7cebaabd69)

<br>

## 🎞️ 프로젝트 결과물
- 메인뷰 실행 결과

![GIFMaker_me (3)](https://github.com/user-attachments/assets/f6f698b2-b8e2-42cf-8399-874a19a66160)


- 리뷰 실행 결과 (미통합 기능)

![GIFMaker_me (2)](https://github.com/user-attachments/assets/26c1f284-515a-4026-bb2b-9c73428151b0)

<br>

## 🪄 Tool
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"> ![Github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white) ![Notion](https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![Slack](https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
