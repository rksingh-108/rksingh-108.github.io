<div align="center">

# 👋 Hi, I'm Ritikesh Kumar Singh

### 🚀 Full-Stack Developer • 🤖 AI Builder • 🎓 BCA Student

**Building production-oriented web applications, backend systems & AI-powered products.**

<p>
  <a href="https://rksingh-108.github.io/">🌐 Portfolio</a> •
  <a href="https://github.com/rksingh-108">💻 GitHub</a> •
  <a href="https://linkedin.com/in/rksingh108">💼 LinkedIn</a> •
  <a href="mailto:rksingh108@outlook.com">📧 Email</a>
</p>

![Open to Internships](https://img.shields.io/badge/🟢_Open_to-Software_%2F_AI_Internships-2ea043?style=for-the-badge)
![BCA](https://img.shields.io/badge/🎓_BCA-2027-8957e5?style=for-the-badge)
![Location](https://img.shields.io/badge/📍_Vadodara-India-0969da?style=for-the-badge)

</div>

---

## 🧭 Quick Navigation

<details>
<summary><b>📌 Explore this README</b></summary>

- 👨‍💻 [About Me](#-about-me)
- 🛠️ [Tech Stack](#️-tech-stack)
- 🚀 [Featured Projects](#-featured-projects)
- 🧪 [More Experiments](#-more-experiments)
- 🏗️ [How I Build](#️-how-i-build)
- 🔭 [Currently Exploring](#-currently-exploring)
- 🎓 [Education](#-education)
- 🎯 [What I'm Looking For](#-what-im-looking-for)
- 📫 [Connect With Me](#-connect-with-me)

</details>

---

## 👨‍💻 About Me

I'm a **BCA student** who enjoys building **complete products**, rather than isolated demos.

I work across:

- 🎨 Frontend applications
- ⚙️ Backend APIs & services
- 🗄️ Database design
- 🔐 Authentication & RBAC
- ⚡ Real-time systems
- 🤖 AI / LLM applications
- ☁️ Cloud deployment & production infrastructure

I care about how the pieces of a system fit together — **API contracts, data models, authentication flows, failure cases, safe workflows, and deployment**.

### 🔄 My Build Cycle

```text
💡 Idea
   ↓
🏗️ Architecture
   ↓
💻 Implementation
   ↓
🔐 Hardening
   ↓
☁️ Deployment
   ↓
🚀 Production
```

---

## 🛠️ Tech Stack

<details open>
<summary>💻 <b>Languages</b></summary>

`Python` `JavaScript` `TypeScript`

</details>

<details>
<summary>🎨 <b>Frontend</b></summary>

`React` `Next.js`

</details>

<details>
<summary>⚙️ <b>Backend</b></summary>

`Node.js` `Express` `Fastify` `Flask`

</details>

<details>
<summary>🗄️ <b>Databases</b></summary>

`PostgreSQL` `MongoDB` `SQLite` `pgvector`

</details>

<details>
<summary>🤖 <b>AI / LLM</b></summary>

`RAG` `Agentic Tool Calling` `LLM Integration` `Groq`

</details>

<details>
<summary>☁️ <b>Cloud / DevOps</b></summary>

`Docker` `Azure` `Vercel` `Render` `Supabase` `Git / GitHub`

</details>

<details>
<summary>🧠 <b>Core Engineering</b></summary>

`REST APIs` `JWT / RBAC` `Real-Time Systems` `Database Design`

</details>

---

# 🚀 Featured Projects

## 🚕 1. TRYLO

### Full-Stack Ride-Booking Platform

TRYLO is an **end-to-end ride-booking system** designed around real-time location, geo-based driver matching, multiple user roles, and reliable wallet settlement.

### ✨ Highlights

| Feature | What it does |
|---|---|
| 📍 Geo Matching | Progressive **1 km → 2 km → 3 km** driver search |
| 🛰️ Live Tracking | Real-time driver GPS using Socket.IO |
| 🔐 Authentication | Phone + OTP + JWT access/refresh |
| 👥 RBAC | Customer, Driver & Admin roles |
| 💰 Wallet | Internal wallet & payment system |
| ⚛️ Settlement | Atomic + idempotent wallet settlement |
| 🗺️ Maps | MapLibre + OSRM routing |
| 📌 Geocoding | Nominatim / Photon |
| 🐳 Deployment | Docker + Azure |

### 🧩 Architecture

```text
        👤 Customer
             │
        🚗 Driver
             │
        🛡️ Admin
             │
             ▼
    ┌─────────────────┐
    │  Common Backend  │
    └────────┬────────┘
             │
             ▼
      🗄️ PostgreSQL
             │
             ▼
      ⚡ Real-Time Services
```

### 🧰 Stack

`Next.js` `React` `Express.js` `PostgreSQL` `Prisma` `Socket.IO` `MapLibre` `OSRM` `Docker` `Azure`

> 🏆 **Focus:** Real-time systems, geospatial matching, reliable money movement and end-to-end system ownership.

---

## 🤖 2. WorkPilot AI

### AI Workplace Agent

WorkPilot AI is designed to go beyond simply answering questions. It combines **company knowledge, tasks, meetings and workflows** to provide actionable assistance and execute structured actions with human approval.

### ✨ Highlights

- 🧠 AI agent for tasks, emails, calendars & meetings
- 📅 Personalized daily planning
- 🤝 Meeting preparation
- 🔗 Multi-step agentic workflows
- 🛠️ Agentic tool calling
- 🔎 RAG-powered company knowledge search
- 🗄️ PostgreSQL + pgvector
- 🔐 Authentication & RBAC
- 👤 Human-in-the-loop approval
- 🧾 Full audit trail

### 🧩 Agent Flow

```text
👤 User
   ↓
🤖 AI Agent
   ↓
🛠️ Tool Calling
   ↓
🔎 RAG / pgvector
   ↓
👤 Human Approval
   ↓
⚡ Action
```

### 🧰 Stack

`Next.js` `TypeScript` `Fastify` `PostgreSQL` `pgvector` `Groq` `RAG` `JWT/RBAC` `Supabase` `Vercel` `Render`

### ☁️ Deployment

```text
🎨 Frontend  → Vercel
⚙️ Backend   → Render
🗄️ Database  → Supabase PostgreSQL + pgvector
🧠 LLM       → Groq
```

> 🏆 **Focus:** Turning an AI chatbot into an agent that can safely perform real actions.

---

## 📊 3. Employee Performance Tracker

### Flask-Based Employee Analytics Application

A smaller-scale production-style application demonstrating real authentication, relational modelling, protected routes, performance scoring and dashboards.

### ✨ Features

- 👑 Admin & employee roles
- 🔐 Authentication
- 🔒 Hashed credentials
- 🛡️ Protected routes
- 👥 Role-based access control
- 🗄️ Relational database schema
- 📈 Performance scoring engine
- 📊 Department reports
- 📉 Analytics dashboards

### 🧰 Stack

`Flask` `SQLAlchemy` `SQLite` `Chart.js`

---

# 🧪 More Experiments

| 🧩 Project | 💡 Description |
|---|---|
| 🛒 **ShopNest** | E-commerce storefront with cart & product flows |
| 💼 **Job Portal** | Listings, applications & role-based access |
| 🎓 **Student Grade Management** | CRUD system with relational records |
| 🌦️ **Weather App** | Live weather through public API integration |
| 🧮 **Calculator CLI** | Command-line tool with parsed expressions |

👉 Explore more on **[GitHub](https://github.com/rksingh-108)**.

---

# 🏗️ How I Build

<details>
<summary>1️⃣ <b>Architect</b></summary>

I design the system before writing features:

- 🗄️ Data model
- 🔌 API contracts
- 🧩 Service boundaries
- 🏛️ Application architecture

</details>

<details>
<summary>2️⃣ <b>Build</b></summary>

I implement the frontend, backend, database and integrations as one coherent system.

</details>

<details>
<summary>3️⃣ <b>Harden</b></summary>

I focus on:

- 🔐 Authentication
- 🛡️ Authorization
- ✅ Validation
- 🚨 Error handling
- 🔄 Safe workflows
- ♻️ Idempotency

</details>

<details>
<summary>4️⃣ <b>Deploy</b></summary>

I move beyond localhost using:

- 🐳 Docker
- ☁️ Cloud infrastructure
- ⚙️ Production-oriented configuration
- 🚀 Real deployments

</details>

---

# 🔭 Currently Exploring

I'm currently exploring the gap between a **chatbot** and an **agent that can safely take actions inside real systems**.

```text
🤖 LLM Applications
       +
🧠 AI Agents & Tool Calling
       +
🔎 RAG Systems
       +
⚡ Real-Time Systems
       +
🏗️ Scalable Backend Architecture
```

---

# 🎓 Education

### BCA — Bachelor of Computer Applications

**Parul University · Vadodara, Gujarat, India**

| 📚 | Details |
|---|---|
| 📖 Current | 5th Semester |
| 🎯 Expected Graduation | 2027 |
| 📊 CGPA | **7.81 / 10** |

---

# 🎯 What I'm Looking For

I'm currently open to:

- 💻 Software Engineering Internships
- 🌐 Full-Stack Development
- ⚙️ Backend Engineering
- 🤖 AI / LLM Engineering
- 🚀 Software / AI opportunities

---

# 📫 Connect With Me

<div align="center">

### Let's build something useful. 🚀

| 🔗 | Link |
|---|---|
| 🌐 Portfolio | [rksingh-108.github.io](https://rksingh-108.github.io/) |
| 💻 GitHub | [github.com/rksingh-108](https://github.com/rksingh-108) |
| 💼 LinkedIn | [linkedin.com/in/rksingh108](https://linkedin.com/in/rksingh108) |
| 📧 Email | [rksingh108@outlook.com](mailto:rksingh108@outlook.com) |

</div>

---

# 💭 Philosophy

> **"Build complete systems, not just demos."**

I like taking a product from a **blank repository → architecture → code → security → infrastructure → deployment** and understanding every layer along the way.

---

<div align="center">

### ⚡ RKS_

**Full-Stack Developer · AI Builder · BCA Student**

<br>

⭐ If you find my work interesting, consider checking out my projects on GitHub!

</div>
