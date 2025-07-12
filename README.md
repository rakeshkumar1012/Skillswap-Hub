
# Skill Swap Platform

**Problem Statement: 1**  
**Name**: Akuthota Rakesh Kumar  
**Email**: akuthotarakeshkumar1012@gmail.com  
**Live Link**: https://akuthota-rakesh-kumar-front-end-project-rak8738-3467s-projects.vercel.app/home

A futuristic skill exchange platform built using **Next.js**, **TypeScript**, and **Tailwind CSS**, enabling users to connect and exchange skills seamlessly. This project follows a modular structure and includes features like authentication, skill management, and an admin dashboard.

## 🚀 Tech Stack

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Package Manager**: pnpm
- **Bundler**: Vite (via Next.js)
- **Form UI**: V0 by Vercel
- **Authentication**: [Custom UI placeholders in auth/]

## 📁 Project Structure

```
.
├── app/
│   ├── globals.css           # Global styles
│   ├── layout.tsx            # Root layout component
│   ├── loading.tsx           # Loading state
│   ├── page.tsx              # Home page
│   └── auth/
│       ├── signin/page.tsx   # Sign In UI
│       └── signup/page.tsx   # Sign Up UI
├── components.json           # UI component definitions
├── next.config.mjs           # Next.js configuration
├── package.json              # Project metadata and dependencies
├── pnpm-lock.yaml            # Lock file for pnpm
├── postcss.config.mjs        # PostCSS config
├── tailwind.config.ts        # Tailwind theme config
├── tsconfig.json             # TypeScript settings
├── middleware.ts             # Middleware configuration
└── .gitignore                # Ignored files for Git
```

## 📦 Getting Started

### 1. Install Dependencies

```bash
pnpm install
```

### 2. Run the Development Server

```bash
pnpm dev
```



### 3. Build for Production

```bash
pnpm build
```

## 🧩 Features (Planned / Scaffolded)

- [x] User Authentication (Sign In / Sign Up)
- [ ] Skill Posting & Requesting
- [ ] Skill Search
- [ ] Swap Request Flow
- [ ] Feedback after swap
- [ ] Admin Panel (`/admin` route - placeholder)




