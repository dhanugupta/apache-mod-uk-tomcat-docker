FROM tomcat:7-jre8

ADD tomcat-users.xml /usr/local/tomcat/conf/

RUN rm -rf /usr/local/tomcat/webapps/ROOT

ADD ROOT.war /usr/local/tomcat/webapps/ROOT.war

CMD ["catalina.sh", "run"]
