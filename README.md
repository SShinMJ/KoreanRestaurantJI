<div align="center">
  <h1> :stew: KoreanRestaurantJI </h1>
  <h3>
    <a href="https://sshinmj.notion.site/Korean-Restaurant-25c7550a36bb4af4abd4658fff66cef6">
      📖 Wiki
    </a>
    <br><br>
    <a href="https://github.com/Team-KyunYoung/KoreanRestaurantJI_Front">
      :desktop_computer: Frontend
    </a>
    <span> | </span>
    <a href="https://github.com/Team-KyunYoung/KoreanRestaurantJI_Back">
      :gear: Backend
    </a>
  </h3>
  <br>
  <h4>
    배포 주소 : https://www.koreanrestaurantji.ml<br>
  </h4>
  <p>
    공유 계정을 통해 체험 가능합니다.<br>
    아이디 : testuser@test.com<br>
    비밀번호 : testuser1!
  </p>
</div>

<br>

## :point_right: Info
'智'는 제작자들의 이름에서 따온 임의의 레스토랑으로, 본 웹사이트는 실제로 레스토랑에서 제공하면 좋을 서비스들을 가정해보고 구현해보았습니다.
- **팀원 :** 본인 외 1인
- **개발기간** : 2022.06.29 ~ 2022.11.12
- **기획의도** : 인터렉티브한 가상의 k-food 음식점 웹사이트를 제작
- **개발목표** : 정확하고 가독성 높은 코드 작성과 실제 서비스를 제공하는 웹사이트의 배포


<br>

## :pushpin: Feature
**BackEnd**
- 사용자 관리 - 회원가입(이메일 인증), 로그인
- 사용자 정보 변경 기능, 관리자/일반 사용자 구분
- 관리자 전용(백오피스) 기능 - 사용자 / 음식 메뉴 / 코스 메뉴 / 예약 현황 / 주문 관리
- JWT 토큰을 이용한 인증 방식 (Spring Security)
- 식당 예약 시스템 - 같은 객실&날짜&시간에 최대 15팀만 예약 가능하게 관리
- 음식 포장 주문 시스템(주문, 장바구니 기능)
- 식당 예약, 주문 수정/삭제 기능
- Q&A, FAQ, 이벤트 게시판 (+Q&A 댓글)
- 구글 드라이브를 활용하여 이미지 저장/불러오기  

**FrontEnd**
- User Interactive & User Familiar
- Responsive Web Design
- Provide Realistic Service
    - Merbership Service: Sign Up, Cancellation, Edit Profile
    - Admin : Manage all services
    - Chat Bot :
    - Reservation Service : Make, Cancel or Change a reservation
    - To-go Service : Place or Cancel an order
    - Review :
    - Qna & Faq : Can view left by others or ask questions (Anonymity is possible)
    - etc
- Try to apply various third party library
    - react-bootstrap
    - react-naver-maps
    - react-simple-chatbot
    - etc

<br>

## :hammer_and_wrench: Tech Stack
<div>
<img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=JAVA&logoColor=white" />
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=Spring Security&logoColor=white" /> 
<img src="https://img.shields.io/badge/JPA-071D49?style=flat-square&logo=JPA&logoColor=white" />
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=Gradle&logoColor=white" />
<img src="https://img.shields.io/badge/Lombok-02303A?style=flat-square&logo=Lombok&logoColor=white" /> 
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=Swagger&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white" />
<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=Apachetomcat&logoColor=white" />
</div>

<br>

## :gear: Development Environment
![image](https://user-images.githubusercontent.com/82142527/207842053-e9429a02-e968-45a1-9c04-102a08ba9d57.png)

<br>

## :earth_asia: Deployment
<div>
<img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat-square&logo=GitHub Actions&logoColor=white" />
<img src="https://img.shields.io/badge/AWS EC2-FF9900?style=flat-square&logo=Amazon EC2&logoColor=white" />
<img src="https://img.shields.io/badge/AWS CodeDeploy-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white" />
<img src="https://img.shields.io/badge/AWS Route53-2490D7?style=flat-square&logo=Amazon AWS&logoColor=white" />
<img src="https://img.shields.io/badge/AWS S3-569A31?style=flat-square&logo=Amazon S3&logoColor=white" />
<img src="https://img.shields.io/badge/AWS Certificate Manager-981E32?style=flat-square&logo=Amazon AWS&logoColor=white" />
<img src="https://img.shields.io/badge/AWS RDS-527FFF?style=flat-square&logo=Amazon RDS&logoColor=white" />
</div>

![image](https://user-images.githubusercontent.com/82142527/202174285-dcc1a2d9-4272-4fc2-ab04-c1409a6dc9dd.png)

<br>

## :open_file_folder: DB ERD
![image](https://user-images.githubusercontent.com/82142527/196112910-4a4c3868-0203-41e5-bfea-4df1d101c05a.png)

<br>

##  :trident: API
![image](https://user-images.githubusercontent.com/82142527/201630140-c8f65949-a85a-4c9b-8c0a-5cc3485e20ac.png)

<br>

##  :desktop_computer: UI/UX
- **Main Page**  
![메인](https://user-images.githubusercontent.com/87280835/201481178-ac4cab3b-da9e-4285-a866-58c1651650c2.gif)  
    
- **Merbership**
    
    **회원가입과 로그인**  
    ![회원가입,로그인](https://user-images.githubusercontent.com/87280835/201484910-a1404eb3-f79f-42fc-b406-3c307e07eaea.gif)  
    
    **닉네임 수정**  
    ![닉네임수정](https://user-images.githubusercontent.com/87280835/201481976-02af919b-bfd9-4f88-bbf3-fec9fb6d6434.gif)  
    
    **비밀번호 변경**  
    ![비밀번호 번경](https://user-images.githubusercontent.com/87280835/201484586-3cc453af-79d3-4164-8953-d2d05922f205.gif)  
    
- **Admin Page**  
![관리자](https://user-images.githubusercontent.com/87280835/201481067-e38ccfb4-66e4-4448-8780-99999bcd4022.gif)
    
- **Chat Bot**  
![챗](https://user-images.githubusercontent.com/87280835/201483857-ebe3ac0d-51c7-405b-a901-e0e3f05d59a4.gif)
    
- **Reservation**
    
    **예약하기**  
    ![예약](https://user-images.githubusercontent.com/87280835/201480522-7d17820b-4648-43fd-9f30-17de4017f242.gif)
    
    **예약변경**  
    ![예약 변경](https://user-images.githubusercontent.com/87280835/201481973-9eae47f1-b8b6-412f-9a3d-81d7ad528b39.gif)
    
- **Order & Cart**  
    ![포장주문 (2)](https://user-images.githubusercontent.com/87280835/201480636-75881f2c-0e70-4698-9bd0-dedc653f2be9.gif)
    
- **QNA & FAQ**
    
    **QNA**  
    ![image](https://user-images.githubusercontent.com/87280835/201484710-ec12a0ad-a54b-4255-bc6a-96c2bbd26b6a.png)
    
    **FAQ**  
    ![image](https://user-images.githubusercontent.com/87280835/201484725-773b7c74-1883-4206-9521-e30d7e1d34ee.png)
    
- **Review**  
    ![image](https://user-images.githubusercontent.com/87280835/201481495-482ec305-8fe2-44fc-aca3-d07cc90f2ec5.png)
    
- **Responsive : tablet & mobile**  
![제목 없음](https://user-images.githubusercontent.com/87280835/198238798-f3994d85-4e55-4c76-9dc1-efdece405a52.png)
