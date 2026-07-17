# Hi there, I'm Kais 👋

I'm a **GLSI2 student** passionate about building real-world solutions — from AI-powered web apps to embedded systems. I love bridging the gap between hardware and software, and I'm always tinkering with something new.

---

## 🧰 Tech Stack
**Languages**
`Python` `JavaScript` `TypeScript` `Java` `Solidity` `C` `SQL` `PHP` `CSS`

**Frontend**
`React` `Angular` `Vite` `Thymeleaf` `HTML/CSS`

**Backend**
`Flask` `FastAPI` `Node.js` `Express` `Spring Boot`

**ML / AI**
`scikit-learn` `XGBoost` `pandas` `NumPy`

**Databases**
`SQLite` `PostgreSQL` `MySQL` `MongoDB`

**Embedded Systems**
`Arduino` `MFRC522 (RFID)`

**Blockchain**
`Ethereum` `Hardhat` `ethers.js` `Solidity`

**DevOps & Tools**
`Git` `GitHub Actions` `Railway` `Docker` `Maven` `JWT` `REST APIs`

---

## 🚀 Featured Projects

### 🛡️ [PhishGuard](https://github.com/zouaouikais4/phishguard)
> AI-powered phishing URL detection tool

A full-stack cybersecurity tool that classifies URLs as phishing or legitimate using a trained **XGBoost** model. Integrates **VirusTotal v3** and **Google Safe Browsing APIs** for enriched threat intelligence.

- Built with **Python / Flask** backend + vanilla JS frontend
- Trained on the **LegitPhish 2025** dataset with 30+ feature extractors
- CI/CD via **GitHub Actions**, deployed on **Railway**
- Includes a `/health` endpoint, backend URL sanitization, and a full **pytest** suite (30+ tests with mocked APIs)

---

### 📋 RFID Attendance Management System
> Hardware-meets-web attendance tracking

An end-to-end attendance system using **Arduino Uno + MFRC522** for card scanning, with a **Flask + SQLite** backend and a **React/Vite** frontend.

- JWT-based authentication
- Per-student history modals, class/group filtering
- Unknown card alerts
- Excel export for attendance reports

---

### 🗂️ File-Sharing Platform
> Cloud-based file distribution with payments

A **Node.js / Express + React** platform supporting **Cloudinary** ZIP uploads, download-via-redirect, **Stripe** payments, and a blockchain service integration.

- PostgreSQL database
- Multer for file handling
- Secure download flows

---


### 🛒 Online Store
> Spring Boot inventory & order management app

A full-stack web application for managing product inventory and processing orders, built with a layered **Spring MVC + JPA** architecture.

- **Spring Boot 4** backend with Spring Data JPA and Bean Validation
- **Thymeleaf** templating for a responsive admin dashboard
- **MySQL** database with duplicate product code enforcement at both service and DB level
- Product image management with placeholder fallback, payment/order form

---

### 🗳️ VoteChain
> Decentralized jury voting on Ethereum

A blockchain-based voting system where an admin registers candidates, randomly selects 3 jury members via an on-chain **Fisher-Yates shuffle**, and manages the voting lifecycle entirely through a smart contract.

- **Solidity** smart contract deployed on a local Hardhat node
- Jury members each receive 10 votes to distribute freely among candidates
- Pure **HTML/JS + ethers.js v6** frontend — no build step required
- Full event logging: `VoteCast`, `JurySelected`, `VotingStarted/Ended`

---
### 📚Bibliothèque
> PHP & MySQL library management system

Full-stack web app built with PHP and MySQL featuring a public catalogue, member authentication, borrowing & reservation system, and a complete admin dashboard with reporting and email notifications.

`PHP` `MySQL` `CRUD` `Authentication` `Admin Dashboard`

---

### 🎓 [ProjetManager — Fil Rouge GLSI2](https://github.com/zouaouikais4/projetmanager)
> Collaborative project management platform with real-time chat

Full-stack capstone project (FastAPI + React) built across 3 Scrum sprints, letting students manage projects, assign Kanban tasks, invite teammates, and chat in real time — with teacher supervision and grading built in.

- **FastAPI + SQLAlchemy** backend with JWT auth (bcrypt-hashed passwords, sessionStorage tokens)
- Drag-and-drop **Kanban board** (To Do / In Progress / Done) with priorities, due dates, and comments
- **WebSocket** group chat per project: typing indicators, read receipts, file attachments, auto-reconnect, toast notifications
- Email-based invitation system with token expiry
- Teacher dashboard for cross-project supervision and graded feedback (0–20)

---

### 🏢 CRM Edu
> Full-stack CRM platform with AI-powered insights and role-based access control

An enterprise-style CRM for managing clients, prospects, subscriptions, opportunities, invoices, and tasks across three educational product lines. Combines a Spring Boot backend, an Angular frontend, and a dedicated Python AI microservice — all containerized and orchestrated with Docker Compose.

- **Spring Boot 4 + Angular 21** full stack with JWT authentication and strict **Role-Based Access Control** (Admin / Commercial / Support), enforced at both the API and UI layers with ownership-level checks (e.g. commercial agents only edit their own leads/tasks)
- **AI microservice** (Python/FastAPI + scikit-learn) for lead scoring, churn prediction, and product recommendation — falls back to a documented heuristic when no trained model exists yet
- **Social media data pipeline**: signature-verified Meta Lead Ads / WhatsApp webhooks normalize real acquisition data (channel, engagement, response time) directly into the CRM for smarter lead scoring
- **Interactive Kanban pipeline** for opportunities (7 stages, drag-and-drop) built with Angular signals and `@angular/cdk`
- **Live dashboard** with real-time KPIs, plus Power BI integration via direct MySQL views and DAX measures for executive reporting
- Fully containerized with **Docker Compose** (MySQL, Spring Boot, FastAPI, Angular/Nginx) for one-command local deployment

`Spring Boot` `Angular` `TypeScript` `Java` `Python` `FastAPI` `scikit-learn` `MySQL` `Docker` `JWT` `RBAC` `Power BI`

---

## 🎓 Academic Background

- Studying **GLSI** (Software Engineering & Information Systems)

---

## 📊 GitHub Stats

![Kais's GitHub stats](https://github-readme-stats.vercel.app/api?username=zouaouikais4&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=zouaouikais4&layout=compact&theme=tokyonight&hide_border=true)

---

## 📫 Let's Connect

- 🐙 GitHub: [@zouaouikais4](https://github.com/zouaouikais4)
- 💼 LinkedIn: [Kais Zouaoui](https://www.linkedin.com/in/kais-zouaoui-232337235/)
- 📧 Email: [zouaouikais4@gmail.com](mailto:zouaouikais4@gmail.com)
- 📍 Menzel Bourguiba, Bizerte, Tunisia

---

*"Build things. Break things. Learn. Repeat."*
