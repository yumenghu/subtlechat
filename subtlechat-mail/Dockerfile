FROM java:8u111-jdk-alpine

WORKDIR app
ADD ./target/subtlechat-mail.jar ./

CMD ["java","-jar", "subtlechat-mail.jar"," --spring.profiles.active=${SPRING_PROFILES_ACTIVE}"]
