An AI-powered mock interview platform built using modern web technologies. Practice interviews, get real-time AI-generated questions, and receive feedback to improve your performance.

✨ Features
⚛️ Built with React + TypeScript
⚡ Powered by Vite for fast performance
🎨 Clean UI using Shadcn UI + Tailwind CSS
🔐 Authentication via Clerk
🤖 AI-generated questions using Google Gemini
🔊 Text-to-Speech feedback analysis
🔥 Backend & database with Firebase

📁 Project Structure
src/
 ├── components/
 ├── pages/
 ├── lib/
 ├── hooks/
 └── App.tsx

🛠️ Tech Stack
React + TypeScript
Vite
Tailwind CSS
Shadcn UI
Clerk Auth
Google Gemini API
Firebase

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/AI-MOCK-INTERVIEWER.git
cd AI-MOCK-INTERVIEWER
2. Install dependencies
npm install
3. Run the development server
npm run dev

👉 Open: http://localhost:5173

🔐 Environment Variables

Create a .env file in root and add:

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_GEMINI_API_KEY=your_gemini_key
VITE_FIREBASE_API_KEY=your_firebase_key

🚀 Build for Production
npm run build

📌 Future Improvements
🎥 Video interview support
📊 Detailed analytics dashboard
🧠 More AI evaluation metrics
🌐 Multi-language support