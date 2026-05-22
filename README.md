# Rax Publications – Astro Static Site

This repository contains the **static site** for **Rax Publications**, an academic publishing platform migrated from WordPress to Astro.

## ✨ Features
- Modern, high‑performance static site generated with Astro
- Premium "Kitspress" inspired design (cyan & navy palette, professional typography)
- Pages: Home, About, Journals, Editorial Board, Archives, Contact, and individual journal pages
- Responsive layout, dark footer, and integrated logo
- Easy to deploy on free static hosts (Netlify, Vercel, GitHub Pages)

## 🛠️ Getting Started
```bash
# Install dependencies
npm install

# Run the development server
npm run dev   # http://localhost:4321
```

## 📦 Build for Production
```bash
npm run build   # outputs to ./dist
npm run preview # preview the built site locally
```

## 🚀 Deploy
Push the repository to GitHub and connect it to a static hosting service (Netlify/Vercel). The site will be automatically built and deployed.

## 📂 Project Structure
```
/
├─ public/            # static assets (logo, favicons)
├─ src/
│   ├─ layouts/      # Layout.astro (header/footer)
│   ├─ pages/        # Astro pages (index, about, contact, …)
│   └─ styles/       # global.css
├─ astro.config.mjs   # Astro configuration
├─ package.json       # dependencies & scripts
└─ README.md          # this file
```

## 📧 Contact
For any questions, reach out at **support@raxpublications.com**.
