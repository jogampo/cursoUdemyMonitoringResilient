# cursoUdemyMonitoringResilient

El nombre del curso de udemy es: Microservices Observability, Resilience, Monitoring on .Net


Este curso se ven cosas de resiliencia y de monitorización.

repo del instructor: http://github.com/aspnetrun/run-aspnetcore-microservices


## Cómo agregar un dockerfile.

En el visualstudio se hace click derecho sobre el proyecto y se agrega docker support o compatibilidad con docker si tenemos en español el visual studio. Se dice que linux y docker file y nos genera un dockerfile. 

## Launch microsvercies:

* **Catalog API -> http://host.docker.internal:8000/swagger/index.html**
* **Basket API -> http://host.docker.internal:8001/swagger/index.html**
* **Discount API -> http://host.docker.internal:8002/swagger/index.html**
* **Ordering API -> http://host.docker.internal:8004/swagger/index.html**
* **Shopping.Aggregator -> http://host.docker.internal:8005/swagger/index.html**
* **API Gateway -> http://host.docker.internal:8010/Catalog**
* **Rabbit Management Dashboard -> http://host.docker.internal:15672**   -- guest/guest
* **Portainer -> http://host.docker.internal:9001**   -- admin/admin1234 (Esta contraseña no fué la que puse no recuerdo cual puse 😢)
* **pgAdmin PostgreSQL -> http://host.docker.internal:5050**   -- admin@aspnetrun.com/admin1234
* **Elasticsearch -> http://host.docker.internal:9200**
* **Kibana -> http://host.docker.internal:5601**

* **Web Status -> http://host.docker.internal:8007**
* **Web UI -> http://host.docker.internal:8006**

5. Launch http://host.docker.internal:8007 in your browser to view the Web Status. Make sure that every microservices are healthy.
6. Launch http://host.docker.internal:8006 in 