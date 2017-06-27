# springboot-cloud

:point_right:基于springBoot+springCloud构建的分布式微服务。:point_left:

## 目录结构
```shell
├── sbc-common                                    // common包，通用组件。  
│   ├── src/main
│   ├── ├──java/com/crossoverJie/sbcorder/common  // 具体代码。  
│   ├── ├──resources
├── sbc-order                                     // order应用
│   ├── src/main
│   ├── ├──java/com/crossoverJie/sbcorder         // 具体代码
│   ├── ├──resources
├── sbc-service                                   // eureka-server注册中心
│   ├── src/main
│   ├── ├──java/com/crossoverJie/service/         // 具体代码
│   ├── ├──resources
├── sbc-user                                      // user应用
│   ├── src/main
│   ├── ├──java/com/crossoverJie/sbcuser/
│   ├── ├──resources
├── .gitignore                                    // git忽略项
├── LICENSE                
├── README.md               


```


- SpringBoot+SpringCloud初探 ：[https://crossoverjie.top/2017/06/15/sbc1/](https://crossoverjie.top/2017/06/15/sbc1)

![https://ooo.0o0.ooo/2017/06/26/59511cef59d46.jpg](https://ooo.0o0.ooo/2017/06/26/59511cef59d46.jpg)


## TODO List

* [x] SpringBoot+SpringCloud初探:[https://crossoverjie.top/2017/06/15/sbc1/](https://crossoverjie.top/2017/06/15/sbc1)
* [ ] `Feign`声明式远程调用,`Eureka`高可用注册中心,`Swagger2`管理`REST API`。
* [ ] 基于`SpringBoot`重构:[https://github.com/crossoverJie/SSM-REQUEST-CHECK](https://github.com/crossoverJie/SSM-REQUEST-CHECK)
* [ ] 通用的异常处理、日志插件、集成logback。
* [ ] 其他待续。。。




