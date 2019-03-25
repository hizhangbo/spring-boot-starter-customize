# spring-boot-starter-customize
自定义场景启动器  

## Spring Boot核心功能自动装配及场景启动器的深度实践

1. 约定大于配置
```java
# 绑定默认配置
@ConfigurationProperties
# 启用默认配置
@EnableConfigurationProperties

# 标识配置类
@Configuration
# 特定条件下配置类生效
@ConditionalOnXXX
# 配置类顺序
@AutoConfigureAfter
```
2. 自动装配
```properties
# 自动配置类需配置在下面的文件中
META-INF/spring.factories
```

[Demo](https://github.com/eugenp/tutorials/tree/master/spring-boot-custom-starter)
[Tutorials](https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-developing-auto-configuration.html)
[SpringBoot自动配置原理](http://www.importnew.com/30599.html)
[SpringBoot自定义Starter](http://www.importnew.com/30610.html)
