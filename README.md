## 简介

Jeecg Spring Boot Starter Demo.

## Maven安装

在项目的pom.xml的dependencies中加入以下内容:
```xml
<dependency>
    <groupId>com.itplh.opensource</groupId>
    <artifactId>jeecg-spring-boot-starter</artifactId>
    <version>2.2.1</version>
</dependency>
```

## Usage

**步骤**
1. 新建`spring boot`项目
2. 引入依赖`jeecg-spring-boot-starter`
3. 相关类
    - org.jeecg.JeecgApplication
    - org.jeecg.JeecgOneGUI
    - org.jeecg.JeecgOneToMainUtil
4. 相关资源
    ```
    resources
        jeecg
        static
        templates
        application.yml
        application-dev.yml
        application-prod.yml
        application-test.yml
        banner.txt
        logback-spring.xml
    ```
5. 启动项目，使用[jeectboot的前端](https://github.com/zhangdaiscott/jeecg-boot/tree/master/ant-design-vue-jeecg)访问