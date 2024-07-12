# 캠핑 관련 정보 공유 사이트 README
 배포 URL : 현재 미배포상태.

## 프로젝트 개요
+ 주제 : 전국 캠핑장에 대한 위치 및 상세정보 등을 제공하는 사이트, 자체적으로 공부한 Spring 기술을 사용하여 게시판 CRUD 기능을 추가하여 기술향상을 목적으로 함.
+ 기간 : 2024년 5월 20일(월) ~ 2024년 6월 25일(화)

## 팀원 구성 

| **팀장** | **팀원** |
| :------: |  :------: |
| **김대근** | **장준희** |

## 개발 환경

- Front : HTML, JavaScript, jquery, react
- Back-end : 공공데이터 활용, SpringBoot
- 데이터 관리 : mysql
- 협업 툴 : Discord, Github
- 배포환경 : AWS

## 페이지 소개

### [메인페이지]
- 접속시 메인페이지의 초기화면이며, 메인화면에 캠핑팁, 캠핑레시피, 캠핑샵과 개인 깃허브를 배치하였음.
![image](https://github.com/user-attachments/assets/931fb31e-8b4b-45c0-bb10-77197262bf0b)
![image](https://github.com/user-attachments/assets/05fdd7da-8209-406d-a0e8-af6e482c5838)

### [카테고리 및 검색페이지]
- 지역별 검색 및 유형별 검색 탭을 만들어 탭을 눌러 캠핑장 리스트를 찾을수있으며 페이징 처리가 되어있어 많은 정보를 제공.
- 지역별 및 유형별 검색후 캠핑장의 이름, 한줄소개, 주소, 주요시설 등으로 간단한 정보를 미리볼수있음.
- 검색기능을 추가하여 원하는 단어 및 캠핑장이름, 주요시설 등으로 검색이 가능함.

##### [지역별 검색(강원)을 이용한 결과]
![image](https://github.com/user-attachments/assets/61caa8a2-063f-4e70-9bf5-69439eaac63f)
##### [유형별 검색(일반야영장)을 이용한 결과]
![image](https://github.com/user-attachments/assets/15d594d7-5e96-44ef-95ed-6f2bfc36bb2d)
##### [검색기능(수영장)을 이용한 결과]
![image](https://github.com/user-attachments/assets/2b135a33-1bcd-4a58-b284-9cc490f0a16b)
##### [검색기능(제목없음)을 이용했을시 결과가없을때]
![image](https://github.com/user-attachments/assets/cbea2624-7d31-4160-9bbf-3c0aa4781ac8)

### [상세페이지]
- 캠핑장의 상세페이지를 나타내는 페이지이며, 캠핑장의 대표이미지, 이름, 주소, 상세정보 등의 다양한 정보를 제공함.
- 캠핑장의 유형별로 기타정보가 다르게 나오게 처리하여, 필요한 정보만을 제공함.
- 사진을 회전시켜 캠핑장의 위치가 나오게 지도API를 사용하였음.

##### [기본정보 및 상세정보]
![image](https://github.com/user-attachments/assets/e4d923e9-3b68-46e4-9133-1cc33f5a8fa5)
##### [지도제공 및 기타정보]
![image](https://github.com/user-attachments/assets/fe247169-004a-4835-a65e-0222c2a0069f)

### [캠핑 팁 및 캠핑레시피]
- 유튜브API를 사용하여 캠핑팁 및 캠핑레시피를 크롤링하여 제공함.
![image](https://github.com/user-attachments/assets/27267e23-7ce7-4632-9553-b16c314a5793)
![image](https://github.com/user-attachments/assets/ec6c8863-d2a4-4ff7-82cb-5c6e4553eec6)

### [게시판]
- 시간부족으로 인해 부트스트랩을 사용하여 외형에 조금 문제가 있으나, 기능적으로는 문제가없음.
![image](https://github.com/user-attachments/assets/42de1b1a-6ba9-46a4-9bdf-7981bceefe33)

#### [회원가입]
- 회원가입 시 이메일 중복확인으로 중복이메일을 사용할수없게 기능구현.
![image](https://github.com/user-attachments/assets/378e5056-d9c6-479f-91f6-c5cba3115d32)

#### [로그인]
- 로그인 기능 구현 및 로그인 시 네비바에 로그인한 유저의 이메일이 표시됨.
![image](https://github.com/user-attachments/assets/e233f1b7-f571-47db-bc37-6cb4843e8c3b)
![image](https://github.com/user-attachments/assets/407663ba-8c02-401b-b379-42e656944a82)

#### [글쓰기 및 댓글작성]
- CRUD 기능을 통해 글쓰기 및 댓글작성 가능.
![image](https://github.com/user-attachments/assets/72fac42c-33d5-4bc3-a243-3586e92c343c)
![image](https://github.com/user-attachments/assets/6621e4de-9246-440d-86f7-92f618f917cf)

## 추가(보완)해야하는 기능
- 고도화 챗봇기능
- 지역별 실시간 채팅 추가
- 부트스트랩 제거 및 게시판 CSS 수정
- 유튜브API 뿐만아닌 블로그 포스트 사용 추가
