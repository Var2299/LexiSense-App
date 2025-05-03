# 🚀 LexiSense – Your Ultimate AI-Powered Book Discovery & Reading Planner 📚🤖

**LexiSense** is a full-stack reading companion built for modern readers and developers. It lets you:
- 🔍 **Discover & Search** thousands of books via Google Books API  
- 📈 **Track Trending** reads with real-time popularity ranking  
- 🧠 **AI-Driven Planner** crafting a 7-day customized reading schedule based on your available time, interests, and number of books
- 🤖 Powered by **Groq’s LLaMA 3–70B** model for blazing-fast, intelligent reading plans 
- ⏱️ **Dynamic Time Allocation** where each day’s split is unique—no two days look the same  
- 💡 **Reflective Prompts** with daily takeaways and micro-questions to deepen engagement  
- ⚙️ **Easy Deploy** on Vercel (frontend) and Render/Vercel (backend) with environment-based configuration  

---

![image](https://github.com/user-attachments/assets/0435c534-e878-4394-9d9f-b5a4e877fd3a)

![image](https://github.com/user-attachments/assets/03af3d9d-04a6-40e0-a962-9212161fe04c)

![image](https://github.com/user-attachments/assets/90f96768-737c-4af2-bbb1-12995bc77cfa)

## 🌟 Key Features

| Feature               | Description                                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------|
| 🔎 Book Search        | Seamless search powered by Google Books API                                                                           |
| 📊 Trending Dashboard | View and update book popularity in real-time with dynamic ranking                                                      |
| 🤖 AI Reading Planner | • **Time-Based**: Specify minutes/day<br>• **Book Count**: Pick 1–5 trending books<br>• **Unique Splits**: Vary daily allocations<br>• **Reflection**: Rate engagement & highlight favorite lines |

---

## 🏗️ Tech Stack

- **Frontend**: React • React Router • CSS Glassmorphism • Responsive Grid  
- **Backend**: Node.js • Express • MongoDB Atlas • Mongoose • Groq AI SDK (Llama3-70B)  
- **APIs**: Google Books API • Groq Chat Completions  
- **Deployment**: Vercel (frontend SSR & CDN) • Render/Vercel Functions (backend)  

---

## ⚡ Quick Start

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YourUsername/lexisense.git
   cd lexisense

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   cp .env.example .env          # set MONGODB_URI & GROQ_API_KEY
   npm start

3. **Frontend Setup**
   ```bash
   cd ../frontend
   npm install
   npm start

## 🚀 Deploy

1. **Push** your code to GitHub  
2. **Connect** the **frontend** directory to Vercel for automatic builds & CDN deployment  
3. **Connect** the **backend** to Vercel Functions or Render for serverless API hosting  

---

## 💬 Contributions & Feedback

We 🎉 welcome your ideas! Open an issue or submit a PR to help us add:

- 📈 **More analytics** (reading streaks, progress charts)  
- 🎨 **Enhanced UI themes** (dark/light mode, accessibility support)  
- 🔧 **Additional AI features** (genre-specific guides, audiobook sync)  
