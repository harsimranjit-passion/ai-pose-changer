# 🌟 Project Setup Guide

This project uses **React/Next.js (TypeScript)** with **Gemini API** integration. Follow the steps below to run it locally.

---

## 📋 Prerequisites
- **Node.js** v18+  
- **npm** (bundled with Node.js)  
- **Gemini API Key** (create one at https://aistudio.google.com/)

---

## 🚀 Getting Started

### 1) Clone the repository
```bash
git clone <your-repo-url>
cd <your-project-folder>
```

### 2) Install dependencies
```bash
npm install
```

### 3) Configure environment variables
Create a file named **`.env.local`** in the project root and add:
```env
GEMINI_API_KEY=your_api_key_here
```
> 🔒 Do **not** commit `.env.local` or your API key to Git.

### 4) Run the development server
```bash
npm run dev
```
Open: **http://localhost:3000**

---

## 📂 Project Structure
```
├─ src/              # Application source code
├─ public/           # Static assets
├─ package.json      # Dependencies & scripts
├─ .env.local        # Local environment variables (ignored)
└─ README.md         # This file
```

---

## 🛠️ Scripts
- `npm run dev`   — Start dev server  
- `npm run build` — Build for production  
- `npm run start` — Start production server  
- `npm run lint`  — Lint checks

---

## ❗ Troubleshooting
- **Command not found**: Verify Node.js/npm installation (`node -v`, `npm -v`).  
- **Env not loading**: Ensure file is named `.env.local` and in project root.  
- **API errors**: Confirm `GEMINI_API_KEY` is valid and not rate-limited.

---

## 📜 License
This project is licensed under the **MIT License**. See `LICENSE` (if provided).
