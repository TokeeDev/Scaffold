<div align="center">

<img src="./public/logo.svg" width="100" alt="Scaffold logo" />

# 🏗️ Scaffold

**Your vibe planner for vibe coding.**  
Plan like a product manager. Build like a senior engineer.

</div>

---

## ✨ Overview

**Scaffold** is your AI-powered planning OS for software projects. It guides you from vague idea → structured plan → step-by-step execution — all in one clean interface.

Think of it as your **product manager**, **architect**, and **prompt engineer**, built into one system.

---

## 🔥 Key Features

- 🧠 **AI Discovery Flow**  
  Answer deep planning questions — WHAT, WHO, WHY, HOW — and get a fully generated build plan.

- ✅ **Smart Task Boards**  
  Tasks with subtasks, linked prompts, and AI-generated step-by-step guidance.

- 🧱 **Prompt Engine for Cursor**  
  Create system + instruction prompts per file or feature. Auto-export Cursor config.

- 🗂️ **Project Hub**  
  Central space for your project context, README, architecture diagrams, assets, and more.

- 🎨 **Asset Locker**  
  Upload your logo, color palette, naming ideas, and UI inspiration to keep everything in one place.

- 🧾 **AI-Generated README & File Trees**  
  Let Scaffold write your README.md and starter file structure based on your discovery inputs.

---

## ⚙️ Tech Stack

| Layer           | Tech                             |
|------------------|----------------------------------|
| Frontend         | [Next.js 15](https://nextjs.org), [Tailwind CSS](https://tailwindcss.com), [shadcn/ui](https://ui.shadcn.com) |
| Backend          | [Prisma](https://www.prisma.io), [NeonDB](https://neon.tech) |
| Auth             | [Clerk](https://clerk.dev) |
| AI               | [OpenAI GPT-4o](https://platform.openai.com) |
| File Uploads     | [UploadThing](https://uploadthing.com) |
| Hosting          | [Vercel](https://vercel.com) |
| Diagrams / Docs  | [Mermaid.js](https://mermaid.js.org) |

---

## 🧪 Local Dev Setup

```bash
# 1. Clone this repo
git clone https://github.com/yourusername/scaffold.git
cd scaffold

# 2. Install dependencies
npm install

# 3. Copy environment file
cp .env.example .env.local

# 4. Push Prisma schema to your database
npx prisma db push

# 5. Start the dev server
npm run dev
