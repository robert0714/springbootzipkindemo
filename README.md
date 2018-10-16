# springbootzipkindemo

使用STS的Run As於 ** com.springboot.zipkin.demo.springbootzipkin.UserAddressService **

** com.springboot.zipkin.demo.springbootzipkin.UserGreetingService **

** com.springboot.zipkin.demo.springbootzipkin.UserNameService **

的Spring Boot App


# Tutoriuals
** https://www.javacodegeeks.com/2018/03/springboot-microservices-tracing-with-zipkin-and-sleuth.html **




# Test
```
wget -O zipkin.jar 'https://search.maven.org/remote_content?g=io.zipkin.java&a=zipkin-server&v=LATEST&c=exec'
```

```
docker-compose up 
```



** http://localhost:9411/zipkin/  **

** http://localhost:3000/api/user/greet   **
