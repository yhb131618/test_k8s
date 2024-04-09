# 기본 이미지로 Java 환경 설정
FROM openjdk:17-jdk-alpine

# JAR 파일 복사

COPY build/libs/example.jar

# 애플리케이션 실행
ENTRYPOINT ["java","-jar","/example.jar"]

