
---

# 🧠 AI Finance Tracker

An AI-powered personal finance tracking and advisory application.
AI Finance Tracker helps you record income/expenses, monitor budgets, and receive AI-driven financial insights for smarter money management.

---

## 📑 Table of Contents

* [Overview](#-overview)
* [Tech Stack](#-tech-stack)
* [Features](#-features)
* [Getting Started](#-getting-started)
* [Project Structure](#-project-structure)
* [Environment Variables](#-environment-variables)
* [Usage](#-usage)
* [Screenshots](#-screenshots)
* [Roadmap](#-roadmap)
* [Contributing](#-contributing)
* [License](#-license)

---

## 🔎 Overview

**AI Finance Tracker** is a modern web app that combines **Next.js, TypeScript, and TailwindCSS** with AI (OpenAI API) to simplify financial planning.

It allows users to:

* Record their daily transactions.
* Visualize financial health with charts and summaries.
* Get personalized AI advice to optimize savings and expenses.

---

## ⚙️ Tech Stack

* **Next.js** – Fullstack React framework
* **TypeScript** – Type safety and maintainable code
* **Tailwind CSS** – Utility-first styling
* **Drizzle ORM** – Type-safe database access
* **OpenAI API** – AI-driven financial recommendations

---

## ✨ Features

* 📊 **Track Income & Expenses** — Simple transaction logging.
* 💰 **Budgeting Tools** — Set, manage, and monitor budgets.
* 🤖 **AI-Powered Advice** — Get insights and recommendations from AI.
* 📱 **Responsive Design** — Works smoothly on mobile and desktop.
* 🔐 **Secure Authentication** — (If implemented) Sign in & manage accounts.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js** (>= 18.x)
* **npm** or **yarn**
* **Git**

### Installation

```bash
# Clone the repository
git clone https://github.com/Shashank07-debug/AI_Finance_Tracker.git
cd AI_Finance_Tracker

# Install dependencies
npm install
```

---

## 🔑 Environment Variables

Create a `.env.local` file in the root directory and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_PUBLIC_OPENAI_API_KEY=your_openai_api_key

```

*(Add additional keys here if using authentication or external APIs)*

---

## ▶️ Usage

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

For production:

```bash
npm run build
npm start
```

---

## 📂 Project Structure

```
AI_Finance_Tracker/
│── app/                # Next.js routes & pages
│── components/         # Reusable UI components
│── lib/                # Helper libraries
│── utils/              # Utility functions
│── public/             # Static assets
│── drizzle.config.js   # Database config
│── next.config.mjs     # Next.js configuration
│── tailwind.config.js  # Tailwind CSS configuration
│── package.json        # Project dependencies
```

---

## 📸 Screenshots

*(Add screenshots of your app UI here — dashboard, AI insights, etc.)*

---

## 🛣️ Roadmap

* ✅ Basic income/expense tracking
* ✅ Budget creation & monitoring
* 🚧 AI financial predictions (in progress)
* 🚧 Notifications / Alerts
* 🚧 Multi-user authentication

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create a feature branch (`git checkout -b feature/awesome-feature`)
3. Commit changes (`git commit -m 'Add awesome feature'`)
4. Push to branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request

---


