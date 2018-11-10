FROM java:8
VOLUME /tmp
COPY configserver-1.0-SNAPSHOT.jar /home/atl/Desktop/Services/configserver/app.jar
RUN sh -c 'touch /home/atl/Desktop/Services/configserver/app.jar'
ENTRYPOINT ["sh", "-c", "java -Djava.security.egd=file:/dev./urandom -jar /home/atl/Desktop/Services/configserver/app.jar"]