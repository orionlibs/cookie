# Orion Cookie
Java library that provides utilities for HTTP cookies.

Please check the wiki

https://github.com/orionlibs/google-maps-wrapper/wiki

You can import the library by using:  
```xml
<dependency>
    <groupId>io.github.orionlibs</groupId>
    <artifactId>cookie</artifactId>
    <version>1.0.0</version>
</dependency>
```

To use this service, you can do:
```java
CookieService.createJavaCookie("cookieName", "myValue", "domainOptional", expirationInSeconds);
```
There are more methods in the CookieService