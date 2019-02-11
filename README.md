## API Gateway / Load Balancing / Proxy (Netflix OSS Zuul)

####
Build the service and run it
* Build using maven
```
mvn clean install
```
* Run the jar
    - App will be launched on **8082** port you can change it as per your need.
```
java -jar zuul-0.0.1-SNAPSHOT.jar --server.port=8082
```

* Test the content using your favourite browser and call the below rest endpoint
```
http://localhost:8082
```