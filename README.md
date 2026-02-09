# **MailPlus** ✉️✨

## **GitHub Repository Description:**
```
AI-powered inbox assistant. Login with Google OAuth, see top 10 prioritized emails, and get AI summaries that extract dates/times/venues so you never miss important details.
```

---

# **README.md**

<div align="center">

# **MailPlus** 📧⚡

**Never miss important details in your emails again**

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Google OAuth](https://img.shields.io/badge/Google%20OAuth-2.0-white?style=for-the-badge&logo=google)](https://developers.google.com/identity)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)

</div>

## **🌟 Features**

<div align="center">

| 🔐 Secure Login | 📊 Smart Dashboard | 🤖 AI Summarization |
|:---:|:---:|:---:|
| One-click Google OAuth | Top 10 priority emails | Extract key details |
| **📅 Date Detection** | **📍 Venue Finder** | **⏰ Time Tracking** |
| Never miss deadlines | Find event locations | Track meeting times |

</div>

## **📸 Preview**

<div align="center">

![MailPlus Dashboard](https://via.placeholder.com/800x450/1e293b/ffffff?text=MailPlus+Dashboard+Preview)
*Clean, modern interface showing prioritized emails with AI summaries*

</div>

## **🚀 Quick Start**

### **Prerequisites**
- Node.js 18+ & npm
- Google Cloud Project with OAuth credentials
- OpenAI API key (or alternative)

### **Installation**
```bash
# Clone the repository
git clone https://github.com/yourusername/mailplus.git
cd mailplus

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your credentials

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see MailPlus in action! 🎉

## **🛠️ Tech Stack**

<div align="center">

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Framework** | Next.js 15 (App Router) | Full-stack React framework |
| **Language** | TypeScript | Type safety & better DX |
| **Auth** | NextAuth.js + Google OAuth | Secure authentication |
| **Email API** | Gmail API | Email fetching & management |
| **AI** | OpenAI GPT-4/3.5 | Email summarization |
| **Styling** | Tailwind CSS + shadcn/ui | Modern UI components |
| **Icons** | Lucide React | Beautiful icons |
| **Deployment** | Vercel | Optimized hosting |

</div>


## **🔧 Configuration**

### **1. Google Cloud Setup**
1. Create a project at [Google Cloud Console](https://console.cloud.google.com)
2. Enable **Gmail API** and **Google OAuth 2.0**
3. Create OAuth 2.0 credentials
4. Add authorized redirect URI: `http://localhost:3000/api/auth/callback/google`

### **2. Environment Variables**
```env
# Authentication
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_secret_key

# AI Services
OPENAI_API_KEY=your_openai_key
# OR
ANTHROPIC_API_KEY=your_anthropic_key

# Optional: Redis for session storage
REDIS_URL=your_redis_url
```

