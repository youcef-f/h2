# h2

Pour avoir la console h2 ( http://localhost:8080/h2-console )  il faut:

## ou bien ajouter l'annnotation dans application properties

```shell
spring.h2.console.enabled=true
````

## ou bien ajouter la dépendance de spring devTools
```xml
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-devtools</artifactId>
</dependency>
```
