# 1 Base Image for OS

FROM eclipse-temurin:21-jdk-jammy

# 2 working Directory for the application

WORKDIR /app

# 3 code for creating the application

COPY src/Main.java /app/Main.java

COPY quotes.txt quotes.txt

# 4 Run the command to install the libs to compile the code

RUN javac Main.java

# 5 Exposing the port

EXPOSE 8000

# 6 server the app and keep it running so thats why i wont use RUN

CMD ["java","Main.java"]
