# Pull base image
FROM tomcat:8.0.30-jre7

# Maintainer
MAINTAINER "franck.hubschwerle@uha.fr"
# Set Environment properties
ENV JAVA_OPTS=-Denvironment=production

# Copy war file to tomcat webapps folder
COPY /petitfilrouge.war /usr/local/tomcat/webapps/
COPY /tomcat-users.xml /usr/local/tomcat/conf