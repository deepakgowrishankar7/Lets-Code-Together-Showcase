<div align="center">

# 🚀 Let's Code Together

### *The All-in-One Interactive Coding, Learning & Mobile Ecosystem*

<br/>

[![Release v1.0.0](https://img.shields.io/badge/Release-v1.0.0%20Production-06b6d4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases/tag/v1.0.0)
[![Android APK](https://img.shields.io/badge/Android%20APK-Download%20(67MB)-10b981?style=for-the-badge&logo=android&logoColor=white)](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases/download/v1.0.0/LetsCodeTogether-v1.0.0.apk)
[![Web Platform](https://img.shields.io/badge/Web%20Portal-Live%20Demo-6366f1?style=for-the-badge&logo=render&logoColor=white)](https://lets-code-together.onrender.com)
[![React Native](https://img.shields.io/badge/Mobile-React%20Native%20%2F%20Expo-2496ED?style=for-the-badge&logo=react&logoColor=white)](https://reactnative.dev)
[![Spring Boot](https://img.shields.io/badge/Backend-Spring%20Boot%203.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)

<br/>

**Learn · Code · Compile · Visualize · Communicate — On Web & Android**

*A unified, full-stack educational and development platform combining the interactive learning of LeetCode, the multi-language execution of an online IDE, the execution tracing of a code visualizer, and an ATS resume studio — accessible on desktop and native Android.*

<br/>

### 📲 [**Download Android APK v1.0.0 (Direct CDN)**](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases/download/v1.0.0/LetsCodeTogether-v1.0.0.apk) &nbsp;•&nbsp; 🌐 [**Try Live Web Demo**](https://lets-code-together.onrender.com) &nbsp;•&nbsp; 📄 [**Open Showcase Webpage**](https://deepakgowrishankar7.github.io/Lets-Code-Together-Showcase/)

<br/>

---

</div>

## 📱 Mobile App Showcase (Android v1.0.0)

The native mobile app is built with **React Native (Expo SDK 52)** and connects seamlessly to the cloud workspace. It provides a full-featured handheld development environment without compromises.

<table>
  <tr>
    <td width="25%" align="center">
      <img src="./assets/screenshots/app_home_courses.png" width="100%" alt="Courses Hub"/>
      <br/><b>📚 Course Hub & Topics</b>
    </td>
    <td width="25%" align="center">
      <img src="./assets/screenshots/app_compiler_ide.png" width="100%" alt="In-App Compiler"/>
      <br/><b>⚡ 8-Language IDE & Compiler</b>
    </td>
    <td width="25%" align="center">
      <img src="./assets/screenshots/app_course_study.png" width="100%" alt="Study Hub"/>
      <br/><b>🎯 Distraction-Free Study</b>
    </td>
    <td width="25%" align="center">
      <img src="./assets/screenshots/app_resume_builder.png" width="100%" alt="ATS Resume Builder"/>
      <br/><b>📄 ATS Resume Builder</b>
    </td>
  </tr>
</table>

---

## ⚡ Core Features & Capabilities

### 💻 1. Multi-Language IDE & Mobile Compiler
- **8 Supported Languages:** Python 3, Java 21, C++, C, JavaScript (Node.js), Go, Ruby, and PHP.
- **Embedded Execution Engine:** Write code on your smartphone or browser and get immediate stdout, stderr, execution time, and memory metrics.
- **In-Console AI Auto-Debugger:** When syntax or logic bugs trigger exceptions, the debugger offers intelligent diagnostics directly in the output console and applies fixes with word-by-word animated compiler injection.

### 🔬 2. Real-Time Algorithm Visualizer
- **Step-by-Step Code Tracing:** Watch variables update in real time as algorithms execute.
- **Call Stack & Memory Inspection:** Visualize recursion trees, loop state transitions, and memory pointers to understand complex DSA concepts deeply.

### 🎓 3. Interactive Learning & Interview Hub
- **Core Curriculum:** Java, Python, SQL, and Data Structures & Algorithms.
- **Curated Interview Bank:** Topic-specific questions and technical answers for interview revision.
- **Full-Screen Focus Mode:** Distraction-free mobile reading mode with text-to-speech audio companion for listening on the go.
- **Knowledge Quizzes:** Scored assessments with visual analytics to track topic retention.

### 📄 4. ATS Interactive Resume Builder
- **Job-Ready Formatting:** Input education, skills, projects, and certifications into high-converting, ATS-compliant formats.
- **Dynamic Profile Derivation:** Automatically links with user profile data for immediate preview and export.

### 💬 5. Real-Time Collaboration & Leaderboards
- **Public Chat & Direct Messages:** Exchange thoughts, ask questions, and collaborate with peers in real time.
- **Learning Streak & Leaderboards:** Stay accountable with daily activity tracking, challenge completions, and peer rankings.

---

## 📥 How to Install the Android App

1. **Download the APK:**  
   Click the direct download link: [**`LetsCodeTogether-v1.0.0.apk`**](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases/download/v1.0.0/LetsCodeTogether-v1.0.0.apk) (Size: ~67 MB).
2. **Enable Unknown Apps (if prompted):**  
   Tap the downloaded `.apk` file. If Android prompts you with a security alert, select **Settings** and toggle **"Allow from this source"**.
3. **Install & Launch:**  
   Tap **Install**. Once finished, launch **Let's Code Together** and start coding immediately!

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                    User Client Applications                     │
├────────────────────────────────┬────────────────────────────────┤
│     Android Native Mobile      │     Responsive Web Portal      │
│  (React Native / Expo SDK 52)  │    (HTML5 / Tailwind / PWA)    │
└────────────────┬───────────────┴────────────────┬───────────────┘
                 │                                │
                 ▼                                ▼
┌─────────────────────────────────────────────────────────────────┐
│               REST API & WebSocket Stomp Broker                 │
│         (Spring Boot 3.5 • Java 25 • Spring Security 6)        │
├─────────────────────────────────────────────────────────────────┤
│  • JWT Authentication Filter    • Multi-Language Code Runner    │
│  • Course & Topic Engine        • Real-Time Chat & Direct Msg   │
│  • Quiz Assessment Controller   • ATS Resume Service            │
└────────────────┬────────────────────────────────┬───────────────┘
                 │                                │
                 ▼                                ▼
┌─────────────────────────────────┐  ┌────────────────────────────┐
│      Relational Persistence     │  │       Execution Pool       │
│     (MySQL 8.0 / Hibernate 6)   │  │   (Isolated Code Sandbox)  │
└─────────────────────────────────┘  └────────────────────────────┘
```

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| **Mobile Client** | React Native, Expo SDK 52, Lucide Icons, React Navigation |
| **Web Frontend** | HTML5, Tailwind CSS, Monaco Code Editor, Chart.js, PWA |
| **Backend Core** | Spring Boot 3.5, Java 25, Spring Data JPA, Spring Security 6, JJWT |
| **Execution Sandboxes** | Python 3, OpenJDK 21, GCC (C/C++), Node.js, Go, Ruby, PHP |
| **Database** | MySQL 8.0, Hibernate 6 ORM, Flyway Migrations |
| **Deployment & CI/CD** | Docker, Render Cloud, GitHub Actions (Automated Gradle Builds) |

---

## 🔗 Project Links

- 📲 **Official Android APK:** [Download v1.0.0](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases/download/v1.0.0/LetsCodeTogether-v1.0.0.apk)
- 🌐 **Live Web App:** [https://lets-code-together.onrender.com](https://lets-code-together.onrender.com)
- 💻 **Showcase Landing Page:** [https://deepakgowrishankar7.github.io/Lets-Code-Together-Showcase/](https://deepakgowrishankar7.github.io/Lets-Code-Together-Showcase/)
- 📦 **GitHub Releases:** [Showcase Releases v1.0.0](https://github.com/deepakgowrishankar7/Lets-Code-Together-Showcase/releases)

---

<div align="center">

Developed with dedication by **[Deepak Gowrishankar](https://github.com/deepakgowrishankar7)**  
*Empowering every coder to learn, build, and grow together.*

</div>
