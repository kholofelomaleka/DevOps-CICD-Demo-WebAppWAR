FROM tomcat:10.0.6-jdk16-openjdk-slim

#Setting Worker Directory to webapps.dist folder

WORKDIR /usr/local/tomcat/webapps.dist

#Copying all files in webapps.dist to webapps folder
RUN cp -r * /usr/local/tomcat/webapps/

# Copying the war file in a folder to the path inside the Container

COPY ./target/webapp.war /usr/local/tomcat/webapps/

#Creating a volume for webapp

#VOLUME webappserver
