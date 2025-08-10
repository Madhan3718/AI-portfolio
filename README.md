# Brand new AI Portfolio 🤖

Static portfolios are *so last season*.  
This is **not just a portfolio** — it’s an **AI-powered conversation** tailored to whoever’s visiting.  
Instead of making you scroll endlessly, my portfolio **adapts to you**.  

💬 **Ask me anything** — my AI avatar responds instantly.

---

## 🌟 What Can You Ask?

- 🧠 **Tech Recruiter?** → Ask about my tech stack & project results.  
- 💻 **Developer?** → Dive into my code, logic, and problem-solving mindset.  
- 🧑‍🤝‍🧑 **Friend or Family?** → See what I’ve been building lately.  

---

## 🚀 Live Demo

👉 **[https://madan-dev.netlify.app/](https://madhan-dev.netlify.app/)**  
*What will you ask first?*

---

## 🛠 Tech Stack

- **Node.js** (v18 or higher)
- **npm** (Package Manager)
- **Google Gemini API** (AI chat functionality)
- **Vite** (Build tool)
- **React + TypeScript** (Frontend framework)
- **Tailwind CSS** (Styling)

## 🔧 Environment Setup

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd AI-powered-portfolio-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```bash
   # Google Gemini API Key
   # Get your API key from: https://makersuite.google.com/app/apikey
   VITE_GOOGLE_API_KEY=your_google_api_key_here
   ```

   **⚠️ Security Note:** Never commit your `.env` file to version control. It's already added to `.gitignore`.

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173`

## 🔐 Security

This project uses environment variables to securely store API keys. The `.env` file is automatically ignored by Git to prevent accidental exposure of sensitive credentials.
