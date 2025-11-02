# MyNet Campus Forum Web | Full-Stack Campus Community Platform

> 🇨🇳 [中文说明 / Chinese README](README_CN.md)  
>  
> A full-stack campus community platform built with **Spring Boot 3, React, MySQL, Redis, and Docker**,  
> supporting post publishing, commenting, liking, notifications, and content recommendation with high-performance backend architecture.

![cover](docs/cover.png)  


---

## Overview

**MyNet Campus Forum Web** is a modern full-stack web application that simulates a real campus community.  
It demonstrates high-performance backend design and smooth frontend interaction, integrating **Kafka**, **Redis**, and asynchronous event-driven communication with a **Dockerized** deployment.

---

##  Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React · Ant Design · Axios · Vite |
| **Backend** | Spring Boot 3 · Spring Data JPA · Kafka · Redis |
| **Database** | MySQL |
| **Deployment** | Docker · Docker Compose |
| **Build Tools** | Maven · npm |
| **Version Control** | Git · GitHub |

---

## Key Features

- **📝 Post & Comment System** — Create, view, and discuss posts within the campus community  
- **💬 Notification Center** — Real-time notification for new comments and likes via Kafka event-driven architecture  
- **⚡ High Performance** — Redis caching and Kafka decoupling reduce database load under high traffic  
- **🎨 Modern UI** — Responsive design built with React + Ant Design  
- **🐳 One-Click Deployment** — Docker Compose to spin up the full stack locally

---

## System Modules

| Module | Description |
|---------|-------------|
| **User Service** | Handles registration, login, and JWT authentication |
| **Post Service** | CRUD operations, likes, and ranking |
| **Comment Service** | Comment system with pagination |
| **Notification Service** | Consumes Kafka events and generates user notifications |
| **Recommendation Service** | Post ranking based on activity and popularity |

---

## Screenshots

| Home Feed | Post Detail | Notification Center |
|------------|--------------|--------------------|
| ![](docs/home.png) | ![](docs/post.png) | ![](docs/notify.png) |

---

## Getting Started

### Prerequisites
- Java 17+
- Node.js 18+
- Docker & Docker Compose

### Clone Repository
```bash
git clone https://github.com/serena-0/mynet-campus-forum.git
cd mynet-campus-forum



