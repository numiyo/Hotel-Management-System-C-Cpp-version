# 酒店管理系统项目

## 项目概述
（tips：本项目主要是个人练手项目QAQ）
-该系统主要用于本地管理酒店的用户信息和房间信息，实现用户的增删改查以及酒店房间的管理等功能。

## 技术选型
### 开发语言
本项目使用 C/C++ 进行开发，语言版本要求为 C++11 及以上。

### 主要运用特性
指针, 结构体, STL等。

### 版本控制工具
使用 git 作为项目的版本控制工具，代码托管在 GitHub 平台上。

### 数据库
本系统使用本地的 txt 文本文件作为数据库，用于存储用户注册信息、房间信息以及请求信息。

### 编辑器
在开发过程中，主要使用 CLion 和 SublimeText 作为代码编辑器。

## 实现功能
### 用户管理
- **用户角色**：用户角色分为管理员和顾客，顾客又细分为会员账号和普通账号。
  - 管理员账号预设为admin，密码与账号相同。
  - 顾客可以进行注册、登录、修改信息等操作。
- **用户增删改查**：
  - 管理员可以对用户信息进行增加、删除和修改操作。
  - 所有用户都可以查询自己的信息。

### 房间管理
- **房间增删改查**：
  - 管理员账号拥有对酒店房间进行删除和增加的权限。
  - 顾客可以查询房间的类型、价格、预定时间等信息。
- **房间预订**：
  - 顾客可以订房间，系统会自动扣减相应余额并修改对应房间的状态。

### 数据持久化
程序关闭之后，用户、房间等的信息会被保存到本地的 txt 文件中，下次运行程序时可以被重新加载，确保数据不会丢失。

## 项目结构
- **源代码**：包含实现旅店管理系统的所有 C++ 代码文件。
- **README.md**：本项目介绍文档，详细说明了项目的功能、技术选型以及使用方法等。

## 特别鸣谢
- **技术支持**：CSDN, DeepSeek-R1, Kimi提供的报错解决方案
- **项目重构**：DeepSeek-R1, 豆包提供的三次项目重构支持:(

## 如何使用
克隆本项目到本地：
   ```bash
   git clone <仓库地址>
