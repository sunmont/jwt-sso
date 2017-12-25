# jwt-sso
Cookie based Single Sign On (SSO) with JSON Web Token (JWT) powered by Spring Boot in Java.<br/>

Authentication & Authorization Service
The service provides authentication to protect resources (a resource service or any defined resource)<br/>
And it uses persistent cookie to offer single sign on (sso).<br/>
the cookie is secured by modern JWT token, which carries all necessary information by itself.<br/>
The JWT token can be redirected saftely around resouce services and auth services.<br/>

The Auth service's security then is enhanced by Spring Security framework.<br/>


Compile:
```
gradle build
```

Boot Run:
```
gradle bootRun
```

Requirements:
```
JDK 1.8+
Spring Boot 1.5.9
Gradle 2.10+
jjwt 0.7.0
```
