#Run using docker
1. docker build . --tag demo
2. docker run -it -p8282:8282 demo:latest
#Run native
1. gite clone https://gitlab.com/GLG204/administration/backend/spring-boot-admin.git
2. cd spring-boot-admin
3. mvn package
4. java -jar target/demo.jar 
