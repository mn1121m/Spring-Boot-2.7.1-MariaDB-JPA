# Spring-Boot-2.7.1-MariaDB-JPA

### Text book
- Title: 코드로 배우는 스프링 부트 웹프로젝트
- Authors: 구멍가게 코딩단

    <img width="200" alt="spring-web-project-img" src="http://image.kyobobook.co.kr/images/book/large/070/l9791189184070.jpg">



## Goal
- Spring Boot 에서 필요한 MariaDB 설정 및 Spring Data JPA 기술 학습

  - MariaDB의 설치와 스키마/계정 생성
  - 스프링 부트 프로젝트의 데이터베이스 설정
  - Spring Data JPA를 이용한 CRUD와 페이징 처리 기법 배우기
  - JpaRepository 인터페이스를 활용하는 다양한 방법 익히기



## Spec
- Java 11
- Spring Boot (v2.7.1)
- Spring Data JPA
- IntelliJ IDEA CE
- MariaDB (v2.7.0)



## Spring Initializr - Selected Dependencies
- Spring Boot DevTools
- Lombok
- Spring Web
- Spring Data JPA



## DB를 위한 Spring Boot Setting
- Spring Data JPA 라이브러리 설정

  - MariaDB용 JDBC -> "maven mariadb -> MariaDB Java Client >> 2.7.0
  
    <img width="500" alt="mariadb-gradle-setting" src="https://user-images.githubusercontent.com/83820185/178628159-5904d7f0-7534-44f5-b9c3-297dbe26c504.png">

  - Spring Boot Project 내 MariaDB 설정 -> application.properties 파일 내의 다음의 내용을 추가
  
    <img width="500" alt="application-properties-setting" src="https://user-images.githubusercontent.com/83820185/178627942-39923070-f1de-4020-b1d5-de2e7e3104a8.png">

