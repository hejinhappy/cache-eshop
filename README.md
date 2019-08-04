# cache-eshop

本项目是《亿级流量电商详情页系统实战（第二版）：缓存架构+高可用服务架构+微服务架构》 练习代码

## 第一版与第二版的区别
- 第 001 ~ 123 章是第一版，主要对缓存架构、高可用中用到的技术做了深入讲解
- 从 123 章起是第二版，主要是实战，重点是商品详情页架构实战，对于技术在第一版中已经讲解过

所以目前看来，第一版是基础，第二版是实战

- 对应笔记文档请参阅：https://zq99299.github.io/note-book/cache-pdp/
- 笔记文档仓库：https://github.com/zq99299/note-book

## 练习代码目录大致讲解
由于练习代码的微服务可能会比较多，而且为了集中在一起，就都放在一个仓库中了。

根目录/build.gradle : 把各个项目用到的公共配置提取到这里，只做公共配置管理，每个子项目在概念上是独立的
