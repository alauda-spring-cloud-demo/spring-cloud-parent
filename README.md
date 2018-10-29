### linkme的maven父项目，包含公共依赖pom

#### 目前所涉及微服务治理组件（基于Spring Cloud）：
1. Spring Cloud Eureka（服务注册/发现中心）参照[eureka-server](https://code.aliyun.com/linkme/eureka-server)项目
2. Spring Cloud Config Server（配置中心）参照[config-server](https://code.aliyun.com/linkme/config-server)项目
3. Spring Cloud OAuth2（授权/认证中心）参照[oauth2-server](https://code.aliyun.com/linkme/oauth2-server)项目
4. Spring Cloud Gateway（微服务网关）参照[gateway](https://code.aliyun.com/linkme/gateway)项目

#### 目前所涉及基础库：
1. Gateway（数据库版本管理）
2. Mybatis + 通用Mapper + PageHelper（Mybatis家族）
3. Lombok（代码简化库，简化Getter、Setter、Logger、Builder等等）
