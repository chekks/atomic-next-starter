# 🚀 Next.js Starter Kit (Atomic + Tailwind + React Query + shadcn)

A production-ready starter kit that helps you build clean, scalable web apps fast.

## 📦 Tech Stack
- ✅ Next.js (App Router)
- 🎨 Tailwind CSS + shadcn/ui
- ⚛️ React Query for data fetching
- 🧱 Atomic design pattern (atoms → organisms)

## 🗂️ Folder Structure Highlights
- `components/` → atomic UI (atoms, molecules, organisms)
- `lib/api/` → React Query hooks for data fetching
- `hooks/` → custom utilities like useAuth, useTimezone
- `providers/` → app-level providers (e.g., QueryClientProvider)
- `types/` → reusable TypeScript types

## 🚀 Getting Started
```bash
pnpm install
pnpm dev
```

## 🔧 ENV Setup
Create a `.env.local` file:
```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

## ☁️ Deploy on Vercel
This kit works great with Vercel:

1. Push your code to GitHub
2. Go to https://vercel.com/new
3. Import your GitHub repo
4. Set your `.env` vars (like `NEXT_PUBLIC_API_URL`)
5. Click "Deploy"

That’s it. You get production hosting with preview deployments by default.

## 📁 Clone This Template
```bash
git clone https://github.com/yourusername/nextjs-starter-kit.git
cd nextjs-starter-kit
```

## ✅ To-Do
- [ ] Add authentication (Clerk or NextAuth)
- [ ] Customize branding
- [ ] Replace dummy pages/components

---

Feel free to fork or use as your foundation for client work, SaaS apps, admin panels, and more!
