# mk217
Spring Boot2.0深度实践之核心技术篇
Spring Boot2.0深度实践之核心技术篇
[![下载地址](https://img.mukewang.com/szimg/5fcdffb30910d31a05400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 系列总览 

#### 总览 Spring Boot 2.0 深度实践系列课程的整体议程，包括 Spring Boot 三大核心特性（组件自动装配、嵌入式Web容器、生产准备特性）、Web 应用（传统 Servlet、Spring Web MVC、Spring WebFlux）、数据相关（JDBC、JPA、事务）、功能扩展（SpringApplication、Spring Boot 配置、Spring Boot Starter）以及...
1-1 -课程导学 (15:58)

1-2 为什么说Spring Boot 2.0 易学难精？ (09:05)

1-3 开场白：系列总览 (02:52)

1-4 核心特性介绍 (03:25)

1-5 核心特性之组件自动装配工程部分 (09:10)

1-6 Web应用介绍 (01:34)

1-7 传统 Servelt 应用 (09:26)

1-8 异步非阻塞 Servlet 代码示例 (03:18)

1-9 Spring Web MVC 应用介绍 (11:16)

1-10 Spring WebFlux 应用 (05:33)

1-11 Web Server 应用 (09:08)

1-12 数据相关介绍 (15:01)

1-13 功能扩展介绍 (11:50)

1-14 运维管理介绍 (11:29)


### 第2章 走向自动装配 

#### 完整地讲述了 Spring Boot 是如何从 Spring Framework 逐渐走向组件自动装配的。根据 Spring Framework发展的脉络，首先介绍 “Spring 模式注解装配”，随后讲解 “Spring @Enable 模块装配”，最后讨论 “Spring 条件装配“，掌握 Spring Framework 中所提供的原生能力，并且理解 Spring Boot 是如何...
2-1 走向自动装配 (00:38)

2-2 Spring Framework 手动装配 (05:52)

2-3 Spring Framework手动装配自定义模式注解 (12:10)

2-4 Spring Framework 手动装配 - @Enable 基于注解驱动方式 (07:05)

2-5 Spring Framework @Enable - 自定义 @Enable 基于接口驱动实现 (04:32)

2-6 @Enable 模块装配两种方式 (09:49)

2-7 Spring条件装配 (03:27)

2-8 基于配置方式实现自定义条件装配 (09:49)

2-9 基于编程方式实现条件装配 (12:33)

2-10 Spring Boot 自动装配 (07:07)

2-11 自定义自动装配 (08:45)

2-12 走向自动装配总结 (09:02)


### 第3章 理解 SpringApplication

#### 本节首先简介 SpringApplication 基本使用方法，并且根据其在 Spring Boot 应用所处的执行阶段，分别讨论 SpringApplication 准备阶段以及 SpringApplication 运行阶段。理解 Spring Boot Bean 配置源的作用、Web 应用类型推断对 Spring 应用上下文类型的作用，以及 Spring Boot 事件/事件机制。...
3-1 理解 SpringApplication (01:31)

3-2 基础技术和衍生技术 (04:38)

3-3 合并工程 (03:44)

3-4 SpringApplication 准备阶段 (07:35)

3-5 配置 Spring Boot Bean 源码部分 (09:02)

3-6 推断 Web 应用类型 (03:49)

3-7 推断引导类 (03:13)

3-8 加载应用上下文初始器 (10:30)

3-9 加载应用事件监听器 (09:56)

3-10 SpringApplication 运行阶段 (11:26)

3-11 SpringApplication 运行监听器事件监听器编程模型 (08:37)

3-12 SpringApplication 运行监听器 (05:03)

3-13 监听 Spring Boot 事件 (11:56)

3-14 创建 Spring 应用上下文 (08:15)

3-15 理解SpringApplication总结 (03:54)


### 第4章 Web MVC 核心

#### 通过 J2EE 前端控制器(Front Controller)模式的介绍，理解 Spring Web MVC 架构设计的思想，随后回顾Spring Web MVC 在传统 Servlet 容器中 XML 文件配置和 WAR 文件部署场景，以便重新认识 Spring Web MVC核心组件以及它们的交互流程，包括 Web MVC 注解驱动能力以及自动装配的能力，从而更好地理解...
4-1 Web MVC 核心 - 开场白 (01:04)

4-2 理解 Spring Web MVC 架构 (08:45)

4-3 Spring Framework 时代的一般认识 (19:29)

4-4 Spring Framework 时代的重新认识 (14:57)

4-5 核心组件流程说明 (08:45)

4-6 Web MVC 注解驱动 (11:35)

4-7 Web MVC 模块组件说明 (04:23)

4-8 WebMvcConfigurer 注入过程 (08:58)

4-9 Web MVC 常用注解（上） (14:02)

4-10 Web MVC 常用注解（下） (07:46)

4-11 Web MVC 自动装配 (08:24)

4-12 Web MVC 自动装配实现 (06:02)

4-13 Spring Boot 时代的简化 (03:28)

4-14 完全自动装配 (07:48)

4-15 条件装配 (02:26)

4-16 外部化配置 (01:07)

4-17 简Spring Boot 时代的简化 - 课纲部分 (07:54)

4-18 重构 Spring Web MVC 项目 (19:27)

4-19 -1 Web MVC 核心总结 (10:57)


### 第5章 Web MVC 视图应用

#### 本章最为核心的议题为“视图内容协商”，掌握内容协商策略的配置手段，理解它们与视图处理器的内在联系，从而深入理解Spring Web MVC 视图处理的核心原理，由此理解 Spring Boot 是如何自动装配视图处理器和内容协商管理器，以及怎么通过外部化配置控制它们的行为。同时介绍新一代服务端模板引擎 Thymeleaf，内容包...
5-1 Web MVC 视图应用 (02:47)

5-2 新一代服务端模板引擎Thymeleaf语法和核心要素 (05:25)

5-3 Thymeleaf 示例 (13:38)

5-4 ThymeleafViewResolver和多ViewResolver处理流程 (05:43)

5-5 ThymeleafViewResolver 示例 (11:09)

5-6 整合InternalResourceViewResolver示例 (14:48)

5-7 修复 Maven 多模块 JSP 定位问题 示例 (15:37)

5-8 视图内容协商 (09:33)

5-9 视图内容协商代码分析 (10:31)

5-10 ViewResolver 冲突说明部分 (07:40)

5-11 ViewResolver 内容协商原理 (24:03)

5-12 Web MVC 视图应用总结new (12:02)


### 第6章 Web MVC REST 应用

#### 首先讨论 REST 基本理论，并介绍 Spring Web MVC 对 REST 全面支持，包括 REST 控制定义、注解映射、请求、响应、AOP 拦截以及跨域控制（如：@CrossOrigin）等。随后重点讨论并结合源码分析 REST 内容协商的原理，理解内容协商管理.以及了解 Spring Web MVC REST 内容协商处理流程。...
6-1 Web MVC REST应用和REST介绍 (09:02)

6-2 Web MVC REST 支持 (07:21)

6-3 REST 内容协商 (06:19)

6-4 Web MVC REST 处理流程 (03:40)

6-5 Web MVC REST 处理流程源码分析 (21:05)

6-6 Web MVC REST 内容协商处理流程 (05:16)

6-7 Web MVC REST 内容协商处理流程源码分析 (17:00)

6-8 理解媒体类型 (07:10)

6-9 理解媒体类型源码分析 (11:04)

6-10 扩展 REST 内容协商-反序列化部分 (16:36)

6-11 扩展 REST 内容协商-序列化部分 (11:09)

6-12 自定义 Resolver 实现 (23:42)

6-13 自定义 Handler 实现 (16:45)

6-14 REST 内容协商CORS (11:15)

6-15 Web MVC REST应用总结 (06:30)


### 第7章 渐行渐远的 Servlet

#### 讨论的议题主要围绕着 Spring Boot 2.0 怎么让 Servlet 渐行渐远，首先需要了解的是 Servlet 的使用场景，以及各版本 Servlet 规范所覆盖的功能特性，其中包括 Spring Boot 所支持 Servlet 3.1+ 规范。通过 Servlet 生命周期的讨论，加深 Spring Web MVC DispatcherServlet 以及其他 Filter 组件...
7-1 渐行渐远的Servlet (03:02)

7-2 Servlet 核心 API (04:26)

7-3 Servlet 版本 (07:29)

7-4 Servlet 注册 (03:23)

7-5 理解 Servlet 组件生命周期 (16:16)

7-6 Servlet 异步支持 (12:03)

7-7 DeferredResult 增加线程信息 (02:48)

7-8 DeferredResult 设置 timeout 以及处理回调 (05:53)

7-9 DeferredResult 异步执行 (12:43)

7-10 Callable 异步执行 (04:18)

7-11 CompletionStage 异步执行 (06:42)

7-12 MVC 异步支持原理分析 (03:09)

7-13 异步 Servlet 实现 (16:54)

7-14 DefferedResult 实现原理 (03:47)

7-15 Spring Boot 嵌入式 Servlet 容器限制 (23:03)

7-16 Spring Boot 嵌入式 Servlet 容器限制 原理分析 (13:42)

7-17 Spring Boot 应用传统 Servlet 容器部署 (02:18)

7-18 扩展 SpringBootServletInitializer (04:46)

7-19 构建应用 (24:12)

7-20 渐行渐远的Servlet总结 (05:18)


### 第8章 从 Reactive 到 WebFlux

#### 帮助大家理解 Reactive 的本质。通过 Reactive 六种不同定义、编程模型、以及设计模式，理解它的使用场景，并延伸介绍 Reactive Streams 规范和它的实现框架 Reactor。在理论和实践的结合下，使我们清醒地认识到 Reactive 并非新鲜事物，而是一种新型的编程模型，它即不局限于其实现框架，也并非解决问题的“银弹...
8-1 从 Reactive 到 WebFlux (04:48)

8-2 关于 Reactive 的一些说法 (03:55)

8-3 理解阻塞的弊端和并行的复杂 (16:55)

8-4 Reactor 认为异步不一定能够救赎 (03:20)

8-5 理解 Callback Hell (08:44)

8-6 理解 Future 阻塞问题 (04:19)

8-7 理解 Future 链式问题 (10:25)

8-8 Reactive Streams JVM 认为异步系统和资源消费需要特殊处理 (03:02)

8-9 Reactive Programming 定义 (01:41)

8-10 Reactive Manifesto 定义 (02:05)

8-11 维基百科 (06:56)

8-12 Spring Framework 定义 (05:32)

8-13 ReactiveX 定义 (04:20)

8-14 Reactor 定义 (02:59)

8-15 andrestaltz 定义 (04:15)

8-16 Reactive Programming 特性：编程模型 (05:50)

8-17 Reactive Programming 特性：数据结构 (11:44)

8-18 Reactive Programming 特性：并发模型 (06:01)

8-19 Reactive Programming 使用场景 (23:03)

8-20 Reactive Streams 规范：定义 (02:11)

8-21 Reactive Streams 规范：API和事件 (05:20)

8-22 Reactive Streams 规范：背压 (06:51)

8-23 Reactor 框架运用 - 核心 API (10:44)

8-24 Reactor 框架运用实战（上） (11:50)

8-25 Reactor 框架运用实战（下） (12:26)

8-26 走向 Spring WebFlux (14:34)

8-27 从 Reactive 到 WebFlux - 课堂总结 (10:03)


### 第9章 WebFlux 核心

#### 继续讨论 WebFlux 的使用场景、编程模型以及核心接口。其中，使用场景部分将介绍 Spring WebFlux 的引入动机，对比 Spring MVC 的适用性边界、执行性能以及并发模型。讨论的焦点集中在编程模型，Spring WebFlux 提供函数式 Endpoint的支持，进而提升请求处理和映射的编程弹性。最后，通过对比 Spring MVC 核...
9-1 WebFlux 核心 (06:42)

9-2 官方引入WebFlux的动机分析 (09:12)

9-3 回顾Reactive (06:17)

9-4 编程模型：注解驱动 (03:11)

9-5 Java 函数编程基础 (08:39)

9-6 编程模型：函数式端点 - Functional Endpoints (19:31)

9-7 WebFlux 核心 - 并发模型 (12:32)

9-8 WebFlux 核心 - 核心组件 (10:35)

9-9 WebFlux 核心处理流程 - 函数式端点组件请求处理流程 (14:30)

9-10 WebFlux 核心处理流程 - 注解驱动组件请求处理流程 (10:57)

9-11 WebFlux 核心 - 使用场景 (22:15)

9-12 WebFlux 核心 - 课堂总结 (02:33)

9-13 WebFlux 核心 - 课程彩蛋 (14:18)


### 第10章 超越外部化配置

#### 首先讨论的议题为 Spring Environment 抽象，它作为 Spring Framework 以及 Spring Boot，甚至是Spring Cloud 的配置核心 API。结合SpringApplication 生命周期和 Spring Boot 事件分析，宏观地把握 Spring Boot 多种配置源的使用场景，理解它们之间优先级顺序逻辑，进而为扩展 Spring Boot 外部化配...
10-1 开场白部分 (01:52)

10-2 理解和应用“外部化配置” (09:49)

10-3 用于 XML Bean 定义的属性占位符 (15:32)

10-4 PropertySource 顺序说明 (05:17)

10-5 应用“外部化配置”- 用于 @Value 注入（上） (06:37)

10-6 应用“外部化配置”- 用于 @Value 注入（下） (05:49)

10-7 用于 Environment 读取 (12:33)

10-8 用于 Environment 读取 - 源码分析 (13:53)

10-9 用于 @ConfigurationProperties Bean 绑定（上） (17:00)

10-10 用于 @ConfigurationProperties Bean 绑定（下） (19:28)

10-11 用于 @ConditionalOnProperty 判断 (12:23)

10-12 扩展“外部化配置” (03:04)

10-13 理解 Spring Boot Environment 生命周期 (06:06)

10-14 定位外部化配置属性源 (28:10)

10-15 基于 SpringApplicationRunListener.environmentPrepared (17:19)

10-16 基于 ApplicationEnvironmentPreparedEvent (05:53)

10-17 基于 EnvironmentPostProcessor (09:04)

10-18 基于 ApplicationContextInitializer (04:20)

10-19 扩展外部化配置属性源其他扩展点 (06:40)

10-20 扩展“外部化配置”课堂总结 (03:19)


[下载地址](https://51xueit.vip "下载地址")
