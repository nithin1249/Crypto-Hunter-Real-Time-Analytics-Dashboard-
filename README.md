# Crypto-Hunter: Full-Stack Digital Asset Analytics Dashboard

A professional-grade, full-stack cryptocurrency platform featuring real-time data streaming, secure user authentication, and persistent cloud storage. This application provides a personalized experience for monitoring market trends and managing asset watchlists using a robust MERN-style architecture.

## 🚀 Live Demo
**[View Live Project](https://crypto-hunter.netlify.app/)**

---

## 🏗️ System Architecture

Crypto-Hunter is built using a **decoupled Full-Stack architecture**, ensuring a clear separation of concerns between the user interface and the data management layer:

* **Frontend:** A responsive **React.js** Single Page Application (SPA) utilizing the **Context API** for global state management.
* **Backend & Logic:** Custom **Node.js** and **Express.js** logic to handle API orchestration and user data routing.
* **Storage Layer:** **MongoDB** for high-availability user data storage and **Firebase Firestore** for real-time synchronization.
* **Authentication:** Hybrid identity management via **Firebase Auth**, supporting **Google OAuth** and traditional Email/Password flows.
* **Data Sourcing:** High-frequency data ingestion from the **CoinGecko API**.

---

## 🛠️ Engineering Highlights

- **Custom Backend Architecture:** Engineered a **Node.js** server to manage user data, moving beyond a client-only dashboard to a fully persistent web application.
- **Secure User Storage:** Implemented a **MongoDB** schema to store and synchronize personalized user watchlists, ensuring data is saved and accessible across all user sessions and devices.
- **Identity & Access Management:** Integrated **Google OAuth** via Firebase to offload sensitive credential management to a secure provider while maintaining internal user profiles.
- **Global State Optimization:** Orchestrated a centralized **React Context** store to manage complex states—including currency localization (USD/INR) and authentication status—eliminating prop-drilling.
- **Performance-Tuned Rendering:** Utilized React Hooks (`useMemo`, `useCallback`) to manage high-frequency API polling, preventing unnecessary re-renders during volatile market updates.

---

## 📋 Core Features

- **Personalized Watchlists:** Allows authenticated users to save assets to their profile; data is persisted in the cloud and updated in real-time.
- **Dynamic Charting Engine:** Built interactive price-trend visualizations using **Chart.js**, supporting multiple timeframes (24h, 30d, 1y).
- **Interactive Carousel:** A high-performance horizontal scroller showcasing trending coins with real-time price percentage changes.
- **Intelligent Search & Filtering:** Custom filtering logic for instant asset discovery across a paginated list of 100+ cryptocurrencies.
- **Automated CI/CD:** Continuous deployment pipeline via **Netlify**, ensuring the production environment is automatically updated with every GitHub commit.

---

## 🏗️ Tech Stack

* **Frontend:** React.js, Material UI (MUI), Chart.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, Firebase Firestore
* **Authentication:** Firebase Auth (Google OAuth)
* **API Integration:** Axios
* **Deployment:** Netlify