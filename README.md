# 🌲 The Wild Oasis Website

A modern, full-stack luxury cabin booking and guest management platform built with Next.js 14, featuring real-time data handling, server actions, and secure authentication.

---

## 🔗 Live Demo

- **Live Application:** [https://the-wild-oasis-website-wheat-three.vercel.app/](https://the-wild-oasis-website-wheat-three.vercel.app/)

---

## 🚀 Tech Stack

- **Framework:** Next.js 14 (App Router & Server Actions)
- **Styling:** Tailwind CSS
- **Database & Backend:** Supabase (PostgreSQL)
- **Authentication:** Auth.js / NextAuth.js (Google OAuth)
- **Deployment:** Vercel

---

## ✨ Features

- 🏡 **Cabin Showcase:** Dynamic cabin listing, filtering by capacity, and detailed cabin views.
- 📅 **Interactive Booking:** Live reservation calendar, date picking, guest limits, and automatic price calculation.
- 🔐 **Guest Area:** Google OAuth login, user profile editing, and reservation management (view, edit, delete bookings).
- ⚡ **Optimistic UI:** Fast, responsive client-side updates combined with server-side data mutations.

---

## 🛠️ Getting Started (Local Development)

1. Clone the repository:
   ```bash
   git clone [https://github.com/mustafasensess/the-wild-oasis-website.git](https://github.com/mustafasensess/the-wild-oasis-website.git)

2. Install dependencies:
    ```bash
    npm install

3. Set up environment variables in a .env.local file:
   
    SUPABASE_URL=your_supabase_url
   
    SUPABASE_KEY=your_supabase_key
   
    NEXTAUTH_URL=http://localhost:3000
   
    NEXTAUTH_SECRET=your_secret

5. Run the development server:
    ```bash
    npm run dev
   
