### 整合Springboot与ELK(Elasticsearch + Logstash + Kibana)


```
https://49qt701t.mirror.aliyuncs.com
docker pull logstash:6.6.2
docker pull wurstmeister/kafka
docker pull elasticsearch:6.6.2
docker pull kibana:6.6.2


#启动es
docker run -d -p 9200:9200 --name="es" elasticsearch:6.6.2

```