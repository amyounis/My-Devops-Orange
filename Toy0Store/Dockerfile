# create image from base image openjdk which a linux and has Java
FROM openjdk:8-jre-alpine
# copy jar file into image
COPY target/Toy0Store-1.0.jar /Toy0Store-1.0.jar 
EXPOSE 8000
# run application with this command line 
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/Toy0Store-1.0.jar"]
