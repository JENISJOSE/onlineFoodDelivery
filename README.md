# Online food Delivery System 
online food delivery system using 
## Technologies used
<pre>
<details><summary>Use the technologies for restaurant Microservice</summary>
<p>
 * Java Persistence Query Language (JPQL)
 * Used fetch type Lazy which lazy and fetching strategy subselect SUBSELECT
(between restaurant entity, food menu entity )
 * Aspect-oriented programming for each rest call (@before and @AfterReturning,
 * logging aspect on file, rest, service and Dao package )
 * Messaging AMQP and Rabbitmq
 * Spring Rest Global exception handling (@ContollerAdvice)
 * Hibernate Validator
 * Jackson (data binding passed data that Rest Controller to Java POJO )
</p>
</details>
<details><summary>Use the technologies for Order Microservice</summary>
<p>
* Email
* Java Persistence Query Language (JPQL)
* Used fetch type Lazy which lazy and fetching strategy subselect SUBSELECT (
restaurant entity, food menu entity )
* Aspect-oriented programming for each rest call (@before and @AfterReturning,
logging aspect on file, rest, service and Dao package )
* Messaging AMQP and Rabbitmq
* Spring Rest Global exception handling (@ContollerAdvice)
* Hibernate Validator
* Jackson (data binding passed data that Rest Controller to Java POJO )
* Email
</p>
</details>
<pre>
High-Level Design Diagram
# High level solution design 
![High level solution design](https://github.com/MahiSharew/onlineFoodDelivery/blob/master/img/High-LevelDesignDiagram.png)
> High level  design 
---
Order microservice to Restaurant microservice communication using AMQP and RabbitMQ
![AMQP and RabbitMQ](https://github.com/MahiSharew/onlineFoodDelivery/blob/master/img/message.jpg)
> AMQP and RabbitMQ
---
