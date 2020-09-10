# DDD-Base
DDD的基本项目结构


## 结构描述

```
.
├─backend
│  └─src
│     └─main
│        ├─java
│        │  └─info
│        │      └─lostmylife
│        │          └─ddd-demo
│        │              └─backend
│        │                  ├─application
│        │                  │  └─service	应用服务
│        │                  ├─domain	领域结构
│        │                  │  └─demo
│        │                  │      ├─entity	领域实体
│        │                  │      ├─repository	仓储
│        │                  │      │  ├─mapper		orm
│        │                  │      │  ├─persistence	仓储实现
│        │                  │      │  └─po		数据库实体
│        │                  │      └─service	领域服务
│        │                  ├─infrastructure
│        │                  │  ├─common
│        │                  │  │  └─event
│        │                  │  ├─config	配置
│        │                  │  └─util		工具
│        │                  └─interfaces	接口层
│        │                     ├─assembler		转换服务
│        │                     └─facade	controller
│        └─resources
│            └─mapping
└─client
    └─src
        └─main
           ├─java
           │  └─info
           │      └─lostmylife
           │          └─ddd-demo
           │              └─client
           │                  ├─api		包装类
           │                  ├─model		请求与返回类
           │                  │  ├─dto		数据传输bean
           │                  │  │  └─demo
           │                  │  ├─param	增、删、改bean
           │                  │  │  └─demo
           │                  │  └─query	查询bean
           │                  │     └─demo
           │                  └─rest	rest client
           └─resources

```
