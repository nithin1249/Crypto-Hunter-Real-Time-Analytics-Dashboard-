# Crypto-Hunter: Real-Time Digital Asset Analytics

A high-performance, responsive cryptocurrency tracking dashboard built with React and Material UI. This application provides real-time market data visualization, price trend analysis, and portfolio monitoring tools using a specialized modular architecture.

## 🚀 Live Demo
**[View Live Project](https://crypto-hunter.netlify.app/)**

---

## 🛠️ Engineering Highlights

- **Real-Time Data Streams:** Integrated with the CoinGecko API to fetch live market prices, market caps, and 24h volume for over 100+ cryptocurrencies.
- **Dynamic Data Visualization:** Implemented interactive historical price charts using **Chart.js**, featuring custom tooltips and responsive scaling for various timeframes (24h, 30d, 1y).
- **Global State Management:** Optimized data flow using the **React Context API** to handle currency switching (e.g., USD to INR) globally without prop-drilling.
- **Advanced UI/UX:** Built with **Material UI (v4)** featuring a custom dark-mode theme, glassmorphism effects, and a custom-engineered search filter for instant asset discovery.
- **Performance Optimization:** Utilized React Hooks (`useEffect`, `useMemo`) to manage API polling intervals and prevent unnecessary re-renders during high-frequency data updates.

## 📋 Core Features

- **Interactive Carousel:** A high-performance horizontal scroller showcasing trending coins with real-time price percentage changes.
- **Comprehensive Asset Profiles:** Detailed pages for individual coins featuring historical data charts and market statistics.
- **Responsive Data Tables:** A paginated, searchable list of cryptocurrencies with real-time sorting capabilities.
- **Currency Localization:** Support for multiple fiat currencies with automatic symbol and price formatting.

## 🏗️ Tech Stack

* **Frontend Framework:** React.js
* **Styling & UI Components:** Material UI (MUI)
* **Charts & Graphs:** Chart.js / React-Chartjs-2
* **API Integration:** Axios
* **Routing:** React Router DOM
* **Deployment:** Netlify