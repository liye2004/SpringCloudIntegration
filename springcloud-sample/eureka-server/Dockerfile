FROM java:8u111-jre-alpine

WORKDIR /home/apps/
ADD target/eureka-server-0.0.1-SNAPSHOT.jar .
ADD start.sh .

ENTRYPOINT ["sh", "/home/apps/start.sh"]