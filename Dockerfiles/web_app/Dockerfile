FROM tomcat:8-jre11
#remove default webapp
RUN rm -rf /usr/local/tomcat/webapps/*
#add the new app after build it
COPY ./vprofile-v2.war  /usr/local/tomcat/webapps/ROOT.war
WORKDIR /usr/local/tomcat
EXPOSE 8080
CMD ["catalina.sh","run"]

