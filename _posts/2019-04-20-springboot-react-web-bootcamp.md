---
layout: post
title:  "Web全栈开发实战课程"
author: 
categories: [ Bootcamp, Full Stack ]
image: assets/images/4.jpg
featured: true
---



## **Web全栈实战课程**
全栈实战课程会从web应用最基本的理论开始入门，导师们会带着学员从复习基本的Java, JavaScript, HTML, CSS语法开始，循序渐进地深入了解目前主流开发框架和技术。

课程选用的框架是目前web应用开发最流行的SpringBoot作为后端框架，以及最流行的React作为前端框架。通过本次学习，学员们可以对业务逻辑分析和面对对象设计、数据库关系设计、后端RestAPI设计、前端UI设计、测试等项目实际开发流程有很好的了解，为将来的实习或者工作打下很好的基础。

本次课程的目的是带领学员深入体验真实的web应用实战开发，为学员在求职过程中的简历加分，得到更好的实习和工作机会，也为将来的实习和工作打下更坚实的基础。

授课语言：英语、中文
地点：AC
时间：周六/周日

## **SpringBoot介绍**

Spring Boot 是目前最流行的web应用后端框架，由 Pivotal 团队开发的，其作用是用来简化新 Spring 应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置，简单理解就是springboot并不是什么新型的框架，而是整合了spring，springmvc等框架，默认了很多配置，从而减少了开发者的开发时间。

Spring Boot 简化了基于 Spring 的应用开发，通过少量的代码就能创建一个独立的、产品级别的 Spring 应用。 Spring Boot 为 Spring 平台及第三方库提供开箱即用的设置。

**SpringBoot优点：**

 1. 使用 Spring 项目引导页面可以在几秒构建一个项目
 2. 支持关系数据库和非关系数据库
 3. 支持运行期内嵌容器，如 Tomcat、Jetty
 4. 强大的开发包，支持热启动
 5. 自动管理依赖
 6. 自带应用监控
 7. 支持各种 IDE，如Eclipse, IntelliJ IDEA, NetBeans

![](https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=3180699167,1298829483&fm=173&app=25&f=JPEG?w=530&h=300&s=29D28C5609686C1390CC334F03006074)

**SpringBoot能带来哪些便捷？**

用SpringBoot 单元测试更简单：

我们只需要在项目中引入spring-boot-start-test依赖包，加上注解，就可以对数据库、Web 等各种情况进行测试，十分方便。

用SpringBoot 配置变得更简单：

springboot最显著的有点就是让本来繁琐的配置，变的十分简单，使得程序开发者有更多的时间去写真正的业务代码。

![](https://ss1.baidu.com/6ONXsjip0QIZ8tyhnq/it/u=2622952426,3358038760&fm=173&app=25&f=JPEG?w=579&h=300&s=AEE1E05A839D41CA4C75124E03004077)

用SpringBoot 部署变得更简单：

pring Boot 内嵌Tomcat容器。使用 Spring Boot 开发项目，不需要关心容器的环境问题，专心写业务代码即可。（ 用Jenkins 部署 Spring Boot 项目非会使项目构建更简单，感兴趣的可以去看看）

## **React介绍**

![Image result for REACT](https://matwrites.com/wp-content/uploads/2019/01/1_HSisLuifMO6KbLfPOKtLow.jpeg)
React是目前最流行的前端JavaScript框架，用于构建“可预期的”和“声明式的”Web用户界面，它已经使Facebook更快地开发Web应用。

**一、特点：**

1、简单简单的表述任意时间点你的应用应该是什么样子的，React将会自动的管理UI界面更新当数据发生变化的时候。

2、声明式在数据发生变化的时候，React从概念上讲与点击了F5一样，实际上它仅仅是更新了变化的一部分而已。React是关于构造可重用组件的，实际上，使用React你做的仅仅是构建组建。通过封装，使得组件代码复用、测试以及关注点分离更加容易。

另外还有以下注意点：

 - React不是一个MVC框架
 - React不使用模板
 - 响应式更新非常简单

**二、主要原理**

传统的web应用，操作DOM一般是直接更新操作的，但是我们知道DOM更新通常是比较昂贵的。而React为了尽可能减少对DOM的操作，提供了一种不同的而又强大的方式来更新DOM，代替直接的DOM操作。就是Virtual DOM,一个轻量级的虚拟的DOM，就是React抽象出来的一个对象，描述dom应该什么样子的，应该如何呈现。通过这个Virtual DOM去更新真实的DOM，由这个Virtual DOM管理真实DOM的更新。

为什么通过这多一层的Virtual DOM操作就能更快呢？ 这是因为React有个diff算法，更新Virtual DOM并不保证马上影响真实的DOM，React会等到事件循环结束，然后利用这个diff算法，通过当前新的dom表述与之前的作比较，计算出最小的步骤更新真实的DOM。

**Components 组件**

在DOM树上的节点被称为元素，在这里则不同，Virtual DOM上称为commponent。Virtual DOM的节点就是一个完整抽象的组件，它是由commponents组成。

注：component 的使用在 React 里极为重要, 因为 components 的存在让计算 DOM diff 更高效。

**State 和 Render**

React是如何呈现真实的DOM，如何渲染组件，什么时候渲染，怎么同步更新的，这就需要简单了解下State和Render了。state属性包含定义组件所需要的一些数据，当数据发生变化时，将会调用Render重现渲染，这里只能通过提供的setState方法更新数据
