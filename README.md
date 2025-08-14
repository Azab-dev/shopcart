<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="Next.js" />
    <img src="https://img.shields.io/badge/-Sanity-ea2328?style=for-the-badge&logo=sanity&logoColor=white" alt="Sanity" />
    <img src="https://img.shields.io/badge/-Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" />
    <img src="https://img.shields.io/badge/-Clerk-4b2aad?style=for-the-badge&logo=clerk&logoColor=white" alt="Clerk" />
    <img src="https://img.shields.io/badge/-Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  </div>

  <h3 align="center">E-Commerce Platform — Next.js + Sanity CMS</h3>
  <p align="center">A modern full-stack shop with CMS-driven products, secure checkout, and clean, responsive UI.</p>
</div>

---

## 📋 Table of Contents
1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔐 [Environment Variables](#environment-variables)
6. 🗂️ [Project Structure](#project-structure)
7. 🖼️ [Screenshots](#screenshots)
8. 🛠️ [My Enhancements](#my-enhancements)
9. 🗺️ [Roadmap](#roadmap)
10. 📄 [License](#license)

---

## 🤖 Introduction
A production-ready **E-Commerce platform** built with **Next.js (App Router)** and **TypeScript**.  
Content is fully managed in **Sanity CMS** (products, categories, banners), with **Clerk** for auth and **Stripe** for payments.  
The app focuses on performance, accessibility, and a delightful shopping experience.

---

## ⚙️ Tech Stack

- **Next.js** — Full-stack React framework (SSR/ISR, API routes)
- **TypeScript** — Type-safe development
- **Sanity CMS** — Headless CMS for products & content
- **Clerk** — Authentication & user management
- **Stripe** — Checkout & payments
- **Tailwind CSS + shadcn/ui** — Modern, accessible UI
- **Vercel** — Hosting & CI/CD

---

## 🔋 Features

- **CMS-Driven Catalog** — Products, categories, and promotional banners from Sanity
- **Powerful Product Pages** — Variants, rich content, and optimized images
- **Cart & Checkout** — Persistent cart and secure Stripe Checkout
- **Auth** — Email/OAuth login, protected routes with Clerk
- **Search & Filters** — Category filters and keyword search
- **Responsive & Fast** — Lighthouse-friendly, mobile-first UI

---

## 🤸 Quick Start

```bash
# 1) Clone
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# 2) Install
npm install

# 3) Env vars (see next section)
cp .env.example .env.local  # optional helper

# 4) Dev
npm run dev
# open http://localhost:3000
