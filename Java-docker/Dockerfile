#pull base image
FROM eclipse-temurin:17-jdk-alpine  

#create the folder where app code will be stored
WORKDIR /app

#copy the source code from host machine to container
COPY src/Main.java /app/Main.java

#compile the application code
RUN javac Main.java

#run the application
CMD ["java","Main"]
