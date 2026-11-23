# Spring Cloud Learning Labs

[简体中文](README.zh-CN.md)

A Maven workspace for learning service discovery, remote calls, failure handling, routing, and centralized configuration with Spring Cloud Greenwich and Spring Boot 2.1. The examples use a shared department-service contract.

| Topic | Where to start |
| --- | --- |
| Service discovery and calls | [Eureka](springcloud-eureka-7001), [department provider](springcloud-provider-dept-8001), [consumer](springcloud-consumer-dept-80), and [Feign consumer](springcloud-consumer-dept-feign-80). |
| Failure handling and routing | [Hystrix provider](springcloud-provider-dept-hystrix-8001), [Hystrix dashboard](springcloud-consumer-hystrix-dashboard), and [Zuul gateway](springcloud-zuul-9527). |
| Centralized configuration | [Config Server](springcloud-config-server-3344) and [Config Client](springcloud-config-client-3355). |

The root [POM](pom.xml) declares the Feign module as `springcloud-consumer-dept-feign`, while the checked-in directory is `springcloud-consumer-dept-feign-80`. For a full Maven reactor build, those paths need to match. The department-provider examples also require a configured MySQL database.
