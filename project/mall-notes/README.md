# mall 电商系统学习笔记

> mall 项目是一套基于 SpringBoot + Vue + uni-app 的电商系统，GitHub 60K+ Star。
> 项目地址：https://github.com/macrozheng/mall

## 项目简介

mall 项目包括：
- **前台商城系统**：商品浏览、搜索、购物车、订单、支付
- **后台管理系统**：商品管理、订单管理、会员管理、权限管理、营销管理

## 技术栈

| 技术 | 用途 |
|------|------|
| Spring Boot | 后端框架 |
| MyBatis | ORM 框架 |
| Spring Security | 权限控制 |
| Redis | 缓存 |
| RabbitMQ | 消息队列 |
| Elasticsearch | 搜索引擎 |
| MySQL | 数据库 |
| Docker | 容器化部署 |

## 学习路线

| 阶段 | 内容 | 状态 |
|------|------|------|
| 环境搭建 | Docker 部署 MySQL/Redis/RabbitMQ/Elasticsearch | ⬜ |
| 用户模块 | 注册、登录、JWT 鉴权、权限控制 | ⬜ |
| 商品模块 | 分类、品牌、SKU、库存管理 | ⬜ |
| 订单模块 | 购物车、下单、订单状态机、库存扣减 | ⬜ |
| 缓存实战 | Redis 商品缓存、分布式锁 | ⬜ |
| 消息队列 | 订单超时取消、库存回滚 | ⬜ |

## 笔记列表

- [01-环境搭建](01-环境搭建.md)
- [02-用户模块](02-用户模块.md)
- [03-商品模块](03-商品模块.md)
- [04-订单模块](04-订单模块.md)
- [05-Redis 缓存实战](05-Redis缓存实战.md)
- [06-RabbitMQ 消息队列](06-RabbitMQ消息队列.md)

## 参考资源

- [mall 官方文档](https://www.macrozheng.com)
- [mall 学习教程](https://macrozheng.github.io/mall-learning/)
