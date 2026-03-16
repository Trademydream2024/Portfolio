<div align="center">

# Igor Slobodnichenko

### Backend Developer | Automation Expert | Bot Specialist

[![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Telegram](https://img.shields.io/badge/Telegram_Bots-Specialist-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.org)
[![API](https://img.shields.io/badge/API_Integration-Advanced-FF6F00?style=for-the-badge&logo=fastapi&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Linux_Deploy-Production-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#)

*Building intelligent automation systems that run 24/7*

---

**5+ Production Systems Deployed** · **10+ API Integrations** · **Real-Time Data Processing** · **99.9% Uptime**

---

</div>

## About Me

I'm a **backend developer** specializing in **Python automation**, **Telegram bots**, and **real-time data systems**. I build production-grade solutions that handle complex API integrations, process data in real-time, and make intelligent automated decisions.

My systems currently run **24/7 on production servers** handling real data, real users, and real money.

---

## Featured Projects

### 🔹 Real-Time Weather Intelligence Platform

> *Automated monitoring system that collects, analyzes, and acts on weather data across 20+ US cities*

**The Challenge:** Build a system that monitors weather conditions across multiple cities in real-time, calculates statistical probabilities for temperature ranges, and generates automated alerts and reports.

**What I Built:**
- Multi-city monitoring engine scanning **60+ data streams** simultaneously
- **Probability engine** using normal distribution (CDF) to predict temperature ranges
- Real-time data pipeline with **5-minute update cycles**
- **RSA-PSS cryptographic authentication** for secure API communication
- Automated daily reporting system with performance analytics
- Production deployment with **systemd** auto-restart and monitoring

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6F00?style=flat-square&logo=fastapi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![systemd](https://img.shields.io/badge/systemd-4B275F?style=flat-square&logo=ubuntu&logoColor=white)

**Architecture:**

```
┌─────────────────────────────────────────────────────────┐
│                   Weather Intelligence Platform          │
├─────────────┬──────────────┬──────────────┬─────────────┤
│  Data Layer │  Engine Layer │  Action Layer│  Ops Layer  │
├─────────────┼──────────────┼──────────────┼─────────────┤
│ Weather API │  Probability │  Automated   │  systemd    │
│ Multi-City  │  Calculator  │  Decision    │  Auto-start │
│ Real-Time   │  Statistical │  Engine      │  Monitoring │
│ Forecast    │  Modeling    │  Reporting   │  Logging    │
└─────────────┴──────────────┴──────────────┴─────────────┘
```

**Key Achievements:**
- ✅ Processes data from **20+ cities** simultaneously
- ✅ **99.9% uptime** with automatic crash recovery
- ✅ Sub-second probability calculations using NumPy
- ✅ Secure API auth with RSA-PSS SHA256 signing
- ✅ One-command deployment pipeline

---

### 🔹 Cryptocurrency Market Analytics Engine

> *Multi-strategy analytics platform processing real-time market data with technical indicators*

**The Challenge:** Create a system that connects to cryptocurrency exchange APIs, processes real-time market data, applies multiple technical analysis strategies, and generates actionable insights.

**What I Built:**
- Real-time market data scanner monitoring **multiple trading pairs**
- **VWAP (Volume Weighted Average Price)** bounce detection algorithm
- **RSI (Relative Strength Index)** analysis with custom thresholds
- Multi-strategy evaluation engine with configurable parameters
- Risk management module with position sizing and exposure limits
- WebSocket integration for **millisecond-level data updates**

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6F00?style=flat-square&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Architecture:**

```
┌──────────────────────────────────────────────────────────┐
│              Market Analytics Engine                      │
├──────────────┬──────────────┬─────────────┬──────────────┤
│  Data Feed   │  Strategies  │  Risk Mgmt  │  Reporting   │
├──────────────┼──────────────┼─────────────┼──────────────┤
│ REST + WS    │  VWAP Bounce │  Position   │  Real-Time   │
│ Multi-Pair   │  RSI Filter  │  Sizing     │  Dashboard   │
│ Real-Time    │  Custom      │  Exposure   │  Analytics   │
│ Historical   │  Indicators  │  Limits     │  Alerts      │
└──────────────┴──────────────┴─────────────┴──────────────┘
```

**Key Achievements:**
- ✅ Processes **real-time market data** with sub-second latency
- ✅ Multiple technical analysis strategies running in parallel
- ✅ Built-in risk management with configurable safety rules
- ✅ Handles exchange API rate limits and reconnection logic

---

### 🔹 Gaming Automation Platform (Telegram Bot)

> *Full-featured Telegram bot for gaming communities with integrated payment system*

**The Challenge:** Build a scalable Telegram bot that automates gaming operations, manages users, handles payments, and provides an engaging user experience for a gaming community.

**What I Built:**
- **Telegram bot** with interactive menus, inline keyboards, and callback handlers
- Integrated **payment processing system** for in-bot purchases
- User management with profiles, history, and activity tracking
- Multi-language support and customizable user experience
- **V2 rebuild** with improved architecture and performance
- Automated task scheduling and notification system

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Payments](https://img.shields.io/badge/Payment_API-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Architecture:**

```
┌──────────────────────────────────────────────────────────┐
│              Gaming Automation Bot                        │
├──────────────┬──────────────┬─────────────┬──────────────┤
│  Bot Engine  │  User Mgmt   │  Payments   │  Automation  │
├──────────────┼──────────────┼─────────────┼──────────────┤
│ Commands     │  Profiles    │  Processing │  Scheduler   │
│ Callbacks    │  History     │  Validation │  Tasks       │
│ Menus        │  Tracking    │  Receipts   │  Alerts      │
│ Keyboards    │  Roles       │  Refunds    │  Cron Jobs   │
└──────────────┴──────────────┴─────────────┴──────────────┘
```

**Key Achievements:**
- ✅ **Two major versions** built - V1 and complete V2 rewrite
- ✅ Integrated payment system handling real transactions
- ✅ Scalable architecture supporting hundreds of concurrent users
- ✅ Comprehensive error handling and logging

---

### 🔹 Beta Tester Onboarding Bot (Telegram)

> *Multi-language Telegram bot for managing Android app beta tester registration with admin approval workflow*

**The Challenge:** Build a complete onboarding flow that guides potential beta testers through registration, validates their information, verifies group membership, and grants access only after manual approval and installation confirmation.

**What I Built:**
- **Multi-language support** (English, Russian, Hebrew) with localized messages throughout
- Guided registration flow: requirements acceptance → email collection → group joins → identifier capture
- **Email validation** with regex and fake-pattern filtering
- **Group membership verification** via Telegram API (bot must be admin in groups)
- **Admin approval workflow** with inline buttons for approve/reject
- **Screenshot verification** — users must send app screenshot before access is granted
- Download links and instructions sent to users; access granted only after admin approves screenshot
- JSON-based state persistence for reliable flow across sessions

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![JSON](https://img.shields.io/badge/JSON_Storage-000000?style=flat-square&logo=json&logoColor=white)

**Architecture:**

```
┌──────────────────────────────────────────────────────────┐
│           Beta Tester Onboarding Bot                     │
├──────────────┬──────────────┬─────────────┬──────────────┤
│  Onboarding  │  Validation │  Admin     │  Access      │
├──────────────┼──────────────┼─────────────┼──────────────┤
│ Multi-lang   │  Email      │  Approval   │  Screenshot  │
│ Flow         │  Groups     │  Workflow   │  Verification│
│ State Mgmt   │  Data       │  Inline     │  Links +     │
│ Handlers     │  Persist    │  Buttons    │  Instructions│
└──────────────┴──────────────┴─────────────┴──────────────┘
```

**Key Achievements:**
- ✅ **3 languages** with full translation coverage
- ✅ Admin controls approval; access granted only after screenshot verification
- ✅ Clean handler-based architecture with state routing
- ✅ Secure: credentials loaded from environment variables

**[View on GitHub](https://github.com/Trademydream2024/BetaTestBot)**

---

### 🔹 Client Management CRM System

> *Custom-built CRM for managing client relationships, tracking interactions, and automating follow-ups*

**What I Built:**
- Client database with full CRUD operations
- Interaction history and communication tracking
- Automated follow-up reminders and notifications
- Clean UI for data management

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Database](https://img.shields.io/badge/Database-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)

---

### 🔹 Risk Analysis & Management Bot

> *Telegram-based system for monitoring and managing risk metrics with real-time alerts*

**What I Built:**
- Telegram bot interface for risk monitoring
- Real-time risk calculations and threshold alerts
- Database-backed tracking and historical analysis
- Handler-based architecture for modular command processing

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Database](https://img.shields.io/badge/Database-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

## Technical Skills

<div align="center">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### Specializations
![Telegram Bots](https://img.shields.io/badge/Telegram_Bots-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![API Integration](https://img.shields.io/badge/API_Integration-FF6F00?style=for-the-badge&logo=fastapi&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-4B8BBE?style=for-the-badge&logo=robotframework&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white)

### Tools & Deployment
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-4B275F?style=for-the-badge&logo=ubuntu&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

</div>

---

## What I Can Build For You

| Service | Description |
|---------|-------------|
| 🤖 **Telegram Bots** | Custom bots with payments, user management, automation |
| 🔗 **API Integrations** | Connect any API - REST, WebSocket, authenticated endpoints |
| ⚡ **Automation Systems** | 24/7 bots that monitor, analyze, and act on data |
| 📊 **Data Processing** | Real-time analytics, statistical modeling, reporting |
| 🖥️ **Backend Development** | Scalable Python backends with databases and APIs |
| 🚀 **Server Deployment** | Linux setup, systemd services, monitoring, CI/CD |

---

## Production Stats

<div align="center">

| Metric | Value |
|--------|-------|
| 🏗️ Production Systems Running | **5+** |
| 🔌 API Integrations Built | **10+** |
| ⏰ System Uptime | **99.9%** |
| 🌐 Data Sources Processed | **60+** |
| 🔐 Secure Auth Implementations | **RSA-PSS, HMAC, OAuth** |

</div>

---

## Let's Work Together

<div align="center">

[![Fiverr](https://img.shields.io/badge/Hire_Me_on_Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/cloudbotdev)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Trademydream2024)

**Ready to build your next automation project? Let's talk!**

</div>
