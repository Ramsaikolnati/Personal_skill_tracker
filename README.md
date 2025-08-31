# 🧠 Skill Tracker App

A personal productivity and performance tracking tool to help developers monitor and grow their skills consistently. This full-stack project allows users to log skill-based goals, track learning progress, and analyze growth over time.

Built from scratch with modern technologies: **FastAPI**, **PostgreSQL**, **React (Next.js)**, **Docker**, **Celery**, and more — deployed securely with **Let’s Encrypt**, and **GitHub Actions**.

---

## 🚀 Features

- ✅ **Authentication with JWT**
- 🎯 Skill logging: Add, edit, delete skills you're learning
- 📈 Track progress by daily/weekly updates
- 🧠 Learning stats and skill mastery analytics
- 🗓️ Habit/goal tracking
- 🔔 Email reminders for consistency (via Celery & Redis)
- 👤 Profile dashboard with level-based growth system
- 🌐 Fully containerized with Docker & Traefik
- ✅ Unit and integration tested with Pytest

---

## 🧰 Tech Stack

| Layer        | Tech Stack                                                                 |
|--------------|-----------------------------------------------------------------------------|
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS                                    |
| **Backend**  | FastAPI, SQLAlchemy / SQLModel, Alembic                                     |
| **Database** | PostgreSQL                                                                  |
| **Auth**     | JWT (Access + Refresh tokens)                                               |
| **Tasks**    | Celery + Redis (for async job queue)                                        |
| **DevOps**   | Docker, Traefik, Let’s Encrypt, GitHub Actions CI/CD                        |
| **Testing**  | Pytest                                                                      |

---

## 📸 Screenshots

<!-- You can add local screenshots or link to deployed frontend once hosted -->
- 📍 Skill Tracker Dashboard  
- 📊 Progress Visualizations  
- 🧩 Add / Update / Delete Skill Flows  
- 📬 Notification Settings

---

## 🔐 Authentication Flow

- User registers and logs in
- JWT access + refresh tokens are issued
- Secure API routes validate access token using dependency injection
- Refresh flow supported to renew tokens

