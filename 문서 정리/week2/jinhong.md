<div align="center">
  작성자 / 작성일 혹은 수정일 - jinhong / 23th August 2022year
</div>

# 2주차. 개인 정리 내용

### 목차
1. [스프링 부트와 AWS로 혼자 구현하는 웹 서비스에서 나오는 "Spring Data"는 무엇인가?](https://github.com/hongcoding94/Web_Service_Study/blob/53a7d6cd7c9692cf31769ea97074f3946980ea79/%EB%AC%B8%EC%84%9C%20%EC%A0%95%EB%A6%AC/week2/jinhong.md#%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-aws%EB%A1%9C-%ED%98%BC%EC%9E%90-%EA%B5%AC%ED%98%84%ED%95%98%EB%8A%94-%EC%9B%B9-%EC%84%9C%EB%B9%84%EC%8A%A4%EC%97%90%EC%84%9C-%EB%82%98%EC%98%A4%EB%8A%94-spring-data%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80)
2. [JSP란 무엇이며 어떻게 구조화 되어 있는가?](https://github.com/hongcoding94/Web_Service_Study/blob/53a7d6cd7c9692cf31769ea97074f3946980ea79/%EB%AC%B8%EC%84%9C%20%EC%A0%95%EB%A6%AC/week2/jinhong.md#jsp%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B4%EB%A9%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%EA%B5%AC%EC%A1%B0%ED%99%94-%EB%90%98%EC%96%B4-%EC%9E%88%EB%8A%94%EA%B0%80)
3. [JPA란 무엇이며 어떻게 구조화 되어 있는가?](https://github.com/hongcoding94/Web_Service_Study/blob/53a7d6cd7c9692cf31769ea97074f3946980ea79/%EB%AC%B8%EC%84%9C%20%EC%A0%95%EB%A6%AC/week2/jinhong.md#jpa%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B4%EB%A9%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%EA%B5%AC%EC%A1%B0%ED%99%94-%EB%90%98%EC%96%B4-%EC%9E%88%EB%8A%94%EA%B0%80)
4. [JPA와 JSP의 구조 차이](https://github.com/hongcoding94/Web_Service_Study/blob/53a7d6cd7c9692cf31769ea97074f3946980ea79/%EB%AC%B8%EC%84%9C%20%EC%A0%95%EB%A6%AC/week2/jinhong.md#jpa%EC%99%80-jsp%EC%9D%98-%EA%B5%AC%EC%A1%B0-%EC%B0%A8%EC%9D%B4)
5. [참고자료](https://github.com/hongcoding94/Web_Service_Study/blob/53a7d6cd7c9692cf31769ea97074f3946980ea79/%EB%AC%B8%EC%84%9C%20%EC%A0%95%EB%A6%AC/week2/jinhong.md#%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C)

### 스프링 부트와 AWS로 혼자 구현하는 웹 서비스에서 나오는 "Spring Data"는 무엇인가?

- Spring Data란?
  <div align="center">
  
    <img src="https://user-images.githubusercontent.com/66407386/186048097-4ce6f310-9733-4a58-99ba-f83c2710bdb7.png" width="600" height="" />
    <p>Spring 공식문서 Spring Data의 내용 中</P>
  </div>

  - 기본 데이터 저장소의 특수한 특성을 유지하면서 **데이터 접근을 위한 친숙하고 일관된<br/>Spring기반의 프로그래밍 모델을 제공**하는 프로젝트
  
  - 아래의 기술들을 보다 쉽게 사용할 수 있도록 지원한다.
    - 데이터 접근 기술
    - Relational and non-relational database
    - map-reduce 프레임워크
    - 클라우드 기반의 서비스
    
  - 데이터베이스와 관련된 많은 하위 프로젝트를 포함하는 포괄적인 프로젝트(하위 참조)
    |Category|Sub-project|
    |---|---|
    |Relational Database|JPA<br/>JDBCC Extensions|
    |Big Data|Apache Hadoop|
    |Data-Grid|GemFire|
    |HTTP|REST|
    |Key Value Stores|Redis|
    |Document Stores|MongoDB|
    |Graph Databases|Neo4j|
    |Column Stores|HBase|
    |Common infrastrucure|Ccommons<br/>Grails Mapping|
    
  - 주요 모듈 
    - Spring Data Commons
    - Spring Data JDBC
    - Spring Data JDBC Ext
    - Spring Data JPA
    - Spring Data KeyValue
    - Spring Data LDAP
    - Spring Data MongoDB
    - Spring Data Redis
    - Spring Data REST
    - Spring Data for Apache Cassandra
    - Spring Data for Apache Geode
    - Spring Data for VMware Tanzu GemFire 

- Spring Data의 특징
  -  

### JSP란 무엇이며 어떻게 구조화 되어 있는가?

- 왜 JPA를 하는데 JSP를 내용을 다루는가?
  > JPA와 JSP의 구조는 다르기 때문에 해당 목차에서는 그 차이점을 비교하기 전에<br/>
  > JSP를 다시 한번 이해하기 위해서 작성하는 내용이다.


### JPA란 무엇이며 어떻게 구조화 되어 있는가?


### JPA와 JSP의 구조 차이


### 참고자료
1. 서적   - [스프링 부트와 AWS로 혼자 구현하는 웹 서비스](http://www.yes24.com/Product/Goods/83849117)
2. 공식문서 - [Spring공식문서 페이지](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
3. 블로그 - [girawhale님의 [JPA] JPA란? JPA를 사용하는 이유](https://girawhale.tistory.com/119)
4. 블로그 - [오리엔탈킴님의 [JPA] JPA란? Spring Data JPA로 간단 예제 프로젝트 구현](https://kim-oriental.tistory.com/20)
5. 영상   - [김성렬님(금오공과대학교)의 스프링과 JPA를 이용한 웹개발](http://www.kocw.net/home/cview.do?mty=p&kemId=1428755)
6. 영상   - [메타코딩님의 스프링부트 강좌 59강(블로그 프로젝트) - 스프링작동원리 복습](https://www.youtube.com/watch?v=S7LBQxgoVP0&t=17s)
7. 커뮤니티 - [人CoDOM 커뮤니티의 Spring Data](http://www.incodom.kr/Spring_Boot/Data)

