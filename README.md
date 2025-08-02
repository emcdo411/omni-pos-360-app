# 🔄 OmniPOS360

> A mobile-first, AI-augmented Point of Sale (POS) simulation built with React Native and Expo — built to demonstrate enterprise-ready POS capabilities for modern TPM-led conversations.

![React Native](https://img.shields.io/badge/Frontend-React%20Native-61DAFB?style=for-the-badge&logo=react)
![Expo](https://img.shields.io/badge/Mobile-Expo-000020?style=for-the-badge&logo=expo)
![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss)
![Node.js](https://img.shields.io/badge/API-Node.js-339933?style=for-the-badge&logo=nodedotjs)
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge&logo=firebase)
![Supabase](https://img.shields.io/badge/Database-Supabase-3ECF8E?style=for-the-badge&logo=supabase)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions)
![Docker](https://img.shields.io/badge/DevOps-Docker-2496ED?style=for-the-badge&logo=docker)
![AI Simulated](https://img.shields.io/badge/AI%20Modules-Simulated-blueviolet?style=for-the-badge&logo=openai)

---

## 📚 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Architecture](#-architecture)
- [AI Modules](#-ai-modules)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
- [For TPMs](#-for-tpms)
- [License](#-license)

---

## 📖 Overview

**OmniPOS360** is a simulated enterprise-grade POS solution tailored for modern retail or food service operations. Designed for both mobile and web environments, it showcases:

- **Offline-first sales and sync simulation**
- **Real-time dashboards**
- **AI-augmented business intelligence**
- **TPM-ready design language**

---

## ✨ Features

- 🔐 Role-based login (Cashier / Manager / Admin)
- 🛒 Product Catalog + QR/Barcode Scanning
- 🧾 Checkout Simulation w/ Tax, Receipt & Sync
- 🚫 Offline Mode with Queueing + Re-Sync
- 📊 Real-Time AI Dashboard with Insights
- 📦 Inventory + Daily Sales Closeout Module

---

## 🧠 AI Modules

> All modules simulated with mock JSON responses, toggled via AI Mode switch.

| Module              | Description                                      |
|---------------------|--------------------------------------------------|
| Sales Forecasting   | Prophet-style trend prediction from SKU logs     |
| Fraud Detection     | KNN or Isolation Forest for anomaly flagging     |
| Customer Clustering | K-Means on recent purchase and visit frequency   |

---

## 🏗️ Architecture

```mermaid
graph TD
  A[Mobile App - React Native]
  B[Backend API - Node Express]
  C[Auth Service - Firebase]
  D[Database - Supabase or PostgreSQL]
  E[AI Engine - Mock Logic]
  F[Sales Forecasting]
  G[Anomaly Detection]
  H[Customer Clustering]
  I[Dashboard - WebView or RN Web]

  A --> B
  B --> C
  B --> D
  B --> E
  E --> F
  E --> G
  E --> H
  D --> I
  A --> I
````

---

## 🧩 Tech Stack

![React Native](https://img.shields.io/badge/Frontend-React%20Native-61DAFB?style=for-the-badge\&logo=react)
![Expo](https://img.shields.io/badge/Mobile-Expo-000020?style=for-the-badge\&logo=expo)
![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwindcss)
![Node.js](https://img.shields.io/badge/API-Node.js-339933?style=for-the-badge\&logo=nodedotjs)
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge\&logo=firebase)
![Supabase](https://img.shields.io/badge/Database-Supabase-3ECF8E?style=for-the-badge\&logo=supabase)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=for-the-badge\&logo=githubactions)
![Docker](https://img.shields.io/badge/DevOps-Docker-2496ED?style=for-the-badge\&logo=docker)
![AI Simulated](https://img.shields.io/badge/AI%20Modules-Simulated-blueviolet?style=for-the-badge\&logo=openai)

---

## 🖼️ Screenshots

### 📊 Dashboard Overview

Displays real-time metrics on daily sales, items sold, customers, and growth — optimized for quick role-based decisioning.

![Dashboard](https://raw.githubusercontent.com/yourusername/omnipos360/main/assets/screenshots/Screenshot%202025-08-01%20224416.png)

---

### 🧾 Point of Sale Workflow

Simulates real-world cashier checkout interaction with dynamic pricing, tax calculation, and itemized cart view.

![Point of Sale](https://raw.githubusercontent.com/yourusername/omnipos360/main/assets/screenshots/Screenshot%202025-08-01%20224500.png)

---

### 🧪 Barcode Scanner Module

Simulated scanner that mimics retail input hardware, includes scan logs and quick-code demos.

![Barcode Scanner](https://raw.githubusercontent.com/yourusername/omnipos360/main/assets/screenshots/Screenshot%202025-08-01%20224957.png)

---

## 🚀 Getting Started

```bash
# Clone
git clone https://github.com/yourusername/omnipos360.git
cd omnipos360

# Install dependencies
npm install

# Run in Expo
npx expo start
```

---

## 🧭 For TPMs

> Real-World Questions Answered in the README supplement:

* How does the app handle internet downtime in stores?
* How scalable is this architecture for 17+ locations?
* Where are the failover points in the sync logic?
* How are AI outputs validated in mock pipelines?
* Could the AI modules be externalized via microservices?

Also includes a **Notion PDF** titled:

📌 *"If I Were the TPM Overseeing a 17-Store POS Rollout..."*

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

> Designed with real-world TPM, AI productization, and mobile performance in mind.
> Inspired by the future of embedded analytics, agent workflows, and AI-first customer experiences.

```

---

🔧 Replace `yourusername` in the raw URLs with your actual GitHub username (e.g., `emcdo411`) once you push the screenshots to the appropriate repo path:  
`/assets/screenshots/`.

Let me know if you want me to generate those image paths automatically or create the zipped `assets/screenshots` folder for you to upload.
```

