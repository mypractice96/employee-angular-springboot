# Start with a base image containing Java runtime
FROM java:8
# Make port 8080 available to the world outside this container
EXPOSE 8080
ADD target/springboot2-jpa-emp-crud.jar springboot2-jpa-emp-crud.jar
# Run the war file
ENTRYPOINT ["java","-jar","springboot2-jpa-emp-crud.jar"]