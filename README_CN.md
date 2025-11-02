# MyNet 校园社区全栈平台 | MyNet Campus Forum Web

> 🌎 [English Version](README_EN.md)  
>  
> 基于 **Spring Boot 3、React、MySQL、Redis、Docker** 构建的校园社区平台，
> 支持发帖、评论、点赞、通知与推荐功能。

![cover](docs/cover.png)

## 项目概述

这是一个模拟校园社区的全栈项目，包含后端 RESTful API、前端界面、消息队列与缓存。


---

##  技术栈 | Tech Stack

| 层级 | 使用技术 |
|------|-----------|
| **前端 Frontend** | React · Ant Design · Axios · Vite |
| **后端 Backend** | Spring Boot 3 · Spring Data JPA · Kafka · Redis |
| **数据库 Database** | MySQL |
| **部署 Deployment** | Docker · Docker Compose |
| **构建工具 Build Tools** | Maven · npm |
| **版本控制 Version Control** | Git · GitHub |


---

## 核心功能 | Key Features

- **📝 发帖与评论系统** — 支持发帖、浏览、点赞与评论  
- **💬 通知中心** — 基于 Kafka 实现异步通知（评论、点赞）  
- **⚡ 高性能架构** — Redis 缓存与消息队列解耦提升并发性能  
- **🎨 响应式界面** — 使用 React + Ant Design 实现流畅用户体验  
- **🐳 一键部署** — Docker Compose 启动完整全栈环境  

---

## 系统模块 | System Modules

| 模块 | 功能说明 |
|------|-----------|
| **用户模块 User Service** | 注册、登录、JWT 鉴权 |
| **帖子模块 Post Service** | 发帖、点赞、热度排序 |
| **评论模块 Comment Service** | 评论展示与分页加载 |
| **通知模块 Notification Service** | 消费 Kafka 事件生成用户通知 |
| **推荐模块 Recommendation Service** | 基于活跃度与热度的内容推荐 |

---

## 页面预览 | Screenshots

| 首页 | 帖子详情 | 通知中心 |
|------|-----------|-----------|
| ![](docs/home.png) | ![](docs/post.png) | ![](docs/notify.png) |

---

## 快速开始 | Getting Started

### 环境要求
- Java 17 或更高版本  
- Node.js 18 或更高版本  
- Docker 与 Docker Compose  

### 克隆仓库
```bash
git clone https://github.com/serena-0/mynet-campus-forum.git
cd mynet-campus-forum
