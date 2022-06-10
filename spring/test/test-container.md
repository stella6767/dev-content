


## 쓰는 이유
- 운영 DB와 In-Memory DB의 문법이 100% 호환되지 않는다.
- In-Memory DB는 정상 동작하나 운영 DB에서는 동작하지 않을 수 있다.



## 의존성 설정


```
    testImplementation group: 'org.testcontainers', name: 'testcontainers', version: '1.15.3'
    testImplementation group: 'org.testcontainers', name: 'junit-jupiter', version: '1.15.3'
    testImplementation group: 'org.testcontainers', name: 'mysql', version: '1.15.3'

```

https://backtony.github.io/spring/2021-08-15-spring-test-2/


## init Script

```
jdbc:tc:postgresql:///schema_name?TC_INITSCRIPT=file:src/test/resources/schema.sql
```

https://stackoverflow.com/questions/53078306/populate-a-database-with-testcontainers-in-a-springboot-integration-test


## @TestConfiguration


@TestConfiguration 이 테스트 환경에서 필요한 빈들을 등록할 수 있도록 도와주는 어노테이션이다.

Nested @TestConfiguration



## Testcontainer Docker-compose 환경 구축하기


https://taes-k.github.io/2021/05/02/spring-test-container/



## 기타참고

https://sg-choi.tistory.com/543

https://honeyinfo7.tistory.com/305

https://isntyet.github.io/java/TestContainers%EB%A1%9C-test-%EB%A9%B1%EB%93%B1%EC%84%B1-%EB%86%92%EC%9D%B4%EA%B8%B0/