🛡️ Automated Fake News Monitoring & Awareness Platform

A fully automated web platform that continuously monitors news sources, detects fake news, provides verified corrections, and visualizes how misinformation spreads across different platforms — all through a clean, user-friendly dashboard.

🚀 Project Overview

This project is designed as a public awareness and monitoring system.
Users do not submit news manually. Instead, the system automatically:

Scrapes news data at scheduled intervals

Detects fake, real, or unverified news

Generates corrected information for fake news

Analyzes how fake news spreads across platforms

Displays everything on a single live dashboard

The goal is to reduce misinformation, increase awareness, and support informed decision-making.

🎯 Key Features

🔄 Fully Automated Workflow (No user input required)

🧹 Scheduled Web Scraping (runs twice daily)

🧠 Fake News Detection Engine

📝 Corrected Information for Fake News

📊 Big Interactive Dashboard

📈 Platform-wise Spread Analysis

🌐 Live Deployed Website

🧠 Fake News Detection Strategy

Instead of relying on generative AI or RAG, the system uses a safer and more reliable hybrid approach:

Rule-Based Analysis

Panic words

Clickbait language

Urgency indicators

Source Credibility Scoring

Trusted vs untrusted domains

Pattern-Based ML Model (Optional)

Pretrained classifier for linguistic patterns

Classification Labels:

❌ Fake

✅ Verified

⚠️ Unverified

⚠️ The system does not claim absolute truth for breaking news and responsibly marks such cases as Unverified.

System Workflow (End-to-End)

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

🖥️ Tech Stack
Frontend

React.js

Next.js

Tailwind CSS

Chart.js / Recharts

Deployed on Vercel

Backend

Node.js

Express.js

Web Scraping Logic

Cron Job Scheduler

Fake News Detection Logic

Deployed on Render

Database

MongoDB Atlas (Cloud Database)

📊 Dashboard Modules
🔴 Fake News Panel

Fake headline

Platform(s) where it spread

Timestamp

Corrected information

🟢 Verified News Panel

Trusted news articles

Source name

Publication time

📈 Spread Analytics

Fake news count per platform

Platform-wise comparison

Trend over time

⚠️ Alerts Section

Trending fake news

Most shared misinformation


⏰ Cron Job Scheduling

Runs twice a day

Automatically triggers web scraping

No frontend or user interaction required

Example:

Morning run

Evening run
