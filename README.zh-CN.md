<h1 align="center"> 在线订货系统 </h1>

<div align="center">

Spring Cloud Demo （以微服务理念设计）

[![GitHub issues](https://img.shields.io/github/issues/cookob/online-ordering-platform)](https://github.com/cookob/online-ordering-platform/issues) [![GitHub forks](https://img.shields.io/github/forks/cookob/online-ordering-platform)](https://github.com/cookob/online-ordering-platform/network) [![GitHub stars](https://img.shields.io/github/stars/cookob/online-ordering-platform)](https://github.com/cookob/online-ordering-platform/stargazers) [![GitHub license](https://img.shields.io/github/license/cookob/online-ordering-platform)](https://github.com/cookob/online-ordering-platform/blob/master/LICENSE)

</div>

## 以微服务理念设计 ##

---

一、项目功能

```
                      |--用户登录
                      |--用户退出
            |--客户端--
            |         |--商品订购
            |         |--我的订单
在线订货平台--
            |
            |              |--管理员登录
            |              |--管理员退出
            |              |--添加用户
            |              |--查询用户
            |              |--删除用户
            |--后台管理系统--
                           |--添加商品
                           |--查询商品
                           |--修改商品
                           |--删除商品
                           |--订单处理
```

二、系统架构 <br>

![1](https://github.com/cookob/online-ordering-platform/blob/master/model.zh-CN.png)

-----

关于登录

| 用户名 | 密码 | 角色 |
| :---: | :---: | :---: |
| admin1 | 123456 | 管理员 |
| zhangsan | 123456 | 用户 |

## 感谢

感谢   [orderingsystem](https://github.com/southwind9801/orderingsystem) 