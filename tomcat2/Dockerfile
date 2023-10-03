FROM ubuntu:latest

RUN apt-get update && apt-get install -y tomcat9

COPY --from=0 /tomcat /usr/share/tomcat9
EXPOSE 8080

CMD ["catalina.sh", "run"]