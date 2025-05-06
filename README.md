# AI Book Club

An AI-guided discussion platform for books, powered by Mistral via Ollama.

## Features

- 📚 Book discussions with AI-generated questions
- 💬 Real-time chat using Socket.io
- 🤖 AI-powered insights and summaries
- 👥 User profiles and social features
- 🌙 Dark/Light mode support
- 📱 Mobile-responsive design

## Tech Stack

### Frontend
- Next.js 14
- React
- Tailwind CSS
- TypeScript
- Playwright (E2E testing)

### Backend
- Node.js
- Express
- PostgreSQL
- Socket.io
- Jest (Testing)

### AI
- Mistral via Ollama (local)
- Markdown support for AI summaries

## Development Setup

### Prerequisites
- Node.js 18+
- PostgreSQL
- Ollama with Mistral model
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/ai-book-club.git
cd ai-book-club
```

2. Install dependencies
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables
```bash
# Frontend (.env.local)
cp frontend/.env.example frontend/.env.local

# Backend (.env)
cp backend/.env.example backend/.env
```

4. Start development servers
```bash
# Start frontend
cd frontend
npm run dev

# Start backend
cd ../backend
npm run dev
```

## Testing

```bash
# Frontend tests
cd frontend
npm test

# Backend tests
cd backend
npm test

# E2E tests
npm run test:e2e
```
