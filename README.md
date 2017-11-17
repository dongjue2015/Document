#   Spring boot 

------
#  简介
Spring Boot是由Pivotal团队提供的全新框架，其设计目的是用来简化新Spring应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。
推出springboot的初衷就是为了简化spring的配置，使得开发中集成新功能时更快，简化或减少相关的配置。Spring框架功能很强大，但是就算是一个很简单的项目，我们也要配置很多东西。因此就有了Spring Boot框架，它的作用很简单，就是帮我们自动配置。Spring Boot框架的核心就是自动配置，只要存在相应的jar包，Spring就帮我们自动配置。如果默认配置不能满足需求，我们还可以替换掉自动配置类，使用我们自己的配置。另外，Spring Boot还集成了嵌入式的Web服务器，系统监控等很多有用的功，让我们快速构建企业及应用程序。
#  核心启动器
Table 13.1. Spring Boot application starters

Name	Description	Pom
spring-boot-starter
Core starter, including auto-configuration support, logging and YAML
Pom
spring-boot-starter-activemq
Starter for JMS messaging using Apache ActiveMQ
Pom
spring-boot-starter-amqp
Starter for using Spring AMQP and Rabbit MQ
Pom
spring-boot-starter-aop
Starter for aspect-oriented programming with Spring AOP and AspectJ
Pom
spring-boot-starter-artemis
Starter for JMS messaging using Apache Artemis
Pom
spring-boot-starter-batch
Starter for using Spring Batch
Pom
spring-boot-starter-cache
Starter for using Spring Framework’s caching support
Pom
spring-boot-starter-cloud-connectors
Starter for using Spring Cloud Connectors which simplifies connecting to services in cloud platforms like Cloud Foundry and Heroku
Pom
spring-boot-starter-data-cassandra
Starter for using Cassandra distributed database and Spring Data Cassandra
Pom
spring-boot-starter-data-cassandra-reactive
Starter for using Cassandra distributed database and Spring Data Cassandra Reactive
Pom
spring-boot-starter-data-couchbase
Starter for using Couchbase document-oriented database and Spring Data Couchbase
Pom
spring-boot-starter-data-elasticsearch
Starter for using Elasticsearch search and analytics engine and Spring Data Elasticsearch
Pom
spring-boot-starter-data-jpa
Starter for using Spring Data JPA with Hibernate
Pom
spring-boot-starter-data-ldap
Starter for using Spring Data LDAP
Pom
spring-boot-starter-data-mongodb
Starter for using MongoDB document-oriented database and Spring Data MongoDB
Pom
spring-boot-starter-data-mongodb-reactive
Starter for using MongoDB document-oriented database and Spring Data MongoDB Reactive
Pom
spring-boot-starter-data-neo4j
Starter for using Neo4j graph database and Spring Data Neo4j
Pom
spring-boot-starter-data-redis
Starter for using Redis key-value data store with Spring Data Redis and the Jedis client
Pom
spring-boot-starter-data-redis-reactive
Starter for using Redis key-value data store with Spring Data Redis reactive and the Lettuce client
Pom
spring-boot-starter-data-rest
Starter for exposing Spring Data repositories over REST using Spring Data REST
Pom
spring-boot-starter-data-solr
Starter for using the Apache Solr search platform with Spring Data Solr
Pom
spring-boot-starter-freemarker
Starter for building MVC web applications using FreeMarker views
Pom
spring-boot-starter-groovy-templates
Starter for building MVC web applications using Groovy Templates views
Pom
spring-boot-starter-hateoas
Starter for building hypermedia-based RESTful web application with Spring MVC and Spring HATEOAS
Pom
spring-boot-starter-integration
Starter for using Spring Integration
Pom
spring-boot-starter-jdbc
Starter for using JDBC with the Tomcat JDBC connection pool
Pom
spring-boot-starter-jersey
Starter for building RESTful web applications using JAX-RS and Jersey. An alternative to spring-boot-starter-web
Pom
spring-boot-starter-jooq
Starter for using jOOQ to access SQL databases. An alternative to spring-boot-starter-data-jpa or spring-boot-starter-jdbc
Pom
spring-boot-starter-jta-atomikos
Starter for JTA transactions using Atomikos
Pom
spring-boot-starter-jta-bitronix
Starter for JTA transactions using Bitronix
Pom
spring-boot-starter-jta-narayana
Spring Boot Narayana JTA Starter
Pom
spring-boot-starter-mail
Starter for using Java Mail and Spring Framework’s email sending support
Pom
spring-boot-starter-mobile
Starter for building web applications using Spring Mobile
Pom
spring-boot-starter-mustache
Starter for building web applications using Mustache views
Pom
spring-boot-starter-quartz
Spring Boot Quartz Starter
Pom
spring-boot-starter-security
Starter for using Spring Security
Pom
spring-boot-starter-social-facebook
Starter for using Spring Social Facebook
Pom
spring-boot-starter-social-linkedin
Stater for using Spring Social LinkedIn
Pom
spring-boot-starter-social-twitter
Starter for using Spring Social Twitter
Pom
spring-boot-starter-test
Starter for testing Spring Boot applications with libraries including JUnit, Hamcrest and Mockito
Pom
spring-boot-starter-thymeleaf
Starter for building MVC web applications using Thymeleaf views
Pom
spring-boot-starter-validation
Starter for using Java Bean Validation with Hibernate Validator
Pom
spring-boot-starter-web
Starter for building web, including RESTful, applications using Spring MVC. Uses Tomcat as the default embedded container
Pom
spring-boot-starter-web-services
Starter for using Spring Web Services
Pom
spring-boot-starter-webflux
Starter for building WebFlux applications using Spring Framework’s Reactive Web support
Pom
spring-boot-starter-websocket
Starter for building WebSocket applications using Spring Framework’s WebSocket support
Pom
