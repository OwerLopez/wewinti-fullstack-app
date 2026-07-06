# WeWinTI — Full-Stack Platform

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-Backend-E0234E?style=for-the-badge&logo=nestjs)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-Build-646CFF?style=for-the-badge&logo=vite)

Full-stack web platform built for the **WeWin TI** initiative: a React 19 SPA with authentication flows, protected routing and a service layer, backed by a **NestJS** API.

## Architecture

```
├── src/                 # React frontend
│   ├── auth/            # Authentication (context + guards)
│   ├── components/      # Reusable UI components
│   ├── layouts/         # App shells / page layouts
│   ├── pages/           # Route views
│   ├── routes/          # Router config (protected routes)
│   └── services/        # API clients (axios)
└── backend/             # NestJS API
    ├── src/             # Modules, controllers, services
    └── test/            # E2E tests
```

## Stack

| Layer | Tech |
|-------|------|
| Frontend | React 19 · React Router 7 · React Hook Form · Tailwind CSS v4 · Axios |
| Backend | NestJS (TypeScript) · ESLint · Prettier |
| Tooling | Vite (SWC) · npm |

## Quick start

```bash
# Frontend
npm install && npm run dev

# Backend
cd backend && npm install && npm run start:dev
```

---
**Ower Frank Lopez Arela** — Backend & Data Engineering · [Portfolio](https://owerlopez.dev) · [LinkedIn](https://linkedin.com/in/ower-frank-lopez-arela-29558a285)
