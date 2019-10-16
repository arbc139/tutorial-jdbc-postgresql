# 2019-2 Database JDBC-PostgreSQL Example
연세대학교 컴퓨터과학과 2019-2 Database 수업의 JDBC-PostgreSQL 예제입니다.

## Prerequisites
### Java 8
Java 8을 지원하는 `Oracle-JDK 11.0.4` 혹은 `OpenJDK 8`을 설치해주세요.

* [Oracle-JDK 링크](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [OpenJDK 8 링크](https://openjdk.java.net/install/)

### IDE
IDE는 `Intellij` 혹은 `Eclipse`를 사용해주세요.

### Build Tool
Build Tool은 `Maven`을 사용해주세요.

## How to compile?
다음 Command로 compile할 수 있습니다.

```bash
mvn clean package
```

이 결과로, `target/jdbc-postgresql-example-1.0-SNAPSHOT-jar-with-dependencies.jar` 파일이 생성됩니다.

## How to run?
다음 Command로 jar 파일을 실행시킬 수 있습니다.

```bash
java -jar target/jdbc-postgresql-example-1.0-SNAPSHOT-jar-with-dependencies.jar
```

혹은 `Intellij`와 `Eclipse`에서 `Maven`을 설정하신 뒤, 바로 실행하셔도 무방합니다.

실행시키기 전에 꼭 PostgreSQL 서버를 켜주시고(혹은 pgAdmin을 실행), `jdbc_example_university` Database를 생성한 뒤, 실행시켜주세요.

## PostgreSQL ID & Password
PostgreSQL의 ID와 Password는 코드 내부에 하드코딩 되어 있습니다...

바꾸셔야 한다면, Props의 ID와 Password를 변경하고, 재컴파일하여 실행해주세요.
