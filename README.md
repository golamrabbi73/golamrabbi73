<!-- ===================== BANNER ===================== -->
<p align="center">
  <img 
    src="https://i.ibb.co.com/F4sT2Stx/Chat-GPT-Image-Jul-28-2026-08-13-43-PM.png" 
    alt="Md. Golam Rabbe - Full Stack Developer Banner" 
    width="100%" 
  />
</p>

<h1 align="center">Hi 👋, I'm Md. Golam Rabbe</h1>

<h3 align="center">
  Full Stack Developer | React • Next.js • Node.js
</h3>

<p align="center">
  <img 
    src="https://readme-typing-svg.demolab.com/?lines=Full+Stack+Developer;Improving+GeoLog+-+a+Geo-Data+SaaS;Open+to+Junior+Dev+Roles&center=true&width=500&height=45" 
    alt="Typing SVG" 
  />
</p>

<p align="center">
  <img 
    src="https://komarev.com/ghpvc/?username=golamrabbi73&label=Profile%20Views&color=0e75b6&style=flat" 
    alt="Profile Views" 
  />
</p>

---

## 🙋‍♂️ About Me

I'm **Md. Golam Rabbe**, a full stack developer building with **React, Next.js, Node.js, TypeScript, and MongoDB**.

- 🏗️ Currently improving **GeoLog** — a deployed B2B SaaS platform for subsurface data and core sample management, adding features and polishing UX for petroleum/mining/geology teams
- 🤖 Also built **TrendPulse AI**, an AI-driven competitor research platform powered by Groq's Llama 3.3 70B
- 💻 Comfortable across the stack: REST APIs with Express/TypeScript, MongoDB schema design, and React/Next.js frontends
- 🎯 I focus on getting the architecture and data modeling right before writing feature code — every project starts with a requirements/discovery pass, not just UI
- 🌱 Started solving DSA basics on LeetCode
- 📬 Open to Junior Full Stack Developer roles

---

## 🚀 Current Focus

- 🏗️ Adding features and improving UX on **GeoLog** (deployed) — role-based access and core sample/well modules already live, working on search, pagination, and view/edit flows
- 🚗 **DriveFleet** is in maintenance mode — stable, not under active feature development right now
- 🧠 Just getting started with DSA basics on LeetCode

---

## 🛠️ Tech Stack

### Frontend
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind" />
</p>
<p>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
</p>

### Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb" />
</p>
<p>
  <img src="https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge" />
</p>

### Auth & Payments
<p>
  <img src="https://skillicons.dev/icons?i=firebase" />
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" />
</p>

### Tools & Deployment
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,vercel" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" />
</p>

---

## 📌 Featured Projects

### 🛢️ GeoLog — Subsurface Data & Core Sample Management

- 🌐 **Live:** [Live Demo](https://geolog-platform.vercel.app)
- 💻 **GitHub:** [Repository](https://github.com/golamrabbi73/geolog-platform)
- 🛠️ **Tech:** Next.js, TypeScript, Express, MongoDB, Mongoose, Zod, React Hook Form, TanStack Query, JWT (httpOnly cookies)

A deployed B2B SaaS platform for petroleum/mining/geology teams to manage well records and core sample data, built with a real requirements-first process rather than as a template clone.

#### ✨ What's live
- Role-based access control (manager/admin/field-engineer roles with different permissions)
- Core Sample and Well modules: full CRUD with ownership checks (e.g., users can only edit samples they collected)
- JWT auth via httpOnly cookies, with CORS credentials configured across separate frontend/backend deployments
- Type-safe data layer: shared TypeScript interfaces for Well, Core Sample, and User entities, validated with Zod on the backend
- Fixed a production bug where unhandled JWT errors were crashing the Node process (502s on Render) by wrapping auth middleware in a catch-all error handler

#### 🚧 Currently adding
- Search and pagination
- View/Edit pages for Wells and Core Samples
- General UX polish

*This is the project I'm actively growing into something real teams in the industry could use — not just a portfolio demo.*

---

### 📊 TrendPulse AI — Competitor Research Platform

- 🌐 **Live:** [Live Demo](https://trendpulse-rouge.vercel.app)
- 💻 **GitHub:** [Repository](https://github.com/golamrabbi73/trendpulse)
- 🛠️ **Tech:** Next.js 15, TypeScript, Tailwind CSS, React Query, Zustand, React Hook Form, Zod, Recharts, Node.js, Express.js, MongoDB, JWT, Google OAuth, Groq AI (Llama 3.3 70B)

An AI-driven competitor research platform that helps businesses analyze competitors, spot market opportunities, and generate strategic marketing playbooks using Google Gemini AI.

#### ✨ Features
- AI-generated insights from uploaded business documents via Groq's Llama 3.3 70B model
- Asynchronous AI workflows with clear loading/feedback states for long-running analysis
- Secure auth via JWT and Google OAuth
- Data visualization with Recharts for competitor/market breakdowns

#### 🚧 Planned improvements
- Automated competitor monitoring
- AI chat assistant for business analysis
- Exportable PDF/presentation reports
- Team collaboration workspace

---

### 🤖 AI Prompt Sharing Marketplace

- 🌐 **Live:** [Live Demo](https://ai-prompt-hub-client.vercel.app)
- 💻 **GitHub:** [Repository](https://github.com/golamrabbi73/ai-prompt-hub-client)
- 🛠️ **Tech:** React, Node.js, Express.js, MongoDB, Firebase Auth, JWT, TanStack Query, Stripe, Framer Motion

A marketplace where users can list and sell AI prompts, with a full payment flow rather than just a static listing site.

#### ✨ Features
- Stripe-integrated checkout for paid prompt listings
- Role-based dashboard (buyer vs. seller views)
- Firebase Auth + JWT for session security
- Fully responsive UI with animated transitions (Framer Motion)

---

### 🚗 DriveFleet — Car Rental Platform

- 🌐 **Live:** [Live Demo](https://my-assignment09.vercel.app)
- 💻 **GitHub:** [Repository](https://github.com/golamrabbi73/my-assignment09)
- 🛠️ **Tech:** React, Express.js, MongoDB, Firebase Auth, JWT, Tailwind CSS

A car listing and booking platform with a custom dark/light theme system built from scratch (not a UI-library default toggle).

#### ✨ Features
- Custom `useTheme` hook (localStorage-persisted, `data-theme`-based) — built to work around DaisyUI v5 overriding Tailwind's theme colors
- Full car listing management (add/update/delete)
- Firebase Auth + JWT-secured REST API

---

### 🏠 Tile Gallery Platform

- 🌐 **Live:** [Live Demo](https://assignment-08-alpha.vercel.app/)
- 💻 **GitHub:** [Repository](https://github.com/golamrabbi73/assignment-08)
- 🛠️ **Tech:** Next.js 15, React, Tailwind CSS, DaisyUI, HeroUI, MongoDB, BetterAuth, SwiperJS

A searchable tile catalog with authenticated user profiles, built on the Next.js App Router.

#### ✨ Features
- Dynamic search across the tile catalog
- Google Sign-In via BetterAuth
- User profile management with update flow
- Private route protection for authenticated pages

---

## 📊 GitHub Stats

<p align="center">
  <img 
    src="https://github-readme-stats-sigma-five.vercel.app/api?username=golamrabbi73&show_icons=true&theme=tokyonight" 
    alt="GitHub Stats" 
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=golamrabbi73&layout=compact&theme=tokyonight" 
    alt="Top Languages" 
  />
</p>

<p align="center">
  <img 
    src="https://streak-stats.demolab.com/?user=golamrabbi73&theme=tokyonight" 
    alt="GitHub Streak" 
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=golamrabbi73&theme=tokyo-night" 
    alt="GitHub Contribution Graph" 
  />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/golamrabbi73" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/golamrabbi73" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://portfolio-seven-mauve-98.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:mdgolamrabbe.dev@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  📍 <strong>Sirajganj, Bangladesh</strong>
</p>

---

<p align="center">
  <strong>Thanks for visiting! Open to full stack roles and collaborations — feel free to reach out.</strong>
</p>
