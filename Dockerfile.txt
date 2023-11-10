FROM tomcat:9.0.82-jdk11-corretto-al2
COPY ./target/MyMavenApp.war /usr/local/tomcat/webapps/MyMavenApp.war