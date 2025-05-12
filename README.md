Interactive Periodic Table with AI Chemistry Assistant 
This project is an interactive periodic table designed for educational use in schools. Each element tile is dynamic—clicking or tapping a tile connects to qwen/qwen-2.5-72b-instruct model via the A2A protocol, providing detailed explanations about the element. Students can ask follow-up questions and engage with a state-of-the-art AI model as much as they need. The AI has been fine-tuned with a custom temperature setting and prompted to guard against jailbreaks, ensuring safety for school environments.
Features
Interactive Periodic Table: Click any element tile to learn about it via an AI-powered chemistry assistant.

AI Integration: Powered by qwen/qwen-2.5-72b-instruct model with A2A and MCP capabilities protocol for real-time, conversational learning.

Student-Friendly: Students can ask unlimited follow-up questions, with the AI tailored for educational use and safety.

Responsive Design: Works seamlessly on desktop and mobile devices.

Theming: Supports dark and light modes for better accessibility.

Smooth Animations: Element tiles and UI transitions are enhanced with subtle animations.

Tech Stack
Frontend Framework: Next.js 14 with static exports for fast, SEO-friendly performance.

UI Library: React 18 with hooks for state management.

Styling: Tailwind CSS with shadcn/ui components (built on Radix UI primitives) for a modern, accessible UI.

TypeScript: Ensures type safety across the application.

Animation: Framer Motion for smooth transitions and effects.

Database/Backend: Supabase for lightweight data management.

AI Integration: qwen/qwen-2.5-72b-instruct for the chemistry assistant.

Icons: Lucide React for clean, scalable SVG icons.

Form Handling: React Hook Form with Zod validation for any user inputs.

Theming: Dark/light mode support via next-themes.

Getting Started
Prerequisites
Node.js (v18 or later)

npm or yarn

A Supabase account and project for backend setup

OpenRouter API and Open Ai end points and SDK

Installation
Clone the repository:
bash

git clone https://github.com/heybattle1/elementalz


Install dependencies:
bash

npm install

Set up environment variables:
Create a .env.local file in the root directory.

Add your Supabase and Gemini API credentials:
env

NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
GEMINI_API_KEY=your-gemini-api-key

Run the development server:
bash

npm run dev

Open http://HayHuntDB.online for the function version

Build for production (static export):
bash

npm run build
npm run export

The static files will be generated in the out directory, ready for deployment.

Deployment
Deploy the static site to any hosting provider (e.g., Vercel, Netlify, or Google Cloud Platform).

Ensure your Supabase backend and Gemini API are accessible in production.

Usage
Navigate the periodic table and click on any element tile.

The AI assistant qwen/qwen-2.5-72b-instruct will provide a detailed explanation of the element.

Students can ask follow-up questions in a conversational format.

Toggle between dark and light modes using the theme switcher.

Safety Notes
The AI model has been adjusted for school use, with a custom temperature setting to ensure appropriate responses.

Jailbreak protection has been implemented to maintain a safe learning environment.

Contributing
This project is designed for educational use, but contributions are welcome! Please submit a pull request or open an issue to discuss improvements.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments
Built with  for students and educators.

Thanks to the open-source community for tools like Next.js, Tailwind CSS, and Supabase.

