# TwoRavel
여행 플래너 웹 사이트 프로젝트TwoRavel, Java 11, Eclipse IDE, JSP + Servlet, Oracle

추가적으로 /src/db.sql 파일 내 쿼리를 통해 DB DDL 및 DML 완료 후 실행

관리자, 비회원, 회원으로 이용자를 분리하여 각 기능을 구현

1. 여행을 계획하는 사람들의 여행 일정 작성
2. 여러 회원들의 여행 일정 공유 가능
3. 개인의 MBTI에 맞는 사람과 여행 매칭

개요
- 여행 계획을 세울 때, 효율적으로 스케줄을 관리할 수 있게 도와주며 여러 사람들과 일정을 공휴할 수 있으며 여행 메이트를 원하는 사람에게 원하는 MBTI에 맞는 사람들을 매칭해준다.

Language
- Java 11
- JavaScript
- SQL/PL
  
Development tool
- Oracle SQL Developer
- Eclipse
 
Skills
- JSP + Servelt
- jQuery
- Ajax
- OpenAPI
- JDBC

프로젝트 참여 인원
- 팀장: 임동균
- 팀원: 5명
 
개발 기간
- 2022.12.26 ~ 2023.01.10

ERD
![image](https://github.com/io030/TwoRavel/assets/114460492/247fbe83-e2fe-47b7-b947-09124f2980af)


|담당 기능|내용|
|:--|---|
|랜드마크 추천|메인 화면에서 랜덤으로 랜드마크를 추천합니다. 클릭 시 해당 랜드마크 세부 정보 페이지로 이동합니다.|
|랜드마크 게시판|지역별 유명한 장소의 이미지와 정보를 입력하여 게시합니다. 관리자가 추가 및 수정을 할 수 있으며 일반 회원들은 각 랜드마크에 한 줄 평가를 달아서 자신의 후기를 작성할 수 있으며 “좋아요” 기능을 통해 추천할 수 있습니다.|
|후기 추천|메인 화면에서 랜덤으로 일반 회원이 작성한 여행 후기들을 추천합니다. 클릭 시 해당 후기 세부 정보 페이지로 이동합니다.|
|후기 게시판|일반 회원들이 자신의 여행 후기를 작성하는 게시판입니다. 이미지와 내용을 입력할 수 있으며 작성자 외 일반 회원들은 댓글을 작성하여 소통할 수 있습니다.|
|숙박 추가 |여행 스케줄 작성 시 머무를 숙박 시설을 검색 혹은 추천을 통해 한 곳을 정한 후 추가하여 계획을 짤 수 있습니다.|
|스케쥴 작성 지역 선택|여행 스케줄 작성 전 어느 곳으로 여행을 떠날지 해당 지역을 선택합니다. 선택한 지역을 기준으로 맵을 로딩한 후 교통, 숙박 시설, 여행지 등 정보 또한 해당 지역을 기준으로만 보여줍니다.|


<details>
    <summary>구현기능 화면</summary>

![image](https://github.com/io030/TwoRavel/assets/114460492/725bdfe1-c595-45d9-b641-fe69d67991f3)

![image](https://github.com/io030/TwoRavel/assets/114460492/64a263fa-4a80-418a-ab5e-26f734d2d914)

![image](https://github.com/io030/TwoRavel/assets/114460492/eb39942d-f4d7-49ab-a797-0748a48bbedc)

![image](https://github.com/io030/TwoRavel/assets/114460492/4336d7f1-7d51-40f7-815a-e9e4a456dded)

![image](https://github.com/io030/TwoRavel/assets/114460492/2db9bd10-1ef7-4f6d-bb74-def7c2d20c5b)

![image](https://github.com/io030/TwoRavel/assets/114460492/c6039310-aa83-470e-94db-a709b91f437f)

</details>
