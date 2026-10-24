# Software Developer | Systems Analyst | Cloud & DevOps Engineer

![Profile Views](https://komarev.com/ghpvc/?username=CalebLouwskitter&color=blue&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/CalebLouwskitter)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:CalebLouwskitter@Gmail.com)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel-portfolio-eta-eight.vercel.app/)

**Bridging software engineering with cloud, mobile, and immersive technologies.**

Experienced in Full-Stack Development • API Engineering • Mobile Platforms • Virtual & Mixed Reality • Infrastructure as Code

---

## 🧠 About Me

I am a software developer with a background in computer science and information systems, focused on building robust, reliable financial and operational systems. My recent engineering work spans legacy-to-modern systems integration and idempotent financial workflows (bridging GnuCOBOL and PHP to TypeScript and SQL Server), secure payment gateway architecture with hands-on threat modelling and attack mitigation, and offline-resilient mobile applications with custom geospatial toolkits. I value clear architectural boundaries, strict security controls, and end-to-end automated testing across web, mobile, and backend platforms.

---

## 🚀 Featured Projects

### 💼 [bureau-bridge](https://github.com/CalebLouwskitter/bureau-bridge)
**Financial systems lab bridging legacy PHP and a real GnuCOBOL ledger to TypeScript, SQL Server, and Expo with idempotent recovery.**

- **Idempotent batch recovery across async boundaries:** Recovers lost batch results without posting twice using a core processed-reference journal, payload conflict checks, and core inquiry.
- **Durable delivery & authoritative ledger:** Coordinates SQL Server outbox transactions and leased worker retries while keeping GnuCOBOL as the financial authority for balances.
- **Deterministic EFT payouts & reconciliation:** Generates hash-checked fixed-width payout files under a lock, checks the demo bank before resending, and reconciles settlement accounts against bank returns.

`TypeScript` · `GnuCOBOL` · `PHP` · `Microsoft SQL Server` · `MariaDB` · `Expo` · `Docker` · `Python`

---

### 🔒 [INSYPOEPaymentGateway](https://github.com/CalebLouwskitter/INSYPOEPaymentGateway) *(Team project, lead developer)*
**International payments portal featuring customer and staff portals backed by an attacker-style security review and exploit test suite.**

- **Hardened against 12 scripted attack vectors:** Conducted post-submission security review testing NoSQL injection, IP-spoofed rate limiting, CSRF, IDOR, and privilege escalation, fixing 16 vulnerabilities with automated test gates.
- **Role-based separation & atomic reviews:** Implemented distinct customer and employee JWT authentication schemes with algorithm pinning, token denylists, and race-safe atomic payment approval workflows.
- **DevSecOps quality gates:** Integrated automated Jest attack-scenario suites, npm audit security gates, Gitleaks history scanning, and CodeQL static analysis in CI.

`React` · `Node.js` · `Express` · `MongoDB` · `Docker` · `GitHub Actions` · `Jest`

---

### 🎯 [KovaakstoAgent](https://github.com/CalebLouwskitter/KovaakstoAgent)
**Local Windows desktop application and training dashboard turning KovaaK's aim-trainer exports into longitudinal progress tracking and AI coaching.**

- **Automated ingestion & export parsing:** Detects Steam installation paths via the Windows registry, watches filesystem changes, and normalises multi-section CSV exports into structured session data.
- **Context-preserving local memory store:** Retains normalized historical sessions, player goals, constraints, and notes in SQLite, assembling deterministic context packets for multiple LLM providers (OpenAI, OpenRouter, Gemini).
- **Zero-admin desktop distribution:** Packaged with Inno Setup and PyInstaller featuring a background system tray watcher, WebView2 frontend, and loopback request origin validation.

`Python` · `SQLite` · `pywebview` · `Inno Setup` · `PyInstaller` · `daisyUI`

---

### 🌐 [geo-core](https://github.com/CalebLouwskitter/geo-core)
**Zero-dependency, platform-agnostic TypeScript toolkit for spatial calculations, geometric operations, and GIS format interchange.**

- **Platform-free spatial algorithms:** Implements haversine distance, bearings, Douglas-Peucker line simplification, ray-casting point-in-polygon (with holes), and polyline snapping with zero runtime dependencies.
- **Bi-directional GIS format conversion:** Parses, validates, and converts spatial datasets between GPX (1.0/1.1) and GeoJSON specifications while preserving metadata and temporal attributes.
- **Modern packaging & strict verification:** Bundled with tsup for dual ESM/CommonJS distribution with full TypeScript declarations, tested with Vitest in Node environments.

`TypeScript` · `Node.js` · `Vitest` · `tsup` · `Changesets`

---

### 🐎 [WIL_App](https://github.com/CalebLouwskitter/WIL_App) *(University team project)*
**Offline-first mobile application developed for the Sardinia Bay Horse Riders Association (SBHRA) to record trail rides and monitor rider safety.**

- **Offline-resilient trail tracking:** Logs GPS coordinates locally on-device during rides and automatically synchronises with Firebase Firestore once network connectivity is restored.
- **Incident reporting & safety features:** Supports animal sighting and trail obstruction reporting with photos, live location SOS alerts, and GPX track export for external mapping platforms.
- **Compliance & analytics dashboard:** Aggregates trail usage data into administrative views to generate monthly, quarterly, and annual compliance reports. *(Caleb Louwskitter contributed: Firebase integration, reports & sightings, and dashboard).*

`React Native` · `Expo (SDK 57)` · `TypeScript` · `Firebase` · `Google Maps`

---

## 🛠 Core Skills & Technologies

### **Languages & Frameworks**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![GnuCOBOL](https://img.shields.io/badge/-GnuCOBOL-BD8356?style=for-the-badge)
![Kotlin](https://img.shields.io/badge/-Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)

### **Backend & API Development**
![.NET](https://img.shields.io/badge/-.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET%20Core-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20API-02569B?style=for-the-badge&logo=swagger&logoColor=white)
![Entity Framework](https://img.shields.io/badge/-Entity%20Framework-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![Microservices](https://img.shields.io/badge/-Microservices-FF6F00?style=for-the-badge&logo=microgenetics&logoColor=white)

### **Mobile & Cross-Platform**
![Android](https://img.shields.io/badge/-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/-iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Unity](https://img.shields.io/badge/-Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![VR/AR](https://img.shields.io/badge/-VR%2FAR-FF6F00?style=for-the-badge&logo=oculus&logoColor=white)

### **Databases**
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### **Cloud & DevOps**
![Microsoft Azure](https://img.shields.io/badge/-Microsoft%20Azure-0089D0?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/-Azure%20DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)

### **Emerging Technologies**
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![AI](https://img.shields.io/badge/-AI%2FML-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LLM](https://img.shields.io/badge/-LLM%20Deployment-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=CalebLouwskitter&show_icons=true&theme=vue-dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CalebLouwskitter&layout=compact&theme=vue-dark&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=CalebLouwskitter&theme=vue-dark&hide_border=true)

---

## 🎯 Key Focus Areas

- 🌐 **Full-stack Development** - Modern architectures and scalable solutions
- 🔌 **API Engineering** - Microservices and RESTful design patterns  
- ⚙️ **DevOps & Automation** - CI/CD pipelines and container orchestration  
- ☁️ **Cloud Infrastructure** - Azure-native deployment and IaC practices  
- 🧩 **Immersive Technologies** - VR/MR interfaces and interactive systems  
- 🤖 **AI Integration** - LLM deployment, edge computing, and IoT prototyping

---

## 💼 Professional Values

![Clean Code](https://img.shields.io/badge/-Clean%20Code-61DAFB?style=flat-square&logo=code&logoColor=white)
![Security](https://img.shields.io/badge/-Security%20First-FF6B6B?style=flat-square&logo=shield&logoColor=white)
![Agile](https://img.shields.io/badge/-Agile%20Development-4ECDC4?style=flat-square&logo=agile&logoColor=white)
![Collaboration](https://img.shields.io/badge/-Team%20Collaboration-45B7D1?style=flat-square&logo=teamwork&logoColor=white)

- 🧽 **Code Quality** - Writing clean, well-documented, and testable code  
- 📐 **Scalable Design** - Architecture for performance and maintainability  
- 🔐 **Security-Aware** - Security considerations across all development layers  
- 🔁 **Agile Delivery** - Iterative development and continuous improvement  
- 🤝 **Cross-Functional** - Bridging engineering, UX, and infrastructure teams

---

## 📈 Current Learning & Exploration

![Learning](https://img.shields.io/badge/-Always%20Learning-FF9500?style=flat-square&logo=graduation-cap&logoColor=white)

- 🚀 Advanced Kubernetes orchestration and service mesh
- 🧠 Large Language Model fine-tuning and deployment
- 🥽 Advanced AR/VR development with Unity and native platforms
- 🔧 Edge computing and IoT device integration
- 📱 Cross-platform development optimization

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/CalebLouwskitter)
[![Email](https://img.shields.io/badge/-Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:CalebLouwskitter@Gmail.com)
[![Portfolio](https://img.shields.io/badge/-View%20Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel-portfolio-eta-eight.vercel.app/)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</div>

⭐ *Feel free to explore my repositories and don't hesitate to reach out for collaborations!*

