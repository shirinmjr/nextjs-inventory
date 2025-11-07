# PrintForge – Inventory Management Module

Part of the [NextJS-Inventory](https://github.com/shirinmjr/nextjs-inventory) monorepo  
**Folder:** `printforge`

## 🚀 Overview

The PrintForge Scrimba project is an educational application built in the Scrimba learning platform that teaches users how to build a full-stack web application using Next.js. The project involves creating a platform for browsing and sharing STL files for 3D printing, and it covers key concepts like static and dynamic routing, server-side and client-side rendering, and data fetching.

## ✨ Features

- ✅ Static & dynamic routing
- ✅ Server-side & client-side rendering
- ✅ Layouts, pages & data fetching, and more!

## 🧰 Tech Stack

- **Framework:** Next.js (App Router)
- **Frontend:** React, TypeScript, Tailwind CSS
- **Database / ORM:** Prisma / PostgreSQL (or your setup)
- **API:** Next.js API Routes
- **Deployment:** Vercel / Node.js server
- **Testing:** Jest / React Testing Library (optional)

## 🧩 Folder Structure

```
printforge/
├── app/                # Next.js app routes, layouts & pages
├── components/         # Reusable UI components
├── lib/                # Database clients & utilities
├── api/                # API endpoints
├── public/             # Static assets
├── styles/             # Tailwind or CSS modules
├── tests/              # Unit & integration tests
├── package.json
├── next.config.js
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

- Node.js v16+
- npm or yarn
- Access to a running database (e.g. PostgreSQL or MongoDB)

### 1️⃣ Installation

```bash
git clone https://github.com/shirinmjr/nextjs-inventory.git
cd nextjs-inventory/printforge
npm install
```

### 2️⃣ Environment Setup

Create a `.env.local` file:

```bash
DATABASE_URL="your_database_url"
NEXT_PUBLIC_API_BASE_URL="http://localhost:3000/api"
PRINT_JOB_API_KEY="your_api_key"
```

### 3️⃣ Run in Development

```bash
npm run dev
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser.

### 4️⃣ Build for Production

```bash
npm run build
npm start
```

### 5️⃣ Testing

```bash
npm run test
```

## 💡 Example Commands

| Action           | Command         |
| ---------------- | --------------- |
| Start dev server | `npm run dev`   |
| Lint code        | `npm run lint`  |
| Build production | `npm run build` |
| Run tests        | `npm run test`  |

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add feature"`
4. Push branch: `git push origin feature/your-feature`
5. Submit a Pull Request

Please make sure your code passes linting and tests before submitting.

## 📜 License

Licensed under the **MIT License** – see the [LICENSE](../LICENSE) file for details.

## 🙏 Acknowledgements

- Next.js team for their amazing framework
- Tailwind CSS contributors
- Open-source libraries powering this module
- Everyone who contributes feedback, bug reports, or improvements

---

**Author:** [Shirin Mohajer](https://github.com/shirinmjr)
🌐 _Part of the NextJS-Inventory ecosystem – building smarter, modular inventory tools._
