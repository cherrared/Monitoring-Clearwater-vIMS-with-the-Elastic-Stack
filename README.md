# Clear ELK

This is a docker-compose for monitoring the [Clearwater vIMS](https://www.projectclearwater.org/) with the [Elastic Stack](https://www.elastic.co/products/)

# How it works:

* To monitor Clearwater you should run the docker-elk repo first: [Docker elk](https://github.com/cherrared/Docker-elk)
* After that run the docker-compose.yml deploying Clearwater and Filebeat on dockers:


```
docker-compose up
```


## What's inside

- Docker compose file with Clearwater and an Elastic Stack configured 
- Filebeat.yml config file



