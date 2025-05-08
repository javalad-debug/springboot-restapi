# Create a simple RESTful API using SpringBoot

To create a RESTful API with springboot is simple, you just need to create a spring MVC controller and you need to annotate it with  the @RestController annotation and within the controller we need to create a java method and we need to annotate it with an appropriate http annotation. For example the @GetMapping annotation.

Ref Path: 
```diff
springboot-rest-api\springboot-rest-api\src\main\java\net\javaguides\springboot\controller\HelloWorldController.java
```

## @GetMapping

The @GetMapping annotation is used to handle http get requests

```diff
+ @GetMapping("/hello-world")
```

```bash
    @GetMapping("/hello-world")
    public String helloWorld(){
        return "Hello World!";
    }

```

There are a couple of other annotations like,

```bash 
@PostMapping
@PutMapping
@DeleteMapping 

```


## @PostMapping

The @PostMapping annotation is used to handle http post requests

```diff
+ @PostMapping("/hello-world")
```

```bash
    @PostMapping("/hello-world")


```

## @PutMapping

The @PutMapping annotation is used to handle http put requests

```diff
+ @PutMapping("/hello-world")
```

```bash
    @PutMapping("/hello-world")


```

## @DeleteMapping

The @DeleteMapping annotation is used to handle http delete requests

```diff
+ @DeleteMapping("/hello-world")
```

```bash
    @DeleteMapping("/hello-world")


```
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

*****
