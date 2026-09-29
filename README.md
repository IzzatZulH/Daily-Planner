# 📊 Operations & Field Activity Tracker

A responsive, offline-first web application designed for mobile field officers, logistics supervisors, and operational teams to schedule daily activities, monitor field expenditures, capture photographic verification, and compile client-side PDF executive memos.

Built with **Modern Vanilla JavaScript**, **Responsive Modular CSS**, **HTML5 LocalStorage Architecture**, and **Client-Side jsPDF Generation**.

---

## 🌐 Live Interactive Deployment

* **Live Demo:** `https://izzatzulh.github.io/Daily-Planner/`
* **GitHub Repository:** `https://github.com/IzzatZulH/Daily-Planner/`
* **Author / Developer:** Izzat Zul

---

## 🚀 Architectural Highlights

### 1. ⚡ Client-Side Resilient Offline Architecture
* **Hybrid Storage Layer:** Engineered to run seamlessly offline using browser `localStorage` caching and an event-driven sync queue that gracefully integrates with cloud backends (Supabase REST APIs) upon network reconnect.
* **Zero Credential Leakage:** Architecture separates client UI logic from cloud configuration, enabling safe open-source public demonstration without exposing proprietary database credentials or API keys.

### 2. 📑 Automated Executive Reporting & PDF Engine
* **Instant Memorandum Generation:** Compiles structured corporate activity memos aggregating completion rates, operational expenditures, and categorized task outcomes.
* **Client-Side Vector PDF Export:** Uses `jsPDF` to generate formatted A4 documents directly in the client browser with zero server roundtrips.

### 3. 🎯 Operational Metrics & Telemetry
* **Real-Time Financial Tracking:** Dynamically tallies day-level and multi-scope operational expenditures (e.g., ad spends, travel allowance, logistics fees).
* **Schedule Matrix & Filter Pipeline:** Features responsive date navigation, dynamic full-text search, and multi-tier filtering by status, category, and priority.

---

## 🛠️ Tech Stack & Dependencies

* **Frontend Engine:** Vanilla JavaScript (ES6+), HTML5, Semantic CSS Grid & Flexbox
* **Document Engine:** jsPDF (Client-Side Vector PDF Compiler)
* **Cloud Ready:** Modular Supabase SDK interface with offline fallback
* **Deployment:** Hosted directly on GitHub Pages

---

## 📬 Contact

* **Developer:** Izzat Zul
* **GitHub:** https://github.com/IzzatZulH
* **Email:** izzatzulh2000@gmail.com
