# 😀이건표 2차 프로젝트

### 🎥 그룹웨어 기본 연동 기능 및 메시지 봇 구현 PROJECT

## 🎞 **● 프로젝트 명** : codingStory 🎞

#### **● 프로젝트 설명** : 영화사 그룹웨어 서비스


<img src="src/main/resources/static/images/메인.jpg" alt="DB설계"/>


## 개요 ✨
이 프로젝트는 영화관을 지점별로 관리할 수 있는 그룹웨어 서비스를 개발하는 것을 목표로 합니다. 주요 기능으로는 그룹웨어의 기본 연동 기능과 메시지 봇의 구현이 포함됩니다. 이 서비스는 영화관 관리자들이 지점 내에서 효율적으로 협력하고 소통할 수 있도록 설계되었습니다.

## 목차 📚
- [프로젝트 배경](#프로젝트-배경)
- [팀원구성 및 역할](#팀원구성-및-역할)
- [기술 스택](#기술-스택-🛠)
- [주요 기능](#주요-기능)
- [기능시연 영상](#기능시연-영상)
- [향후 개선 사항](#향후-개선-사항)

## 프로젝트 배경 📜
현재의 영화관 운영 환경에서는 지점별로 데이터와 업무 프로세스를 통합적으로 관리하는 것이 중요한 요소입니다. 그래서 저희 그룹웨어 서비스는 다양한 기능을 한 곳에서 통합하여 제공함으로써 지점 관리자들이 실시간으로 업무를 처리하고 의사 결정을 내릴 수 있도록 돕습니다. 예를 들어, 지점 간 일정 조율, 인력 출퇴근관리, 공지사항 등의 기능을 통해 운영 효율성을 극대화할 수 있습니다.

또한, 메시지 봇을 통해 자동화된 안내 서비스를 제공함으로써 직원들의 업무 부담을 줄이고 고객 서비스 품질을 개선할 수 있습니다. 이 프로젝트는 기술적으로도 도전적인 면이 있으며, 그룹웨어 플랫폼과 인공지능 기술의 융합을 통해 혁신적인 솔루션을 제공하고자 합니다.

이 프로젝트는 영화관 업계의 디지털 전환을 촉진하며, 지점 운영의 효율성과 경쟁력을 강화하는 데 기여할 것으로 예상됩니다.

## 팀원구성 및 역할
- **(팀장) 이건표**: 게시판 CRUD
  카카오API
  영화API
  DB설계
  layout(index)css

- **(팀원) 박ㅇㅇ**: 회원 CRUD
  OAuth2
  Security
  CI/CD
- **(팀원) 심ㅇㅇ**:   결재관리
  ChatBot
- **(팀원) 왕ㅇㅇ**: 출퇴근관리
  네이버API
  급여관리
- **(팀원) 조ㅇㅇ**: 부서관리
  FullCalendar

## 기술 스택 🛠

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">

<img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">

<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white">
<img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">

<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"/>


- **프로젝트명**: codingStory
- **프로그래밍 언어**:<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
- **프레임워크**: Springboot 2.7.11
- **라이브러리**: Spring WEB(MVC), Thymeleaf, Spring Data JPA, Lombok, SpringSecurity5, websocket, validation, OAuth2, security, openAPI, KOMORAN, websocket
- **데이터베이스**: <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
- **ORM**: Spring Data JPA (JAVA(SQL))
- **개발툴**: IntelliJ
- **템플릿 엔진**: Thymeleaf (HTML + Data)
- **빌드**: <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white">
- **설정**: application.yml, application-oauth2.yml


## 주요 기능
### 게시판(CRUD)
| NO | 기능         | 설명                                                                 |
|----|--------------|----------------------------------------------------------------------|
| 1  | 게시판작성   | 분류를 본사, 노원점, 자동차관, 야외관, 커플관  카테고리로 분류<br> 작성자명은 회원닉네임으로 자동표기<br>파일선택으로 게시글 사진추가 |
| 2  | 게시판조회   | 게시글 상세 조회 가능<br>게시글 조회수 추가<br>게시글 댓글 기능 추가 작성 및 삭제 구현<br> |
| 3  | 게시판수정   | 제목, 내용, 카테고리, 금액, 인원, 사진 수정 가능  |
| 4  | 게시판삭제   | 본인이 작성한 게시글만 삭제 가능  |

### API
| NO | 기능           | 설명                                                   |
|----|----------------|--------------------------------------------------------|
| 1  | 카카오API  | 각 지점별 지도와 마커를 통해 위치표시 <br> 각 지점별 지하철 버스 안내 <br> 각 지점별 위치 주소 한글 영문 표기        |
| 2  | 영화API  | 메인페이지에 일별 박스오피스 리스트 표기    |

### DB
<img src="src/main/resources/static/images/erd.jpg" alt="DB설계"/>

## 기능시연 영상

### 상점게시판 작성시연 영상
![1차create](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/3b2b3ba8-6853-402f-80b9-0acfa910ce60)

### 댓글작성 및 삭제
![1차댓글1](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/a368d7f1-5af9-476d-856f-a0182b233dce)

### 게시판 수정 삭제
![1차수정삭제](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/74b4892e-5b59-467d-8381-1b8d7d1326cc)

### 페이징 서치
![페이징서치](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/149e728e-f104-48cd-a9c5-238cad235db4)


### 좋아요 기능
![like](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/de5ef513-b8a0-427a-8569-06ce99fc6957)

### 장바구니
![장바구니](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/0fea4947-7feb-47cd-bffe-60bbb05d3bc9)

### 메인페이지 Top Like 순
![좋아요](https://github.com/leegeonpyo/Project_teamE1I4/assets/154856555/b65d4afd-632a-456f-8a24-b758c970f77d)

## 향후 개선 사항
프로젝트 처음 시작할 때는 시간이 많은 줄 알았습니다. 첫 프로젝트이기도 하고, 우리 팀원들이 욕심이 많아서 하고 싶은 것들이 많다 보니 생각보다 구현하지 못한 것이 많고, 더 예쁘게 할 수 있었는데 시간에 쫓겨서 포기한 것이 많아서 아쉽습니다. 사용자들에게 더 편리한 쇼핑몰 게시판으로 구현하고 싶습니다.



**[⬆ 위로 가기](#이건표-2차-프로젝트)**