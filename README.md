# Containerization_of_Java_project_using_Docker

# Steps
1. Customize Mysql image (as database) using Dockerfile
2. Customize Tomcat image (as webserver) using Dockerfile
3. Customize Nginx image (as loadbalancer) using Dockerfile
4. Build the java app using
```
mvn install
```
5. Build customize images
6. Create docker-compose.yml file (refer to application.properties file)

# Files
1. Dockerfiles: contains Dockerfiles of Mysql,Tomcat and Nginx
2. pom.xml: application before build 
3. target: application after build
4. application.properties
5. docker-compose.yml

# Run 
. Run the application by using 
```
docker-compose up
```
