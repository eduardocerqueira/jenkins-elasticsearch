# jenkins-elasticsearch

Jenkins sending data to elasticsearch 


```shell
docker-compose up -build
```

* [jenkins](http://localhost:8080/)
* [elasticsearch](http://localhost:9200/)
* [elastichq](http://localhost:5050)
* [grafana](http://localhost:3000)

```shell
Jenkins.instance.pluginManager.plugins.each{
  plugin -> 
    println ("${plugin.getShortName()}:${plugin.getVersion()}")
}
```

![img1](doc/images/Screenshot%20from%202021-12-19%2000-18-36.png)
![img2](doc/images/Screenshot%20from%202021-12-19%2000-23-47.png)
![img3](doc/images/Screenshot%20from%202021-12-19%2000-23-57.png)
