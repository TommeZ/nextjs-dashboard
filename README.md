# Next.js Dashboard

A modern full-stack dashboard application built with the Next.js App Router.  
This project demonstrates authentication, protected routes, server actions, database integration, search, pagination, and responsive dashboard UI patterns using modern React and Next.js best practices.

Inspired by the official Next.js dashboard course and extended with additional real-world architecture and authentication improvements.

---

## ✨ Features

- ⚡ Built with the Next.js App Router
- 🔐 Authentication with Auth.js / NextAuth
- 🛡 Protected dashboard routes
- 🗄 Database integration
- 📊 Dashboard analytics UI
- 🔎 Search and filtering
- 📄 Pagination
- ✏️ CRUD functionality
- 📱 Responsive design
- 🎨 Styled with Tailwind CSS
- 🧩 Server Components + Client Components
- 🚀 Optimized for Vercel deployment
- 🧠 TypeScript support

---

## 🛠 Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- Auth.js
- Vercel

---

## 📸 Preview

Add screenshots or a demo GIF here.

Example:

```md
![Dashboard Preview](/public/dashboard-preview.png)
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/TommeZ/nextjs-dashboard.git
cd nextjs-dashboard
```

### 2. Install dependencies

Using pnpm:

```bash
pnpm install
```

Or npm:

```bash
npm install
```

---

## ⚙️ Environment Variables

Create a `.env.local` file in the root directory:

```env
AUTH_SECRET=your_secret_here
AUTH_URL=http://localhost:3000

# Database
POSTGRES_URL=your_database_url
```

You can generate a secret using:

```bash
openssl rand -base64 32
```

---

## ▶️ Running the Development Server

```bash
pnpm dev
```

Open:

```txt
http://localhost:3000
```

---

## 🔐 Authentication

This project uses Auth.js credentials authentication.

Protected routes are handled through middleware and server-side session validation.

Example features include:

- Login/logout flow
- Session handling
- Route protection
- Callback URLs
- Middleware redirects

---

## 📂 Project Structure

```txt
app/
├── dashboard/
├── login/
├── ui/
├── lib/
├── api/
└── layout.tsx

auth.ts
middleware.ts
```

### Important folders

| Folder          | Purpose                        |
| --------------- | ------------------------------ |
| `app/dashboard` | Protected dashboard pages      |
| `app/ui`        | Reusable UI components         |
| `app/lib`       | Database queries and utilities |
| `app/api`       | API route handlers             |
| `middleware.ts` | Route protection and redirects |
| `auth.ts`       | Auth.js configuration          |

---

## 🧠 What This Project Demonstrates

This repository is designed as a practical learning project for modern Next.js development.

Key concepts include:

- App Router architecture
- Server Actions
- React Server Components
- Authentication flows
- Middleware
- Database querying
- Form validation
- Streaming and loading states
- URL search params
- Scalable folder structure

---
