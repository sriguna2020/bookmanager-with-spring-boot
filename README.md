# Bookmanager w/ Spring Boot


## Frontend build

```
[project-root] $ grunt install
[project-root] $ grunt build
```

This process will generate resourecs/{static,templates} from resoureces/work.

In the default, Spring will refer to `classpath:work` for view-templates. you can change where to refer by editting `spring.thymeleaf.prefix` in application.properties.


## Build and run

```
[project-root] $ MAVEN_OPTS="-javaagent:springloaded-1.2.1.jar -noverify
```
