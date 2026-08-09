<div align="center">

<img src="https://img.shields.io/badge/🚀-Let's%20Code%20Together-0f172a?style=for-the-badge&labelColor=2563eb&color=0f172a" alt="Let's Code Together" width="600"/>

<br/><br/>

# 🚀 Let's Code Together

### _An All-in-One Interactive Coding, Learning & Community Platform_

<br/>

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Render](https://img.shields.io/badge/Live%20on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com/)

<br/>

**Learn · Code · Compile · Visualize · Communicate — All in One Place**

_A premium, full-stack web platform where students can learn programming through structured courses, compile code in 8+ languages, visualize execution step-by-step, take quizzes, and chat with peers — all wrapped in a glassmorphic, modern UI._

<br/>

### 🌐 [**Try the Live Demo →**](https://lets-code-together.onrender.com)

<br/>

---

</div>

## 🎯 What is Let's Code Together?

**Let's Code Together** is a **full-stack educational platform** built from scratch — designed to be a one-stop hub for students learning to code. It combines the best features of platforms like LeetCode, Repl.it, and Discord into a single, beautifully designed application.

> 💡 This is a **solo-developed** project showcasing full-stack engineering, system design, and premium UI/UX skills.

---

## ✨ Platform Features

<table>
<tr>
<td width="50%" valign="top">

### 🎓 Learning Hub
- **4 Active Courses** — Java, Python, SQL, DSA
- **12+ Upcoming Courses** — C++, React, AWS, Node.js, Web Dev, DBMS, Cybersecurity, Data Analytics & more
- **Structured Curriculum** — Topic-by-topic learning with downloadable PDF resources
- **Animated Video Lessons** — Visual concept explanations for complex topics
- **Interactive Quizzes** — Scored assessments with performance analytics

</td>
<td width="50%" valign="top">

### 💻 Online IDE & Compiler
- **8 Languages** — Python 3, Java 21, C++ (GCC), C (GCC), JavaScript (Node.js), Go, Ruby, PHP
- **Code Execution Visualizer** — Step-by-step line-by-line execution tracing
- **Live Code Rooms** — Real-time collaborative coding sessions with shareable links
- **Keyboard Shortcuts** — `Ctrl+Enter` to compile & run
- **Execution Stats** — Runtime, memory usage, and status tracking

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 Communication Hub
- **Public Chat** — Community-wide discussion board
- **Private Messaging** — Direct 1-on-1 messaging between users
- **Admin Announcements** — Platform-wide broadcast messages
- **Real-Time User Search** — Instant multi-field search (name/username)
- **Smart Date Headers** — Messages grouped by Today, Yesterday, and exact dates

</td>
<td width="50%" valign="top">

### 🛡️ Platform & Security
- **JWT Authentication** — Secure token-based login system
- **Admin Dashboard** — Full user management, analytics & notification control
- **Quiz Score Tracking** — Visual performance charts with Chart.js
- **Email Integration** — Password reset via SMTP email
- **PWA Support** — Installable as a native-like mobile/desktop app
- **Dark / Light Theme** — System-wide one-click theme toggle

</td>
</tr>
</table>

---

## 🏗️ Tech Stack

<div align="center">

### ⚙️ Backend

| Technology | Purpose |
|:---|:---|
| **Spring Boot 3.5** | Core REST API framework |
| **Spring Security + JWT** | Authentication & authorization |
| **Spring Data JPA + Hibernate** | ORM & database layer |
| **Spring Mail** | Email services (password reset) |
| **MySQL 8.0** | Relational database |
| **Lombok** | Boilerplate reduction |
| **SpringDoc OpenAPI** | Auto-generated API docs (Swagger UI) |

### 🎨 Frontend

| Technology | Purpose |
|:---|:---|
| **Vanilla HTML / CSS / JavaScript** | Zero-framework, high-performance UI |
| **Custom Glassmorphic Design System** | Premium UI with `backdrop-filter: blur` effects |
| **Chart.js** | Interactive quiz score analytics |
| **Google Fonts (Inter)** | Modern, clean typography |
| **Service Worker + Manifest** | PWA — offline support & app installation |

### 🚀 DevOps & Deployment

| Technology | Purpose |
|:---|:---|
| **Docker** | Multi-stage build with embedded compilers (Java, Python, C/C++, Node.js) |
| **Render** | Cloud hosting with automatic GitHub deploy |
| **Maven** | Build automation & dependency management |

</div>

---

## 🏛️ Architecture Overview

```
┌──────────────────────────────────────────────────────────────────┐
│                        CLIENT (Browser)                         │
│  ┌─────────┐ ┌──────────┐ ┌──────────┐ ┌───────┐ ┌──────────┐  │
│  │  Login  │ │  Courses │ │ Compiler │ │  Chat │ │  Admin   │  │
│  │  Page   │ │  & DSA   │ │  & IDE   │ │  Hub  │ │  Panel   │  │
│  └────┬────┘ └────┬─────┘ └────┬─────┘ └───┬───┘ └────┬─────┘  │
│       │           │            │            │          │         │
│       └───────────┴────────────┴────────────┴──────────┘         │
│                          REST API + JWT                          │
└──────────────────────────────┬───────────────────────────────────┘
                               │
┌──────────────────────────────▼───────────────────────────────────┐
│                    SPRING BOOT 3.5 SERVER                        │
│  ┌──────────────┐ ┌────────────────┐ ┌────────────────────────┐  │
│  │    Auth       │ │   Compile      │ │   Message / Quiz       │  │
│  │  Controller   │ │  Controller    │ │   Controllers          │  │
│  │  (JWT + Mail) │ │  (8 Languages) │ │   (Public + Private)   │  │
│  └──────┬───────┘ └───────┬────────┘ └───────────┬────────────┘  │
│         │                 │                      │               │
│  ┌──────▼─────────────────▼──────────────────────▼────────────┐  │
│  │              Service Layer + JPA Repositories              │  │
│  └────────────────────────┬───────────────────────────────────┘  │
└───────────────────────────┬──────────────────────────────────────┘
                            │
                   ┌────────▼────────┐
                   │   MySQL 8.0     │
                   │   Database      │
                   └─────────────────┘
```

---

## 🎨 Design Philosophy

<table>
<tr>
<td align="center" width="33%">

### 🪟
**Glassmorphism**
<br/>Frosted glass cards with backdrop blur for depth and elegance

</td>
<td align="center" width="33%">

### 🎯
**Royal Blue Palette**
<br/>Consistent `#2563eb` accent across all interactive elements

</td>
<td align="center" width="33%">

### ✨
**Micro-Animations**
<br/>Smooth transitions, hover effects & reveal animations

</td>
</tr>
<tr>
<td align="center" width="33%">

### 📱
**Fully Responsive**
<br/>Adaptive layout for desktop, tablet & mobile

</td>
<td align="center" width="33%">

### 🌗
**Dual Theme**
<br/>Light & Dark modes with seamless one-click toggle

</td>
<td align="center" width="33%">

### ⚡
**Zero Framework**
<br/>Vanilla JS — no overhead, instant load times

</td>
</tr>
</table>

---

## 📊 Project Stats

| Metric | Value |
|:---|:---|
| **Total Frontend CSS** | ~9,500+ lines |
| **Total Frontend JS** | ~5,500+ lines |
| **Backend Controllers** | 10 REST controllers |
| **Database Entities** | 9 JPA entities |
| **Supported Languages** | 8 programming languages |
| **Active Courses** | 4 (Java, Python, SQL, DSA) |
| **Upcoming Courses** | 12+ |

---

## 🧑‍💻 Key Technical Highlights

- **🔐 Full Authentication System** — Register, Login, JWT tokens, Password reset via email
- **⚡ Multi-Language Code Execution** — Docker container with embedded compilers (Java, Python, C/C++, Node.js)
- **📊 Real-Time Analytics** — Chart.js-powered quiz score dashboards
- **🔍 Code Execution Visualizer** — Integration with Python Tutor for step-by-step code tracing
- **💬 Real-Time Messaging** — Public chat, private DMs, and admin broadcasts
- **📱 Progressive Web App** — Service worker + manifest for installable app experience
- **🎨 9,500+ Lines of Custom CSS** — Hand-crafted glassmorphic design system with dual-theme support
- **🐳 Production Docker Build** — Multi-stage build with all compiler runtimes included

---

## 👨‍💻 About the Developer

<div align="center">

**Deepak Gowrishankar**

_Full-Stack Developer_

[![GitHub](https://img.shields.io/badge/GitHub-deepakgowrishankar7-181717?style=for-the-badge&logo=github)](https://github.com/deepakgowrishankar7)

<br/>

> _"Built from scratch as a passion project to create the ultimate coding education platform."_

---

### 🌐 [**Try the Live Demo →**](https://lets-code-together.onrender.com)

<br/>

⭐ **If you like this project, please give it a star!**

</div>
