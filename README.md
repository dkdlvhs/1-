# 1. IntelliJ Community 버전 설치


문제없이 잘 다운받았습니다.


# 2. Debeaver 설치 및 DB Connection


<img width="916" alt="image" src="https://github.com/dkdlvhs/1-/assets/155410316/d0dce03b-ef97-4f35-b8c8-6b44b362aba5">


    <property name="url" value="jdbc:mariadb://comento-db.cxw60aio6p3o.ap-northeast-2.rds.amazonaws.com:43306/statistic"></property>
    <property name="username" value="admin"/>
    <property name="password" value="devfunpj12345"/>


Debeaver를 설치하고 DB 커넥션 정보를 입력하는 과정에서 서버 url과 Authentication에서 username과 password에 대한 정보가 노션 설명으로는 부족했다.
다행히 카톡으로 다른 분이 질문하신 내용으로 데이터소스 코드에서 정보를 알 수 있었고 DB connection을 할 수 있었다.


<img width="1082" alt="image" src="https://github.com/dkdlvhs/1-/assets/155410316/fc96e915-7103-4c8f-8ace-4b271a8c4804">


# 3 Spring MVC 환경설정 & API PING 


Intellij Community에서 파일을 생성하고 코드를 옮겨 적는 과정에서는 큰 어려움이 없었다. Jetty를 실행하여 정상적으로 PingController의 결과를 확인할 수 있었다.


<img width="335" alt="image" src="https://github.com/dkdlvhs/1-/assets/155410316/c5bb947a-6137-4635-a1ea-f46462e0f351">


# 4 datasource & mybatis 연동


<img width="394" alt="image" src="https://github.com/dkdlvhs/1-/assets/155410316/2c6b2321-5e8d-4d8f-b492-292742fb4439">


역시 최종 파일 구조를 동일하게 만들고 코드를 옮겨 적었다. Jetty를 실행하여 정상적으로 HomeController의 결과를 확인할 수 있었다.


<img width="1344" alt="image" src="https://github.com/dkdlvhs/1-/assets/155410316/e1ba5e83-0938-4980-a433-ddb9ad99767b">


