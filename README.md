  整个微服务的开发是基于SpringBoot的，OAuth2.0是用来进行授权操作的，JWT用来封装用户的授权信息，Spring AMQP是消息队列协议。然后就是一套Spring Cloud的微服务框架。

  持久化技术栈选用了MyBatis+通用Mapper，还用到了SpringDataEs用来操作ElasticSearch，SpringDataRedis用来操作Redis。

  数据库采用了MySQL，消息队列选用了RabbitMQ，还实现了MySQL读写分离。

  支付接口就选择了微信支付。
