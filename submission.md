

```dockerfile
# Dockerfile
FROM	openjdk:8u191-jre-alpine
EXPOSE	8080
COPY	./target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar /usr/app/
WORKDIR	/usr/app/
ENTRYPOINT	["java", "-jar", "spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar"]
```

![](Images/HW8/docker%201.PNG)

![](Images/HW8/docker%203.PNG)
