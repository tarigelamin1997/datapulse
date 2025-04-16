# 📊 DataPulse – Smart Business Analytics Platform

**DataPulse** is a plug-and-play analytics and reporting platform built for small and medium-sized retail businesses. It syncs with existing POS or ERP systems to transform raw sales, inventory, and cost data into actionable insights — delivered through a real-time dashboard, automated PDF reports, and optional Zoom consulting.

---

## 🚀 Features

- 🔄 Connect your existing POS / ERP system (Shopify, Odoo, etc.)
- 📈 Real-time sales and profit tracking
- 🧾 Basic accounting summaries
- 📦 Inventory alerts and stock insights
- 📊 Daily, weekly, and monthly PDF reports
- 🌐 Mobile and web dashboards
- 💬 Optional Zoom-based business consulting

---

## 🧰 Tech Stack

- **Backend**: Python + FastAPI
- **Frontend**: React / Vite (Web), React Native (Mobile)
- **Database**: PostgreSQL
- **PDF Generation**: WeasyPrint / wkhtmltopdf
- **Hosting**: GitHub Pages (landing), AWS/GCP (app)

---

## 📍 Current Status

This repository currently includes:

- ✅ Project structure setup
- ✅ Basic landing page (hosted via GitHub Pages)
- 🚧 MVP analytics engine in development
- 🚧 POS sync adapters coming soon

---

## 📦 Getting Started

1. Clone the repo  
   `git clone https://github.com/yourusername/datapulse.git`

2. Navigate and run (backend example):
   ```bash
   cd backend
   pip install -r requirements.txt
   uvicorn app.main:app --reload
