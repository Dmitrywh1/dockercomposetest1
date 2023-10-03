FROM ubuntu:latest

RUN apt-get update && apt-get install -y tomcat9

RUN mkdir /tomcat
RUN cp -r /usr/share/tomcat9 /tomcat/

VOLUME ["/tomcat"]

CMD ["echo", "Tomcat has been installed and moved to /tomcat directory"]