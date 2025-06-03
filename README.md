# 🎯 SensAi – Your AI-Powered Career Coach

SensAi is a smart, personalized career assistant designed to help you grow in your industry with the power of AI. Whether you're trying to stay up to date with industry trends, prepare for job interviews, or write killer cover letters — SensAi has your back.

Built with modern tools like **Next.js**, **Clerk**, **Shadcn UI**, **Inngest**, and **Gemini AI**, this app delivers a fullstack experience that helps users take control of their career journey.

---

## ✨ Features

- 🔍 **Weekly Industry Insights**  
  Input your **industry**, **skills**, and other info — SensAi gives you:
  - Current trends in your field
  - New, in-demand skills
  - Career paths you can explore  
  *(Updated weekly with Inngest workflows)*

- 🧠 **Interview Preparation**  
  AI-generated mock interviews with 10 random questions tailored to your industry, powered by **Gemini AI**.

- 📝 **Cover Letter Generator**  
  Automatically creates strong, professional cover letters based on your role and experience.

- 📄 **ATS-Friendly Resume Builder**  
  Generate clean, ATS-optimized resumes that pass filters and stand out to recruiters.

---

## 🛠️ Tech Stack

- **Framework**: Next.js
- **Auth**: Clerk (with Google SSO support)
- **UI**: Shadcn UI
- **AI**: Gemini AI API
- **Workflows & Cron Jobs**: Inngest
- **Database**: PostgreSQL (via Render)
- **Mail**: Resend

---
## 🚀 Getting Started Locally

### 1. Clone the repo

```bash
git clone https://github.com/josiah-praise/career-app.git
cd career-app
```

### 2. Install dependencies

```bash
pnpm install
#or
npm install
```

### 3. Create .env file
Create a .env file in the root directory and fill it with your own credentials:

``` env

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=****************************
CLERK_SECRET_KEY=****************************
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/sign-in

DATABASE_URL=postgresql://[your-db-url]

RESEND_API_KEY=****************************
GEMINI_API_KEY=****************************
```

### 4. Run the dev server

```bash
npm run dev
```

Visit http://localhost:3000 to start using the app.

🧠 Why SensAi?
I built SensAi to make career growth simpler, smarter, and more accessible. I wanted something that could help me (and others) understand what’s happening in our industries, help us practice for real interviews, and get our resumes and cover letters on point — all from one place.

📜 License
MIT

🙌 Acknowledgements
- Clerk.dev

- Inngest

- Gemini AI

- Shadcn UI

- PostgreSQL
  
- Tailwind

> “Stay ready so you don’t have to get ready.” – SensAi 🧘