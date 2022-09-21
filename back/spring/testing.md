
## 슬라이스 테스트(단위 테스트) 

@WebMvcTest
@WebFluxTest
@DataJpaTest
@JsonTest
@RestClientTest


[Querydsl 슬라이싱 테스트- DataJpaTest 문제](https://jyami.tistory.com/124)
<br/>

[@Sql](https://zzerosouth.tistory.com/51)
<br/>

[스프링 부트 버전 2.3.1 에서 H2 SQL 문법을 MySQL 문법으로 변경한 후 H2 콘솔 사용하는 방법](http://yoonbumtae.com/?p=2581)
<br/>

[Spring Boot DBUnit Starter 패키지를 만들었습니다.](https://blog.anyjava.net/124)
<br/>

[Mock multipart/form-data](https://blog.naver.com/getinthere/222767140080)
<br/>



[@Mock @MockBean @Spy @SpyBean 차이점](https://cobbybb.tistory.com/16)
<br/>

[@TestConfiguration]()
<br/>

[Spring testcontainer를 이용한 독립 테스트환경 구축](https://taes-k.github.io/2021/05/02/spring-test-container/)
<br/>

[스프링부트에서 DbUnit 을 이용하여 DB 테스트 해보기](https://techblog.woowahan.com/2650/)
<br/>

[Spring Boot에서 테스트를 - 1](https://hyper-cube.io/2017/08/06/spring-boot-test-1/)
<br/>


[Invocation of destroy method failed on bean with name 'inMemoryDatabaseShutdownExecutor': org.h2.jdbc.JdbcSQLNonTransientConnectionException: Database is already closed (to disable automatic closing at VM shutdown, add ";DB_CLOSE_ON_EXIT=FALSE" to the db URL)]()


#### SpringBoot TestContainer 참고
- 운영 DB와 In-Memory DB의 문법이 100% 호환되지 않는다.
- In-Memory DB는 정상 동작하나 운영 DB에서는 동작하지 않을 수 있다.

의존성 설정
```
    testImplementation group: 'org.testcontainers', name: 'testcontainers', version: '1.15.3'
    testImplementation group: 'org.testcontainers', name: 'junit-jupiter', version: '1.15.3'
    testImplementation group: 'org.testcontainers', name: 'mysql', version: '1.15.3'
```

- https://backtony.github.io/spring/2021-08-15-spring-test-2/

init Script
```
jdbc:tc:postgresql:///schema_name?TC_INITSCRIPT=file:src/test/resources/schema.sql
```
- https://stackoverflow.com/questions/53078306/populate-a-database-with-testcontainers-in-a-springboot-integration-test
- https://sg-choi.tistory.com/543
- https://honeyinfo7.tistory.com/305
- https://isntyet.github.io/java/TestContainers%EB%A1%9C-test-%EB%A9%B1%EB%93%B1%EC%84%B1-%EB%86%92%EC%9D%B4%EA%B8%B0/


## Testing tool

[JUnit+Mockito vs Groovy+Spock](https://yangbongsoo.gitbook.io/study/junit+mockito_vs_groovy+spock)


[ Task :asciidoctor NO-SOURCE ](https://sas-study.tistory.com/371)

[JUnit 무시 테스트 케이스 : JUnit 4 @Ignore Vs JUnit 5 @Disabled](https://ko.myservername.com/top-25-jdbc-interview-questions)

[Spring REST Docs](https://docs.spring.io/spring-restdocs/docs/current/reference/html5/#documenting-your-api-request-response-payloads)

[Spring Boot Test](https://meetup.toast.com/posts/124)

[JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/#overview)

[JUnit5 완벽 가이드](https://donghyeon.dev/junit/2021/04/11/JUnit5-%EC%99%84%EB%B2%BD-%EA%B0%80%EC%9D%B4%EB%93%9C/)

[Spring Boot의 @TestConfiguration 주석으로 테스트하기](https://reflectoring.io/spring-boot-testconfiguration/)

[]()

[]()
[]()
[]()
[]()