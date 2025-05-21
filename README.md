# AI-Chatbot
Project Overview
Vercel AI Chatbot is a fully functional AI-powered chatbot application built using Next.js 13 and the Vercel AI SDK. It integrates OpenAI’s large language models to enable intelligent and dynamic conversations, and is styled with Tailwind CSS for a clean user experience.

 aimed at exploring LLM integration in modern web applications and deploying real-time AI features using Vercel.

✨ Features
💬 AI-powered chat interface using OpenAI's GPT models

🚀 Built with Next.js 13 (App Router)

🧠 Handles streaming responses from OpenAI

🎨 Styled with Tailwind CSS

⚡ Fast, serverless, and deployable on Vercel

🔒 Environment-variable-based API key configuration

🛠 Tech Stack
Framework: Next.js 13 (React)

Styling: Tailwind CSS

AI Backend: OpenAI API (via Vercel AI SDK)

Hosting: Vercel

Language: TypeScript

📁 Folder Structure
php
Copy
Edit
vercel-ai-chatbot/
│
├── app/                      # App directory (Next.js 13)
│   ├── api/                  # Edge function for chat streaming
│   └── page.tsx             # Main Chat UI
│
├── components/              # React components like Chat, Header, etc.
│
├── lib/                     # Utility functions and config
│
├── public/                  # Static files
│
├── styles/                  # Tailwind & global CSS
│
├── .env.local.example       # Environment variable template
├── package.json
└── README.md
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/vercel-ai-chatbot.git
cd vercel-ai-chatbot
2. Install Dependencies
bash
Copy
Edit
npm install
3. Set Up Environment Variables
Create a .env.local file in the root directory:

env
Copy
Edit
OPENAI_API_KEY=your-openai-api-key
(Replace your-openai-api-key with your actual OpenAI secret key.)

4. Run the Development Server
bash
Copy
Edit
npm run dev
Visit http://localhost:3000 in your browser to interact with the chatbot.

🌐 Deployment on Vercel
Push your code to GitHub.

Go to vercel.com and import the repo.

Set the environment variable OPENAI_API_KEY in Vercel dashboard.

Deploy — your chatbot is live!
