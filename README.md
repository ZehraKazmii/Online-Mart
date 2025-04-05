# 🛒 Online Mart – Full E-Commerce Website with Next.js 15 & MongoDB

A fully-featured e-commerce web application built with the **latest Next.js 15 App Router**, **MongoDB**, **Shadcn UI**, **Tailwind CSS**, and integrated with **Stripe**. Includes user and admin dashboards, modern design, responsive UI, and advanced Next.js features like parallel routes and server actions.


---

## 🧑‍🏫 What You'll Learn

- Build dynamic e-commerce pages using **Next.js 15 Server Components**
- Create elegant UI (header, sidebar, search, product modals) with **Tailwind CSS + Shadcn**
- Use **parallel routes** and **intercepting routes** for Quick View modals
- Design MongoDB **Mongoose models** for products, orders, and users
- Handle form validation with **react-hook-form** and **zod**
- Update data using **Next.js server actions** (no need for APIs!)
- Implement server-side cart with **HTTP cookies**
- Use **Auth.js** with **Google Sign-In** and **Magic Link** for authentication
- Create a **Customer Dashboard** to view/update profile & track orders
- Develop an **Admin Dashboard** with analytics using **Recharts**
- Admin features: manage users, products, and orders

---

## 🛠️ Tech Stack

| Category        | Tech Used                                  |
|----------------|---------------------------------------------|
| Framework       | Next.js 15, React 19                        |
| UI              | Tailwind CSS, Shadcn UI, Recharts           |
| Database        | MongoDB, Mongoose                          |
| Authentication  | Auth.js, Google OAuth, Magic Link          |
| Payments        | Stripe                             |
| File Upload     | Uploadthing                                |
| Email           | Resend                                     |
| Validation      | Zod                                        |
| Deployment      | GitHub + Vercel                            |

---

## 🚀 Getting Started (Run Locally)

### 1. Clone the Repository
Create .env.local. file

```bash
MONGODB_URI=your_mongodb_uri
STRIPE_SECRET_KEY=your_stripe_key
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000
RESEND_API_KEY=your_resend_key
UPLOADTHING_SECRET=your_uploadthing_secret

### 2. 🔐 Run
 
```bash
npm run dev


