FROM tomcat:9-jre8

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/company-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD ["catalina.sh", "run"]
