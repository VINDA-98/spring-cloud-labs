# Spring Cloud Learning Labs

[简体中文](README.zh-CN.md)

A Maven lab workspace built around a department service. The examples use Spring Cloud Greenwich and Spring Boot 2.1 to demonstrate discovery, remote calls, failure handling, gateway routing and centralized configuration.

| Topic | Where to start |
| --- | --- |
| Service discovery and calls | [Eureka](springcloud-eureka-7001), [department provider](springcloud-provider-dept-8001), [consumer](springcloud-consumer-dept-80), and [Feign consumer](springcloud-consumer-dept-feign-80). |
| Failure handling and routing | [Hystrix provider](springcloud-provider-dept-hystrix-8001), [Hystrix dashboard](springcloud-consumer-hystrix-dashboard), and [Zuul gateway](springcloud-zuul-9527). |
| Centralized configuration | [Config Server](springcloud-config-server-3344) and [Config Client](springcloud-config-client-3355). |

The root [POM](pom.xml) lists the modules for the Maven reactor. The department-provider examples require a configured MySQL database.
