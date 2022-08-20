# 김준섭

## 기본 정보

-   email : ggi4111@naver.com
-   github: https://github.com/JsKim4

## 학력

-   명지전문대학교 2015/03 ~ 2020/02 컴퓨터 전자과 졸업

## 경력 사항

-   그린스토어 2020/01 ~ 2021/02 IT본부 백엔드 개발자 근무
-   하이퍼커넥트 2021/04 ~ 2021/08 HyperX Backend Engineer
-   라포랩스\ 
        2021/09 ~ Retention Squad Backend Engineer\
        2022/05 ~ Customer Tribe Backend Lead

## 자격 사항

-   정보처리 산업기사


## 기술 스택

-   백엔드
    -   Spring(java) : 상용 어플리케이션 출시및 서비스
        -   Spring Boot 활용
        -   Spring Data Jpa를 활용한 ORM 방식의 프로그램 개발
        -   Querydsl 을 이용한 동적쿼리 
        -   Spring REST Docs를 활용한 문서화
        -   Spring Security를 이용한 JWT토큰 인증 방식 API
        -   Junit5 / Junit4 를 이용한 단위/통합 테스트
        -   Flyway를 이용한 DB형상 관리
    -   Mysql / Sql Server : 통계성 쿼리를 포함한 쿼리문 작성 가능
-   인프라
    -   Jekins : gitlab 혹은 github와 연동하여 자동 빌드 / 배포환경 구축경험 있음
    -   Docker : Docker를 활용한 테스트 환경 구축 경험 및 Docker-compose 사용 가능 
-   기타
    -   Git : git-flow로 소스 형상관리 
    -   Notion : Notion을 통합 협업 체계 구축 경험
    -   Algorithm : [백준](https://www.acmicpc.net/user/ggi411) 사이트에서 문제풀이 진행(627문제 해결)


# 진행 프로젝트


## 사내 프로젝트
---
### 하이퍼커넥트
---
HyperX 팀의 matrix studio 소속. Backend engineer.
AI&AR 챗봇 메신저 프로젝트 개발. 신규 서비스 런칭.

### 그린스토어
---
-   Green Store Family 매출 현황 어플리케이션
    -   기술 스택 : Spring Boot, Spring Security, Spring Data Jpa, Spring REST docs, JUnit5, Mssql
    -   기간 : 2020/08 ~ 2020/10
    -   참여인원 : ios(1), android(1), Back-End(1)
    -   설명
        -   자사 쇼핑몰 매출액과 반품액의 통계를  실시간으로 확인하기 위한 애플리케이션 개발
        -   해당 어플리케이션의 백엔드를 전담하여 개발하였음


-   [Green Store Family](https://play.google.com/store/apps/details?id=kr.co.greenfamily)
    -   기술 스택 : Spring Boot, Spring Security, Spring Data Jpa, Spring REST docs, JUnit4, Mssql
    -   기간 : 2020/03 ~ 2020/08
    -   참여인원 : ios(1), android(1), Back-End(2), Front-End(1)
    -   설명
        -   하이브리드 어플리케이션으로 개발
        -   자사 회원들을 대상으로한 쇼핑몰
        -   쇼핑을 위한 필수 기능뿐만 아니라, 걸음수 측정및 포인트 지급 기능, 현재 지역 미세먼지 조회 기능, 건강기능 식품 섭취 현황 기록 기능, 자가건강진단 기능이 포함됨
        -   어드민 페이지에서 동작하는 기능을 제외한 클라이언트에서 사용하는 API를 전담하여 개발하였음
        -   관련 프로젝트
            -   월별 걸음수를 체크하여 순위권 유저에게 쿠폰을 지급하는 기능을 위해 프로그램을 개발하여 Jenkins를 이용하여 스케줄링함
            -   월별 구매 누적 합계를 체크하여 회원의 등급을 올려주는 프로그램을 개발하여 Jenkins를 이용하여 스케줄링함

## 개인 프로젝트
---
### 개인 프로젝트

---
-   [URL SHORTNER](https://github.com/JsKim4/URL_Shortening_Service)
    -   기술 스택 : Spring Boot, Spring Data JPA, Redis, RabbitMQ, Docker
    -   기간 :  2021/03 ~ 2021/03
    -   개인 프로젝트
    -   설명
        -   긴 URL 을 짧게 Shorterning 해주는 서비스를 제공
        -   짧아진 URL 별로 몇번의 요청이 있었는지 저장
            -   요청시 RabbitMQ에 요청에 대한 데이터 저장 후 rdbms를 update 하는 방식을 채택함
        -   짧아진 URL을 요청시 원래의 URL로 Redirecte
            -   짧아진 URL 과 원래의 URL은 Redis를 통하여 관리함
        

-   [Shopping Mall](https://github.com/JsKim4/shopping_mall)
    -   기술 스택 : Spring Boot, Spring Security, Spring Data Jpa, Spring REST docs, JUnit5, flyway, Mssql
    -   기간 : 2020/11 ~ 2021/01
    -   개인 프로젝트
    -   설명
        -   사내에서 습득한 쇼핑몰 도메인 지식을 기반으로 하여 쇼핑몰에서 사용하는 API를 구현함
        -   클라이언트 프로그램은 존재하지 않고 REST API만으로 이루어진 프로젝트
        -   실제 클라이언트 개발자와 협업한다는 생각으로 개발진행
        -   RestDocs 롤 통한 문서화 진행
        -   JUnit5 를 통한 단위테스트 및 통합 테스트 진행
        -   상속을 통한 Exception전략 수립 및 개발
        -   Point 관련 정책 설립 및 개발

-   [Baekjoon Online Judge 문제풀이](https://www.acmicpc.net/user/ggi411) 
    -   기술스택 : Java, C++
    -   기간 : 2017/11 ~ 2020/09
    -   개인 프로젝트
    -   설명
        -   자료구조/알고리즘에 대한 지식및 문제해결능력을 키우기 위해 BOJ 사이트에서 알고리즘 문제풀이를 진행
        -   19년 말부터 해결한 문제를 [저장소](https://github.com/JsKim4/BOJ-BaekJoon-Online-judge-)에 업로드함
        -   BOJ에서 총 600개 이상의 문제를 해결하였고, 랭킹 1000위 이상을 달성할 수 있었음
    
### 스터디 프로젝트
---
-   [사내 알고리즘 스터디 운영](https://github.com/JsKim4/Grst-Algorithm)
    -   기술스택 : Java
    -   기간 :  2020/07 ~ 2020/10
    -   스터디 참여인원 : 3명
    -   설명
        -   그린스토어 사내에서 알고리즘 스터디를 운영함
        -   매주 정해진 문제를 풀어와서 각자의 풀이방식을 공유하는 방식으로 운영
