FROM hub.idig88.com:8888/micro-service/java:openjdk-8
MAINTAINER liming www.idig8.com

COPY target/course-edge-service-1.0-SNAPSHOT.jar /course-edge-service.jar

ENTRYPOINT ["java","-jar","/course-edge-service.jar"]