# 🏙️ NagarIQ

### AI-Powered Public Infrastructure Intelligence Platform

> **See. Assess. Prioritize. Act.**

NagarIQ is an AI-powered platform that detects, classifies, assesses, prioritizes, and tracks public infrastructure issues such as **potholes, damaged roads, broken streetlights, overflowing drains, and damaged sidewalks**.

It transforms citizen/inspector images into actionable infrastructure intelligence for faster and smarter maintenance.

---

## 🚨 Problem

Traditional civic complaint systems often struggle with:

* Manual issue classification
* Too many duplicate complaints
* Difficulty identifying urgent problems
* Lack of geographic visibility
* Limited transparency after reporting
* Slow prioritization and response

---

## 💡 Solution

NagarIQ uses AI and contextual data to determine **what the problem is, how severe it is, and how urgently it needs attention**.

### Key Features

* 🤖 **AI Issue Detection** — Identifies infrastructure problems from images.
* ⚠️ **Severity & Safety Assessment** — Estimates severity, safety risk, and AI confidence.
* 🎯 **Context-Aware Priority Score** — Combines severity, safety, location, duplicates, exposure, and recency.
* 🔁 **Duplicate Detection** — Groups multiple reports about the same issue.
* 🗺️ **Infrastructure Map** — Visualizes reported issues geographically.
* 📊 **Authority Dashboard** — Shows active, critical, and resolved infrastructure issues.
* 👥 **Citizen Reporting** — Submit images, locations, and descriptions.
* 📢 **Status Tracking** — Track reports from submission to resolution.
* 🔍 **Explainable AI** — Shows why an issue received its priority.

---

## 🧠 Example AI Analysis

```json
{
  "issue_type": "pothole",
  "severity": 8,
  "safety_risk": 9,
  "confidence": 0.94,
  "priority_score": 91,
  "status": "under_review"
}
```

---

## 🎯 What Makes NagarIQ Different?

### Context-aware prioritization

A large pothole on a low-traffic road may be less urgent than a smaller issue near a school or busy pedestrian area.

### Community intelligence

Multiple reports about the same issue can strengthen its priority instead of creating unnecessary duplicate cases.

### Closed-loop tracking

NagarIQ goes beyond **"Report a problem"** to:

**Detect → Assess → Prioritize → Assign → Resolve → Track**

---

## 🛠️ Tech Stack

* **Frontend:** React / TypeScript
* **AI:** Multimodal AI / Computer Vision
* **Backend:** API / Server Functions
* **Database:** Structured issue & user data
* **Maps:** Geospatial issue visualization
* **Deployment:** Vercel
* **Version Control:** GitHub

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/NagarIQ.git
cd NagarIQ
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file for API credentials:

```env
AI_API_KEY=your_key_here
MAPS_API_KEY=your_key_here
DATABASE_URL=your_database_url
```

**Never commit real API keys to GitHub.**

---

## 🌍 Future Scope

* Traffic-aware priority scoring
* Predictive infrastructure maintenance
* Mobile application
* Advanced geospatial analytics
* Municipal system integration
* Automated authority notifications
* Large-scale infrastructure monitoring

---

## 🏆 Hackathon Project

**NagarIQ** was built to demonstrate how AI can transform civic infrastructure management from a **complaint-driven system into an intelligence-driven system.**

> **Intelligence for Better Cities.**

---

## 📄 License

This project is licensed under the **MIT License**.
