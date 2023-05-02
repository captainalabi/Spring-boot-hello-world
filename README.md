# Spring-boot-hello-world
To demonstrate how to start simple withspring boot
This is a simple hello world that serves as introduction to spring boot.
it contains only the main class which has the main method and hello method that takes a parameter; name and returns a String of hello combined with the submitted name arguement. 
@SpringBootApplication is same as @Configuration @EnableAutoConfiguration @ComponentScan; allows your application to be found and make configurations to be possible.
@RestController is a convenient annotation that combines @Controller and @ResponseBody, which eliminates the need to annotate every request handling method of the controller class with the @ResponseBody annotation. Allows us to auto-detect implementation classes through the classpath scanning and prepares the method as a response body.
@GetMapping("/hello") simply specifies /hello as a path variable for returing the hello greeting
