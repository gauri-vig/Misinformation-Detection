# 🛡️ Automated Fake News Monitoring & Awareness Platform

A fully automated web platform that continuously monitors news sources, detects fake news, provides verified corrections, and visualizes how misinformation spreads across digital platforms — all through a clean, user-friendly dashboard.

---

## 🚀 Project Overview

This project is designed as a **public awareness and monitoring system**.  
Users do **not** submit news manually. Instead, the system automatically:

- Scrapes news data at scheduled intervals
- Detects fake, verified, or unverified news
- Generates corrected information for fake news
- Analyzes how misinformation spreads across platforms
- Displays everything on a single live dashboard

**Goal:** Reduce misinformation, increase awareness, and support informed decision-making.

---

## 🎯 Key Features

- 🔄 Fully Automated Workflow (No user input required)
- 🧹 Scheduled Web Scraping (Runs twice daily)
- 🧠 Fake News Detection Engine
- 📝 Corrected Information for Fake News
- 📊 Interactive Analytics Dashboard
- 📈 Platform-Wise Spread Analysis
- ⚠️ Trending Fake News Alerts
- 🌐 Live Deployed Website

---

## 🧠 Fake News Detection Strategy

Instead of relying on generative AI or RAG models, this system uses a **safer hybrid detection approach**.

### Rule-Based Analysis
- Panic and fear-inducing words
- Clickbait language patterns
- Urgency indicators
- Sensational headline structures

### Source Credibility Scoring
- Trusted vs untrusted domains
- Domain reputation analysis
- Historical source reliability

### Pattern-Based ML Model (Optional)
- Pretrained lightweight classifier
- Linguistic and structural pattern detection

### Classification Labels
- ❌ Fake
- ✅ Verified
- ⚠️ Unverified

> ⚠️ Breaking or insufficiently verified news is responsibly labeled as **Unverified**.

---

## 🔄 System Workflow

Cron Job (Scheduler)
↓
Web Scraping
↓
Database (Raw News)
↓
Fake News Detection Engine
↓
Database (Final Results)
↓
Backend APIs
↓
Frontend Dashboard


---

## 🖥️ Tech Stack

### Frontend
- React.js
- Next.js
- Tailwind CSS
- Chart.js / Recharts
- Deployment: Vercel

### Backend
- Node.js
- Express.js
- Web Scraping Logic
- Cron Job Scheduler
- Fake News Detection Engine
- Deployment: Render

### Database
- MongoDB Atlas (Cloud)

---

## 📊 Dashboard Modules

### 🔴 Fake News Panel
- Fake headline
- Platform(s) where it spread
- Timestamp
- Corrected information

### 🟢 Verified News Panel
- Trusted news articles
- Source name
- Publication time

### 📈 Spread Analytics
- Fake news count per platform
- Platform-wise comparison
- Trend over time

### ⚠️ Alerts Section
- Trending fake news
- Most shared misinformation

---

## ⏰ Cron Job Scheduling

- Runs twice daily
- Fully automated
- No user interaction required

**Example Schedule:**
- Morning run
- Evening run

---

## 🌐 Deployment Architecture

| Layer     | Platform |
|----------|----------|
| Frontend | Vercel   |
| Backend  | Render   |
| Database | MongoDB Atlas |

---

## 🛡️ Ethical Design Principles

- No user-submitted misinformation
- No generative or hallucinated truth claims
- Transparent classification logic
- Responsible handling of breaking news
- Awareness-focused design

---

## 📌 Use Cases

- Public misinformation awareness
- Academic and research projects
- Media literacy platforms
- Hackathons and innovation challenges
- Policy and governance dashboards (conceptual)

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤝 Contributing

Contributions are welcome.  
Please open an issue or submit a pull request.

---

## ⭐ Final Note

This project demonstrates how **automation, rule-based intelligence, and ethical design** can be combined to build reliable misinformation monitoring systems without unsafe AI claims.
