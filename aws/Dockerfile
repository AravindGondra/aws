FROM tomcat:jdk8

ADD target/aws.war /usr/local/tomcat/webapps/

EXPOSE 8080

CMD ["catalina.sh", "run"]