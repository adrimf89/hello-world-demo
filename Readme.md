## Hello world demo

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

## Steps to Setup

**Build and run the app using maven**

```bash
mvn package
java -jar target/hello-world-demo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can run the app directly without packaging it like so -

```bash
mvn spring-boot:run
```

**Build the app using maven and create docker image**

```bash
mvn package dockerfile:build
```
