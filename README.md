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
1. 拉取[jeecg-spring-boot-starter](https://github.com/tanpenggood/jeecg-spring-boot-starter)，执行`mvn install`将它安装到本地仓库
2. 新建`spring boot`项目
3. 引入依赖`jeecg-spring-boot-starter`（步骤一安装在本地的）
4. 相关类
    - org.jeecg.JeecgApplication
    - org.jeecg.JeecgOneGUI
    - org.jeecg.JeecgOneToMainUtil
5. 相关资源
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
