Need A Hand 2.0
AI-Powered Platform Connecting Customers, Local Workers, and Artisans

“Empowering India’s Skilled Hands — Hire, Create, and Inspire through AI.”

🚀 Installation & Setup
# Clone repository
git clone https://github.com/your-username/Need-A-Hand-2.0.git

# Navigate into project
cd Need-A-Hand-2.0

# Install dependencies
npm install    # for backend
flutter pub get   # or npm install for frontend

# Run backend server
npm start

# Run Flutter/React app
flutter run   # or npm start


📌 Overview

Need A Hand 2.0 is an AI-driven digital marketplace designed to bridge the gap between customers, local service workers, and traditional artisans.
It combines the convenience of e-commerce with the authenticity of local skill — enabling users to book services, purchase handmade products, and experience the stories behind every craft.

The platform leverages Google Cloud’s Generative AI, Vertex AI, and Firebase to deliver personalized recommendations, fair pricing, and storytelling automation.

🎯 Objectives

Empower India’s informal and artisan workforce through digital visibility and fair income.

Provide customers with trusted, verified, and affordable services/products.

Integrate AI tools to generate multilingual marketing stories for artisans.

Connect traditional craftsmanship with modern digital commerce.

🧩 Key Features
👥 For Customers

Search and hire verified local workers (plumbers, electricians, cleaners, etc.).

Browse and buy authentic handmade crafts directly from artisans.

Watch short AI-generated videos telling each artisan’s story.

Real-time order tracking, secure UPI payments, and reviews.

🔧 For Workers

Skill-based job matching with nearby customers.

Smart earnings dashboard with AI-suggested pricing.

Verified profiles with ratings, job history, and direct payouts.

🎨 For Artisans

Create digital shops to sell crafts and handmade goods.

AI-powered Story Studio to auto-generate short promotional videos.

Multilingual captions and social-share options for wider reach.

Sales analytics and income tracking.

🧠 AI & Cloud Integrations
Function	Service
Smart Matching & Pricing	Vertex AI / Gemini
Story Generation	Google Cloud Generative AI + Speech-to-Text + Vision API
Authentication & Database	Firebase Auth + Firestore
Hosting & Scalability	Google Cloud Run / Firebase Hosting
Notifications	Firebase Cloud Messaging
Payments	Razorpay / Google Pay API
Offline Access	Twilio (SMS & IVR)
⚙️ System Architecture
+-----------------------+         +-----------------------+         +----------------------------+
|     User Interfaces   | <-----> |  Application Backend  | <-----> |  AI & Cloud Infrastructure |
|-----------------------|         |-----------------------|         |----------------------------|
| Customer App          |         | Node.js APIs          |         | Vertex AI (Matching, Story)|
| Worker App            |         | Firebase Auth         |         | Firestore DB              |
| Artisan App           |         | Cloud Functions       |         | Google Cloud Hosting      |
+-----------------------+         | Payment Gateway       |         | Twilio (Offline Support)  |
                                  +-----------------------+         +----------------------------+

🏗️ Tech Stack

Frontend: Flutter / React Native
Backend: Node.js, Firebase, Google Cloud Functions
Database: Firestore
AI Models: Gemini / Vertex AI
Payments: Razorpay / Google Pay
Cloud Platform: Google Cloud
Design & Prototyping: Figma, Canva
Version Control: GitHub

🧭 Application Flow

User Registration & Role Selection → Customer, Worker, or Artisan.

AI-Driven Discovery → Search for services or crafts with personalized recommendations.

Booking or Buying → Instant job booking or craft purchase.

AI Story Generation → Artisans create short stories promoting their crafts.

Tracking & Payment → Secure UPI payments and real-time tracking.

Review & Reward → Ratings improve trust and ranking.

🧱 Folder Structure (Suggested)
Need-A-Hand-2.0/
│
├── frontend/               # Flutter or React Native app
│   ├── src/
│   ├── assets/
│   ├── components/
│   └── pages/
│
├── backend/
│   ├── server.js
│   ├── firebaseConfig.js
│   ├── routes/
│   ├── models/
│   └── controllers/
│
├── ai/
│   ├── story_generation.py
│   ├── matching_engine.py
│   └── pricing_ai.py
│
├── docs/
│   ├── architecture-diagram.png
│   ├── process-flow.png
│   └── presentation.pdf
│
├── README.md
└── LICENSE

🚀 Installation & Setup
# Clone repository
git clone https://github.com/your-username/Need-A-Hand-2.0.git

# Navigate into project
cd Need-A-Hand-2.0

# Install dependencies
npm install    # for backend
flutter pub get   # or npm install for frontend

# Run backend server
npm start

# Run Flutter/React app
flutter run   # or npm start

💡 Future Enhancements

AI chatbot assistant for customer support.

Blockchain-based artisan product authenticity verification.

Predictive scheduling for high-demand services.

Multilingual voice-based app interface.

Integration with Digital India and e-Shram databases.

📈 Impact Goals
Stakeholder	Impact
Workers	Increased income, verified employment
Artisans	Global reach & cultural preservation
Customers	Trusted, affordable services
Society	Reduced unemployment, digital inclusion
👥 Team

Team Name: Tech Fists
Project: Need A Hand 2.0
Hackathon: Google Cloud Gen AI Exchange Hackathon


🏁 License

This project is licensed under the MIT License — feel free to use, modify, and improve it with proper attribution.

🌐 Live Demo

🔗 Figma Prototype: https://jury-shed-32753804.figma.site

💬 Contact

For queries or collaborations:
📧 teamtechfists@gmail.com
