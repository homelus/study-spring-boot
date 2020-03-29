# [Auto-Configuration](https://docs.spring.io/spring-boot/docs/2.2.4.RELEASE/reference/html/using-spring-boot.html#using-boot-auto-configuration)

Spring Boot auto-configuration 은 설정으로 추가된 jar 종속성들을 대상으로 Spring Application 을 자동으로 설정하려고 시도합니다.
예를 들어, `HSQLDB` 가 클래스패스에 있고 데이터베이스 커넥션 빈들을 수동으로 설정하지 않는다면 Spring-Boot 는 in-memory database 를 자동으로 설정합니다.


