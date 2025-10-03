🧠 AI Finance Tracker

An AI-powered personal finance tracking and advisory application.
AI Finance Tracker helps you record income/expenses, monitor budgets, and receive AI-driven financial insights for smarter money management.

📑 Table of Contents

Overview

Tech Stack

Features

Getting Started

Project Structure

Environment Variables

Usage

Screenshots

Roadmap

Contributing

License

🔎 Overview

AI Finance Tracker is a modern web app that combines Next.js, TypeScript, and TailwindCSS with AI (OpenAI API) to simplify financial planning.
It allows users to:

Record their daily transactions.

Visualize financial health with charts and summaries.

Get personalized AI advice to optimize savings and expenses.

⚙️ Tech Stack

Next.js – Fullstack React framework

TypeScript – Type safety and maintainable code

Tailwind CSS – Utility-first styling

Drizzle ORM – Type-safe database access

OpenAI API – AI-driven financial recommendations

✨ Features

📊 Track Income & Expenses — Simple transaction logging.

💰 Budgeting Tools — Set, manage, and monitor budgets.

🤖 AI-Powered Advice — Get insights and recommendations from AI.

📱 Responsive Design — Works smoothly on mobile and desktop.

🔐 Secure Authentication — (If implemented) Sign in & manage accounts.

🚀 Getting Started
Prerequisites

Node.js (>= 18.x)

npm or yarn

Git

Installation
# Clone the repository
git clone https://github.com/Shashank07-debug/AI_Finance_Tracker.git
cd AI_Finance_Tracker

# Install dependencies
npm install

🔑 Environment Variables

Create a .env.local file in the root directory and add:

OPENAI_API_KEY=your_openai_api_key
DATABASE_URL=your_database_url
NEXT_PUBLIC_APP_URL=http://localhost:3000


(Add additional keys here if using authentication or external APIs)

▶️ Usage

Start the development server:

npm run dev


Then open http://localhost:3000
 in your browser.

For production:

npm run build
npm start

📂 Project Structure
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

📸 Screenshots

(Add screenshots of your app UI here — dashboard, AI insights, etc.)

🛣️ Roadmap

✅ Basic income/expense tracking

✅ Budget creation & monitoring

🚧 AI financial predictions (in progress)

🚧 Notifications / Alerts

🚧 Multi-user authentication

🤝 Contributing

Contributions are welcome!

Fork the project

Create a feature branch (git checkout -b feature/awesome-feature)

Commit changes (git commit -m 'Add awesome feature')

Push to branch (git push origin feature/awesome-feature)

Open a Pull Request
