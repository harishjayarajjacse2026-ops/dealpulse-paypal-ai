# DealPulse AI 🏷️⚡

> AI-powered e-commerce price monitoring agent with automated PayPal v2 sandbox checkout.

DealPulse AI continuously monitors product price drops across online retailers and automatically triggers a hands-free purchase using PayPal's sandbox API as soon as the target price threshold is reached.

---

## 🌟 Key Features
- **URL Price Scraping & Analysis:** Real-time extraction of product meta-data and live price values.
- **AI Purchasing Agent:** Evaluates item discount validity and optimal price buy zones using OpenAI.
- **Automated PayPal Checkout:** Executes automated authorization and payment capture via PayPal Orders API v2 when target thresholds are hit.
- **Custom Budget Caps:** Strict user-defined maximum spend limits to prevent accidental overspending.

---

## 🛠️ Tech Stack
- **Frontend:** React, Tailwind CSS, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Integrations:** PayPal Orders REST API (v2), OpenAI API

---

## ⚙️ How PayPal & AI Are Used

### 1. PayPal Integration
- **Orders API (v2):** Used to initialize, authorize, and capture transaction orders.
- **Sandbox Environment:** Evaluates simulated checkout scenarios automatically when price conditions evaluate to `TRUE`.

### 2. AI Integration
- Uses **OpenAI** model logic to analyze historical price trends, parse unstructured HTML elements, and verify product authenticity before triggering payment flows.

---

## 🚀 Quick Setup & Installation

### Prerequisites
- Node.js (v18+)
- MongoDB running locally or MongoDB Atlas URI
- PayPal Developer Account (Client ID & Secret from Sandbox)

### 1. Clone the Repository
```bash
git clone [https://github.com/harishjayarajjacse2026-ops/dealpulse-paypal-ai.git](https://github.com/harishjayarajjacse2026-ops/dealpulse-paypal-ai.git)
cd dealpulse-paypal-ai
