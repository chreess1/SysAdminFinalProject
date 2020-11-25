# using multistage docker build
# ref: https://docs.docker.com/develop/develop-images/multistage-build/

# temp container to build using gradle
FROM openjdk:11-jdk-alpine
COPY ./springdemo/ChrisWoodWebApp.jar ./springdemo/ChrisWoodWebApp.jar
CMD ["java","-jar","ChrisWoodWebApp.jar"]
