# Zipkin test
copyied from https://howtodoinjava.com/spring/spring-cloud/spring-cloud-zipkin-sleuth-tutorial/

# Overview
zipkin-service-1(api) -> zipkin-service-2 (api)-> zipkin-service-3(api) -> zipkin-service-4(api)

# Preparations
## zipkin quick start
```
curl -sSL https://zipkin.io/quickstart.sh | bash -s
java -jar zipkin.jar
```

# Run
```
cd zipkin-service-1
mvn clean package
cd target/zipkin-service-1-0.0.1-SNAPSHOT.jar

 ...

cd zipkin-service-4
mvn clean package
cd target/zipkin-service-4-0.0.1-SNAPSHOT.jar
```

