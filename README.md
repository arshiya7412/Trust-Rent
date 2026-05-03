# TrustRent 🏢

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://trust-rent.netlify.app/)

**TrustRent** is a modern, escrow-based rental management platform designed to bridge the trust gap between landlords and tenants. It features AI-driven insights, transparent payment tracking, automated receipt generation, and a centralized hub for managing properties and maintenance complaints.

## 🚀 Live Application
Check out the live deployment here: **[TrustRent on Netlify](https://trust-rent.netlify.app/)**

## ✨ Key Features
- **Dual Role Dashboards**: Specialized views depending on whether you log in as a Landlord or a Tenant.
- **AI Assistant**: Built-in chatbot powered by the Gemini API to help answer platform and rental-related queries contextually.
- **Payment Management**: Tenants can easily log rent payments, while landlords track payment histories and cash flows.
- **Invoice Generation**: Automated, downloadable PDF receipts for rent payments.
- **Maintenance & Complaints**: Real-time logging and resolution tracking for property issues.
- **Analytics & Statistics**: Visual insights into rental revenue and property performance using interactive Recharts.

## 🛠 Tech Stack
- **Frontend Framework**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Data Visualization**: Recharts
- **PDF Generation**: jsPDF
- **AI Integration**: Google Gen AI SDK (Gemini)
- **Deployment**: Netlify

## ⚙️ Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/trust-rent.git
   cd trust-rent
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your Gemini API key so the AI features will work:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## 🌍 Deployment to Netlify
This project is configured perfectly for Netlify. A `netlify.toml` file is included in the root to handle Single Page Application (SPA) routing appropriately (redirecting `/*` to `/index.html`).

**Don't forget:** When deploying, go to your Netlify dashboard under **Site configuration > Environment variables** and add your `GEMINI_API_KEY` so the AI Chatbot functions in production!
