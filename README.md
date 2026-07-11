# Hi, I'm Anthony Nebenmor 👋

<div align="center">
  
[![Portfolio](https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://devanthon.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-nebenmor)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/AnthonyNebenmor)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nebenmor.anthony@gmail.com)

</div>

## 🚀 Backend Engineer | Node.js · Python/FastAPI · PostgreSQL | Fintech & SaaS Systems

Building production-grade backend systems, real-time platforms, and fintech infrastructure. 3 years of experience shipping systems that handle real-world complexity — payments, multi-tenancy, webhooks, async processing, and live data.

- 🔭 Currently building: **JobSense** — AI-powered CV analysis tool using Claude API (Anthropic)
- 🌱 Learning: **React Native (mobile development)** · **n8n AI automation workflows**
- 🎯 Long-term: **DevOps/Cloud engineering (Kubernetes, AWS)** — KCNA certification planned
- 💼 Open to: **Backend Engineer, Full-Stack, and Remote opportunities**
- 📍 Location: **Lagos, Nigeria** 🇳🇬
- ⚡ Fun fact: **Started as a Biochemistry graduate. Now I build fintech systems.**

---

## 🛠️ Tech Stack

### **Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

### **Databases & Caching**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **Frontend**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### **Mobile**
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

### **DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### **AI & Automation**
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

### **Testing**
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

### **Currently Learning**
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 🔥 Featured Projects

### [Flowspace — Real-Time Collaborative Task Management](https://github.com/Nebenmor/flowspace)
**Production-grade full-stack multi-tenant SaaS platform (Jira-like)** 🚀

- Multi-tenant architecture: organizations, workspaces, RBAC, real-time presence
- WebSocket rooms per workspace with TanStack Query cache invalidation on task events
- Resilient webhook delivery — HMAC-SHA256 + exponential backoff retry (1m → 5m → 30m → 2h → 8h)
- Celery background workers, Redis caching with workspace-scoped invalidation, GIN-indexed full-text search
- React 19 dashboard with analytics (team productivity, completion trends, time-to-completion)
- 35 Pytest tests across auth, task management, and webhook delivery suites

**Tech:** `FastAPI` `Python` `PostgreSQL (async)` `SQLAlchemy` `Celery` `Redis` `WebSockets` `React 19` `TanStack Query` `Docker`

---

### [PayRoute — Cross-Border Payment Processing](https://github.com/Nebenmor/PayRoute)
**Fintech-grade payment platform for cross-border transactions** 💳

- Full payment lifecycle: FX quote locking → balance debit → provider submission → webhook settlement
- Double-entry bookkeeping ledger with `SELECT FOR UPDATE` overdraft prevention
- Idempotency middleware + HMAC-SHA256 webhook verification + raw-body-first persistence
- React frontend: live FX preview, paginated transaction list, ledger entry timeline
- Containerized with Docker Compose, full Jest/Supertest test coverage

**Tech:** `Node.js` `Express.js` `PostgreSQL` `React` `Vite` `Tailwind CSS` `Docker` `Jest`

---

### [JobSense — AI-Powered CV Analysis Tool](https://github.com/Nebenmor/jobsense) *(In Progress)*
**CV-to-job-description fit analyzer using Groq API** 🤖

- FastAPI backend + Groq API with structured LLM JSON output extraction
- PDF text extraction with content validation and clean error handling
- Returns match score, matching skills, missing keywords, and actionable improvement suggestions
- Data minimization: no raw CV storage, analysis-only persistence with auto-expiry

**Tech:** `FastAPI` `Python` `Groq API` `PostgreSQL` `React` `TypeScript`

---

### [SwiftTalk — Real-Time Chat Application](https://github.com/Nebenmor/swift-talk)
**Real-time messaging platform with 99.9% uptime** 💬

- Socket.IO WebSocket backend with typing indicators, read receipts, and file sharing (10MB)
- JWT authentication, rate limiting (100 req/min), indexed MongoDB (sub-100ms retrieval)
- Compound index on (conversationId, timestamp) — 60% query latency reduction
- 🔗 [Live Demo](https://swifttalk-chat.vercel.app)

**Tech:** `Node.js` `Express.js` `Socket.IO` `MongoDB` `React 19` `TypeScript`

---

## 🏆 Achievements & Impact

- ✅ **Flowspace:** Production full-stack SaaS — async PostgreSQL, Celery workers, Redis, exponential backoff webhooks, 35 tests
- ✅ **PayRoute:** Fintech-grade payment processor — double-entry bookkeeping, idempotency, HMAC verification, zero double-crediting
- ✅ **80% of backend** architecture for enterprise property management system — sub-200ms response times
- ✅ **40% performance improvement** through strategic PostgreSQL indexing and query optimization
- ✅ **95%+ test coverage** with Pytest and Jest across production backends
- ✅ **1,500+ lines** of production React Native code (22+ components) shipped at Smash Technology

---

## 🎯 Current Focus

```javascript
const anthony = {
  currentlyBuilding: [
    "JobSense — AI CV analyzer (Groq API + FastAPI)",
    "React Native fintech mobile app"
],
  currentlyLearning: [
    "React Native advanced patterns",
    "n8n AI automation workflows",
    "Kubernetes (KCNA certification — 2027)"
  ],
  strongestSkills: [
    "Backend systems (Node.js, Python/FastAPI)",
    "Fintech & payment systems",
    "Real-time architecture (WebSockets)",
    "Async processing (Celery, Redis)",
    "Webhook design & reliability"
  ],
  openToWork: true,
  lookingFor: "Backend Engineer · Full-Stack · Remote opportunities",
  location: "Lagos, Nigeria 🇳🇬"
};
```

---

## 📊 GitHub Stats

<div align="center">

![Anthony's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Nebenmor&show_icons=true&theme=dark&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Nebenmor&layout=compact&theme=dark&hide_border=true)

</div>

---

## 📬 Let's Connect

I'm open to backend engineering roles, full-stack opportunities, and remote contracts.

- 📧 **Email:** nebenmor.anthony@gmail.com
- 🌐 **Portfolio:** [devanthon.vercel.app](https://devanthon.vercel.app)
- 💼 **LinkedIn:** [linkedin.com/in/anthony-nebenmor](https://www.linkedin.com/in/anthony-nebenmor)
- 🐦 **Twitter/X:** [@AnthonyNebenmor](https://twitter.com/AnthonyNebenmor)
