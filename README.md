AI Mock Interviewer

An AI-powered mock interview platform built using React, TypeScript, and Vite. The application enables users to practice interviews with AI-generated questions and receive intelligent feedback for performance improvement.

Features
AI-Driven Interviews: Generates realistic interview questions using Google Gemini
Authentication: Secure user login via Clerk
Modern UI: Clean and responsive interface built with Shadcn UI and Tailwind CSS
Real-time Interaction: Dynamic question flow and user response handling
Feedback System: Text-to-speech based analysis for user responses
Scalable Backend: Data management using Firebase
Technology Stack
Frontend: React with TypeScript
Build Tool: Vite
Styling: Tailwind CSS
UI Components: Shadcn UI
Authentication: Clerk
AI Integration: Google Gemini
Database: Firebase
Getting Started
Prerequisites
Node.js (v18 or higher)
npm or yarn
Installation

Clone the repository:

git clone https://github.com/your-username/AI-MOCK-INTERVIEWER.git
cd AI-MOCK-INTERVIEWER

Install dependencies:

npm install

or

yarn install
Running the Application
npm run dev

Open http://localhost:5173 in your browser.

Building for Production
npm run build
How It Works
User Authentication: Users sign in using Clerk
Interview Setup: Select role or domain for interview
AI Interaction: Questions generated dynamically using Gemini AI
Response Capture: User answers are recorded and processed
Feedback Analysis: System evaluates responses and provides insights
Project Structure
ai-mock-interviewer/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   └── App.tsx
├── public/
├── package.json
├── tsconfig.json
├── vite.config.ts
└── tailwind.config.js
Environment Variables

Create a .env file in the root directory:

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_GEMINI_API_KEY=your_gemini_key
VITE_FIREBASE_API_KEY=your_firebase_key
Future Enhancements
Video-based interview simulation
Advanced AI evaluation metrics
Detailed performance analytics dashboard
Multi-language support
Integration with external job platforms