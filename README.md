# Hi, I'm Abdullah Naser 👋

**Junior Developer** focused on building scalable, production-quality web applications with **React, Next.js, and TypeScript**.

I enjoy working on complex frontend problems, building polished user experiences, and developing **internationalized applications with solid i18n/l10n architecture**.

---

## 🚀 Featured Projects

### [Job Tracker](https://jobtracker-a.netlify.app/) · [GitHub](https://github.com/Abdullah-Nass/jobtracker)

![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js) ![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-7-2D3748?logo=prisma&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Neon_Postgres-PostgreSQL-4169E1?logo=postgresql&logoColor=white)

![Job Tracker screenshot](./screenshots/job-tracker.png)

A full-stack Kanban application for managing job applications.

- Authentication with **Better Auth / Neon Auth**
- Drag-and-drop workflows across four pipeline stages using **dnd-kit**
- Optimistic mutations with **TanStack Query**, including cache rollback on failure
- **Server Actions** and REST Route Handlers
- User-scoped database queries designed to prevent **IDOR vulnerabilities**
- PostgreSQL with **Prisma** and Neon

---

### [Waiter](https://waiter-jm3w.onrender.com/en/login) · [GitHub](https://github.com/Abdullah-Nass/waiter) · [▶ Demo](https://www.youtube.com/watch?v=Y7nLLQ_kL0s)

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-Real--Time-010101?logo=socketdotio&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Neon_Postgres-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-7-2D3748?logo=prisma&logoColor=white) ![Better Auth](https://img.shields.io/badge/Better_Auth-Auth-black) ![Zustand](https://img.shields.io/badge/Zustand-State-764ABC) ![next-intl](https://img.shields.io/badge/next--intl-i18n-black?logo=next.js)

A real-time, bilingual restaurant ordering system for waiters, kitchen staff, and admins.

- Custom **Node.js + Socket.io** server pushes new orders to the kitchen board instantly — no polling
- Kitchen status changes notify the waiter as a **live toast** anywhere in the app
- Role-based access control (**Waiter / Kitchen / Admin**) enforced at the layout level
- Cart state managed with **Zustand**; `Order` + `OrderItem` records created atomically via a single **Server Action**
- **30+ tests** with Vitest and React Testing Library covering store actions and role-aware UI components
- Full **Arabic/English** i18n with **next-intl**, automatic RTL/LTR switching, and bilingual data at the DB level (`nameAr`/`nameEn`)

---

### [Zync](https://zync-app.netlify.app/) · [GitHub](https://github.com/Abdullah-Nass)

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white) ![TanStack Router](https://img.shields.io/badge/TanStack_Router-FF4154?logo=reactquery&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-22-339933?logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?logo=postgresql&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-httpOnly_Cookies-000000?logo=jsonwebtokens&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-Media-3448C5?logo=cloudinary&logoColor=white)

![Zync screenshot](./screenshots/zync.png)

A full-stack social media platform built with a React client and independent Express API.

- JWT authentication with **httpOnly cookies**, implemented without an authentication library
- REST API built with **Node.js, Express, and raw PostgreSQL queries**
- Optimistic likes and follows with synchronized **TanStack Query** caches and rollback
- Infinite scrolling with `useInfiniteQuery` and `IntersectionObserver`
- Debounced search with keyboard-friendly interactions
- Direct browser-to-**Cloudinary** media uploads
- React frontend and Express API deployed independently

---

### [MoviesBase](https://moviesbase-a.netlify.app/) · [GitHub](https://github.com/Abdullah-Nass/moviesbase)

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white) ![TMDB](https://img.shields.io/badge/TMDB_API-01B4E4?logo=themoviedatabase&logoColor=white) ![next-intl](https://img.shields.io/badge/next--intl-i18n-black?logo=next.js)

![MoviesBase screenshot](./screenshots/movies-base.png)

A multilingual movie discovery application demonstrating different Next.js rendering strategies and internationalization patterns.

- **SSR, SSG, and CSR** implemented across the application
- Full i18n for **English, Arabic, and Spanish**
- Localized routes with automatic **RTL/LTR** switching
- Live search with debouncing and keyboard navigation
- **TanStack Query** caching
- Component testing with **Vitest and React Testing Library**

---

### [Multilingual Dashboard](https://dashboard-a-n.netlify.app/) · [GitHub](https://github.com/Abdullah-Nass/dashboard)

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white) ![react-i18next](https://img.shields.io/badge/react--i18next-i18n-blue?logo=i18next) ![JWT](https://img.shields.io/badge/JWT-Auth-000000?logo=jsonwebtokens&logoColor=white)

![Multilingual Dashboard screenshot](./screenshots/dashboard.png)

A task management SPA focused on authentication, internationalization, and modern form/mutation patterns.

- JWT authentication with protected routes
- i18n for **English, Arabic, and Spanish**
- Dynamic **RTL/LTR** layout switching
- Forms built with **React Hook Form + Zod**
- Server-state management with **TanStack Query**
- React 19 + TypeScript + Tailwind CSS

---

### [MyStore](https://mystore-a.netlify.app/) · [GitHub](https://github.com/Abdullah-Nass/mystore)

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?logo=reactrouter&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-HTTP-5A29E4?logo=axios&logoColor=white)

![MyStore screenshot](./screenshots/my-store.png)

An e-commerce SPA focused on client-side state management and a practical shopping workflow.

- Persistent cart using **Context API + localStorage**
- Product search and category filtering
- Pagination and API-driven product data
- Client-side routing with **React Router v7**
- HTTP requests with **Axios**

---

## 🛠 Tech Stack

### Frontend

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?logo=tailwindcss&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?logo=reactrouter&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-v5-FF4154?logo=reactquery&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?logo=reacthookform&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![dnd-kit](https://img.shields.io/badge/dnd--kit-Drag_&_Drop-black)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?logo=radixui&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)
![React Testing Library](https://img.shields.io/badge/Testing_Library-E33332?logo=testinglibrary&logoColor=white)

### Backend & Data

![Node.js](https://img.shields.io/badge/Node.js-22-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-5-000000?logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-7-2D3748?logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?logo=postgresql&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-Auth-black)
![REST API](https://img.shields.io/badge/REST-APIs-02569B?logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

### Internationalization & Localization

![next-intl](https://img.shields.io/badge/next--intl-i18n-black?logo=next.js)
![react-i18next](https://img.shields.io/badge/react--i18next-i18n-blue?logo=i18next)
![react-intl](https://img.shields.io/badge/react--intl-ICU-61DAFB?logo=react&logoColor=white)
![RTL/LTR](https://img.shields.io/badge/RTL%2FLTR-BiDi-8A2BE2)
![PO/POT](https://img.shields.io/badge/PO%2FPOT-Localization-4B8BBE)
![XLIFF](https://img.shields.io/badge/XLIFF-1.2%2F2.0-6A5ACD)

### Languages

![Arabic](https://img.shields.io/badge/Arabic-Native_MSA-008000)
![English](https://img.shields.io/badge/English-Fluent-1E90FF)

---

## 💡 What I Care About

- Building maintainable and scalable React applications
- Clean component architecture and reusable UI
- Type-safe frontend development with TypeScript
- Server-state management and optimistic UI
- Authentication and secure API design
- Performance and modern rendering strategies
- Internationalization, localization, and RTL/LTR experiences
- Testing frontend applications with modern tooling

---

## 📫 Get in Touch

**Portfolio:** [abdullah-nass.github.io/portfolio](https://abdullah-nass.github.io/portfolio/)

**LinkedIn:** [linkedin.com/in/abdullah-naser04](https://www.linkedin.com/in/abdullah-naser04)

**Email:** [abdula.naser04@gmail.com](mailto:abdula.naser04@gmail.com)
