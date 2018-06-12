FROM tomcat:8
ADD tomcat-users.xml /usr/local/tomcat/conf
ADD pq-metrics-poc.war /usr/local/tomcat/webapps/
CMD["catalina.sh", "run"]


