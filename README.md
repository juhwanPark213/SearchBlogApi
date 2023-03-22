# 블로그 검색 API
----------------------
## 개발 환경
+ 기본 환경
  + IDE: STS
  + OS: Window 10
  + GIT
+ Server
  + Java17
  + Spring Boot 3.0.4
  + JPA
  + H2
  + Gradle
  + Junit5
  
## 빌드 및 실행
+ Git, Java17 는 설치되어 있다고 가정합니다.
+ Executable jar 파일 위치 : blogAPI/build/libs/blogApi-0.0.1-SNAPSHOT.jar (https://github.com/juhwanPark213/blogApi/tree/main/blogAPI/build/libs)
```
$ git clone https://github.com/juhwanPark213/blogApi.git
$ cd blogApi
$ gradlew clean build
$ java -jar build/libs/blogApi-0.0.1-SNAPSHOT.jar
```

+ 접속 URI: ```http://localhost:8080```
