# visualize_pilot

An example project - Spring Web Project with RestController and JQuery

## Getting Started

This project is an example of spring web application which can show movie list in DB.

### Setting Environment

```
JDK 1.8u231
Eclipse
    - STS Plugin(Spring Tools 3 Add-On for Spring Tools 4)
Apache Tomcat 9
    - Add the Tomcat server to the project
MariaDB 10.4.10
    - theater.movie(int id, String movie_name, String director, String types)
JQuery Library
	- jquery-3.4.1.min.js
```

    pom.xml properties
        - check java-version
        - check springframework-version
    pom.xml plugin
        - check maven-compiler-plugin version
        - match source and target to java-version
    pom.xml dependency
        - mariadb-java-client
        - commons-dbcp
        - spring-jdbc
        - mybatis
        - mybatis-spring
        - log4jdbc-log4j2-jdbc4.1
        - jackson

### Issues

__Issue 1__
    
    Modify an existing controller to create a rest controller(@RestController & @RequstMapping)
        result: localhost:8080/visualize_pilot/restex -> json data

__Issue 2__

	Add resources
		- jQuery Library: jquery-3.4.1.min.js
		- css file for screen design
		- js file for getting data(json data) with using ajax


### Example

![result](https://github.com/dianakoh/visualize_pilot/blob/master/result.png)