# ET AI Copilot

A COMPLETE, FULL-STACK, PRODUCTION-READY web application for financial assistance with an intelligent AI engine.

## 🧱 Setup & Run Instructions

### 1. Prerequisites
- Node.js installed (v16+)
- OpenAI API Key (added to `backend/.env`)

### 2. Initialization
Navigate to the root project folder:
\`\`\`bash
cd et-ai-copilot
\`\`\`

#### Terminal 1: Backend Setup
\`\`\`bash
cd backend
npm install
node server.js
\`\`\`
The server should run on http://localhost:5000 and the SQLite database will be initialized automatically.

#### Terminal 2: Frontend Setup
\`\`\`bash
cd frontend
npm install
npm run dev
\`\`\`
The Vite dev server should start on http://localhost:5173.

### 3. Usage
- Go to `http://localhost:5173` in your browser.
- Register a new account.
- Login with your credentials.
- Use the dashboard or start a chat with the ET AI Copilot.

## ⚙️ Features
- **Authentication**: JWT & bcrypt based secure auth flow with SQLite storage.
- **AI Chat Agent**: OpenAI GPT-4o-mini integration tailored as a financial assistant.
- **Smart Recommendations Engine**: Suggests specific platform tools based on keywords (*invest*, *loan*, *learn*).
- **Responsive UI**: Glassmorphism, Tailwind CSS, and Framer Motion for a premium dark mode experience.
- **Session History**: All chats are synchronized and saved to the SQLite database.
