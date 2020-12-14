FROM openjdk:8
ENV PORT 8080
#ontimize app port
EXPOSE 8080
#app
COPY ./boot/target/REPLACE_ME_APP_NAME-boot.jar /opt/REPLACE_ME_APP_NAME-boot.jar
WORKDIR /opt
CMD ["java", "-XX:+UnlockExperimentalVMOptions", "-XX:+UseCGroupMemoryLimitForHeap", "-jar", "REPLACE_ME_APP_NAME-boot.jar"]
