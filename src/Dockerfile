FROM tomcat:9.0

ADD  target/demo-0.0.1-SNAPSHOT.war /opt/tomcat/webapps/

EXPOSE 8082

CMD ["/opt/tomcat/bin/catalina.sh", "run"]
