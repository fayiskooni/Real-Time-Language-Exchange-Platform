# Real-Time Language Exchange Platform

A full-stack platform connecting language learners globally via real-time text chat and video calls.

🔗 **Live:** https://livechat-videocallapp.onrender.com

---

## Features

- Discover language partners by native and target language
- Send, accept, and reject friend requests
- Real-time text chat with presence indicators
- High-quality video calls
- Profile onboarding with language, location, and bio
- Global theme switching

## Tech Stack

**Frontend:** React 19, TanStack Query, Zustand, DaisyUI, Tailwind CSS, Framer Motion

**Backend:** Node.js, Express, MongoDB, Mongoose

**Auth:** JWT via HttpOnly cookies, bcryptjs

**Real-time:** Stream Chat SDK, Stream Video SDK

## How It Works

1. User signs up and completes language onboarding
2. Dashboard shows recommended partners based on language match
3. Friend requests connect users to chat and video rooms
4. Stream SDK handles all real-time messaging and video infrastructure
5. Backend generates secure per-user Stream tokens on login

## Run Locally
```bash
# Clone the repo
git clone https://github.com/fayiskooni/YOUR_REPO_NAME

# Install dependencies
cd backend && npm install
cd ../frontend && npm install

# Add environment variables
# Backend: MONGO_URI, JWT_SECRET, STREAM_API_KEY, STREAM_SECRET
# Frontend: VITE_STREAM_API_KEY

# Run
cd backend && npm run dev
cd ../frontend && npm run dev
```
