# Capstone-11H56M-이거먹자

<br>

## 💻 프로젝트
## 1.1 프로젝트 개요
현대인들의 식단 불균형 해소를 위해 사용자가 매일 먹은 음식들중 부족한 영양소를 분석하여, 이를 채워줄 수 있는 음식을 추천해주는 웹서비스

<br>

## 1.2 프로젝트 배경
바쁜 현대 사회에서 항상 빠질 수 없는 고민은 오늘 무엇을 먹을까 식사 메뉴를 결정하는 것이다. 우리는 일상 속에서 음식 메뉴 고르는 시간을 자주 허비하게 되는데, 이에 해당하는 시간 낭비를 줄이기 위해 개인 영양소를 고려한 음식 추천 사이트를 만들고자 본 프로젝트를 만들게 되었다. 
'이거먹자'는 기존 음식 추천 틀에서 벗어나 사용자가 입력한 매일 먹은 음식들을 토대로 3대 영양(단백질, 탄수화물, 지방)을 고루 챙겨먹도록 부족한 영양소를 보충해줄 수 있는 음식을 추천해주고자 한다.
<br>

## ⏰ 개발 기간
**2023년 3월 9일 ~ 2023년 6월 8일**

<br>

## 👨‍👨‍👧‍👧 역할 분담
- **박용태**(백엔드) : DB 엔티티 수정, 음식 추천 기능, 캘린더 식사 정보 기능(삽입,수정,응답), 사용자 정보 확인 기능, 더미데이터 제작 및 삽입, 프록시 및 빌드 설정
- **박종혁**(백엔드) : DB 스키마 및 엔티티 제작, 데이터세트 전처리, 회원 관리 기능(회원가입,로그인,로그아웃), 쿠폰 관리 기능, 게시판 작성/리스트 기능<br>


- **이다예**(프론트) : 메인페이지, 음식 추천 페이지, 로그인/회원가입페이지, 쿠폰 페이지, 게시판 작성/리스트 페이지, (로그인,회원가입,음식추천,게시판)페이지별 axios 활용 서버와 통신
- **이동주**(프론트) : 회원가입 페이지 css, 음식별 식당 페이지/카카오맵 api 연동, 캘린더 페이지와 캘린더 axios 활용 서버 통신, 메뉴 입력 모달창 기능
<br>

## ⚙ 개발환경
- `Java Script`, `python`
- 사용 도구: React, MySQL, RestAPI
- 개발 환경: Window
- 개발 도구: VScode

<br>


## 📌 주요 기능
### **메인페이지**<br>
화면 우측 점들로 각 페이지별 소개를 보며 페이지를 이동<br>
로그인을 하면 로그인 버튼이 사용자가 로그인했던 id로 글자가 변경
 
<br>

![메인페이지](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/97cf0e1c-4074-44cc-b018-adbae0e620df)

<br>
<br>

### **로그인/회원가입페이지**<br>
회원 가입했던 아이디와 비밀번호로 로그인<br>

![로그인페이지](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/692a5e49-2606-49d4-a915-a782145c2864)

<br>

### **Ai 음식 추천 페이지**<br>

사용자가 캘린더에 입력했었던 음식들중 최근 먹었던 50가지를 뽑아, 사용자에게 부족한 영양소를 분석하여 이를 채워줄 수 있는 음식들이 랜덤으로 부족한 영양소와 함께 출력<br>

![음식추천](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/0a1fbcc0-8ed5-472c-82f6-1e9ecb8fd1d3)

<br>


<br>



### **쿠폰 페이지**<br>

우측 하단 floating 아이콘을 클릭하면 쿠폰 페이지가 떠서 쿠폰을 발급하고 발급한 쿠폰 저장<br>

![coupon_after](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/2f9922db-500a-4c49-8e5f-b3f674563567)

<br>

<br>


### **캘린더 페이지**<br>

로그인을 하고 사용자가 그 날 먹었던 세끼를 입력하고 저장하면, 나의 캘린더에 하루 내가 먹었던 칼로리가 계산되며 입력한 메뉴가 저장<br>


![calendar_input](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/094e7a17-d03a-4baa-85fd-1a9c1c341b0f)<br>

![calendar](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/2363af0f-7a7c-48c1-8ed4-4af885359baa)
<br>

<br>



### **게시판 페이지**<br>
게시판 리스트 페이지에서 글 작성을 누르면 모달이 떠서 글을 작성할 수 있고, 게시판 목록에서 글 제목과 작성한 사용자 아이디가 함께 작성했던 글이 출력<br>

![community_writing](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/9ef70ee3-fd6d-4e2e-a668-c7ed01589d01)<br>

![community](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/de64bdac-7c91-4b34-86f1-29010696b110)

<br>

<br>


### **카테고리 페이지**<br> 
각 카테고리 음식 눌러 식당 추천 페이지로 이동<br>

![category](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/4c37e4fd-dee2-4d88-a1cf-ecc516858040)
<br>

<br>


### **식당 추천 페이지**<br>

좌측에 식당 지도들과 우측에 각 음식별 식당들을 추천해주고 검색 기능으로 원하는 음식에 해당하는 식당 출력<br>

![search map](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/a28c25a7-4c6a-4bc6-ba2b-98fe8e75be07)
<br>

<br>

## 📝 프로젝트 알고리즘<br>

![알고리즘](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/96d32f3f-270f-42ce-b7b3-e55415537d2a)

<br>

<br>

## ✏ 구조도 <br>
![구조도](https://github.com/rainnn99/11H56M_Capstone/assets/102869025/225b3602-5ba2-4bc1-97f6-ec1acc37b6d9)

<br>


