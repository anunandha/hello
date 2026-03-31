FROM tomcat:9.0-jdk17
COPY target/*.war /usr/local/tomcat/webapps/
EXPOSE 9090
CMD ["catalina.sh", "run"]
