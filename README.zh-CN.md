# Spring Cloud 学习示例

[English](README.md)

一组使用 Spring Cloud Greenwich 和 Spring Boot 2.1 的 Maven 示例。代码围绕部门服务展开，涵盖服务发现、远程调用、故障处理、网关路由和集中配置。

| 主题 | 阅读入口 |
| --- | --- |
| 服务发现与调用 | [Eureka](springcloud-eureka-7001)、[部门服务提供方](springcloud-provider-dept-8001)、[消费方](springcloud-consumer-dept-80)和 [Feign 消费方](springcloud-consumer-dept-feign-80)。 |
| 故障处理与路由 | [Hystrix 服务提供方](springcloud-provider-dept-hystrix-8001)、[Hystrix 监控面板](springcloud-consumer-hystrix-dashboard)和 [Zuul 网关](springcloud-zuul-9527)。 |
| 集中配置 | [Config Server](springcloud-config-server-3344) 和 [Config Client](springcloud-config-client-3355)。 |

根目录的 [POM](pom.xml) 列出了 Maven 聚合构建包含的模块。部门服务提供方的示例需要配置 MySQL。
