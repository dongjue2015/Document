#   Spring boot 基本教程

------
##  简介
Spring Boot是由Pivotal团队提供的全新框架，其设计目的是用来简化新Spring应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。
推出springboot的初衷就是为了简化spring的配置，使得开发中集成新功能时更快，简化或减少相关的配置。Spring框架功能很强大，但是就算是一个很简单的项目，我们也要配置很多东西。因此就有了Spring Boot框架，它的作用很简单，就是帮我们自动配置。Spring Boot框架的核心就是自动配置，只要存在相应的jar包，Spring就帮我们自动配置。如果默认配置不能满足需求，我们还可以替换掉自动配置类，使用我们自己的配置。另外，Spring Boot还集成了嵌入式的Web服务器，系统监控等很多有用的功，让我们快速构建企业及应用程序。
## 初衷
- Spring 设计初衷，简化配置，使得开发中集成功能时更快，简化或减少配置。
#  社区文档
-  [英文文档](http://projects.spring.io/spring-boot/)
#  子项目说明
- initial spring boot application  springboot 应用程序
- complete spring boot restful restFul接口定义
- consuming-rest  restFul 接口调用

# 注解
- @Bean 标注在方法(返回某个实例的方法) ,等价于spring的xml配置文件中的<bean>，作用：注册bean对象.
