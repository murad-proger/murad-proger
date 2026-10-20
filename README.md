# Murad Adigozalov

**Senior Frontend Engineer** • **React** • **Next.js** • **TypeScript**

📍 Sumqayit, Azerbaijan · Open to: **Remote (global)** · **Relocation (Poland, Belarus)** · **On-site (Azerbaijan)**

Senior Frontend Engineer with **7+ years of experience** and the **sole Frontend Developer on 20+ commercial projects** — e-commerce platforms, corporate websites, and web applications — from Figma to production. Frontend Lead at Oweb Solutions (2020–2025), where I owned architecture, performance, accessibility, and technical SEO decisions end-to-end, working with designers, backend developers, project managers, and clients.

I also build **full-stack Next.js applications** (App Router, Server Actions, Supabase, Prisma, Auth.js, Stripe) with automated tests and CI/CD.

**Measurable results from commercial work:**
**PageSpeed 57 → 92** · **Top-5 search rankings in Moscow** · **booking conversions +~12%** · **support inquiries −~32%** · **14-page brand platform shipped in 1 month**

---

## 💼 Experience Highlights

* **7+ years** of frontend development (5+ years commercial at Oweb Solutions, Frontend Lead)
* Sole Frontend Developer on **20+ commercial projects**
* Frontend architecture and technical decision-making, from Figma to production
* Technical estimation and feature planning
* Migration of legacy **jQuery modules to React**
* Migration of monolithic **PHP 5.6** systems to modular **React + Vite + Redux** with typed OpenAPI/Swagger contracts
* REST API integration and client-side business logic
* Technical SEO implementation
* Performance and accessibility optimization
* Pull request reviews and code quality practices; strict Git flow (feature branches, PRs)
* Mentored a Frontend Intern
* Advised designers on frontend constraints, UI patterns, and reusable components
* Direct collaboration with clients, designers, backend developers, and project managers

### Selected Results

* **Rozetki.su** — raised Google PageSpeed Performance from **57 to 92** (Desktop) by removing 4,000+ lines of redundant CSS, conditional script loading, and native lazy loading; reached **Top-5 search rankings in Moscow** via semantic HTML, Schema.org microdata, and dynamic breadcrumbs; rebuilt the outlet configurator in React with dynamic product variants
* **KrymKing** — re-engineered the vacation rental booking interface (form/date-picker UX, down to 320px), lifting bookings **~12%** and cutting booking completion time **~30%** (verified via Yandex Metrica); custom Yandex Maps integration with interactive property markers (50+ listings)
* **Cryomont** — 14-page flagship brand platform built from scratch **in 1 month** (vs. a 2–3 month industry baseline): 15 responsive breakpoints, 8 synchronized Swiper carousels, interactive SVG map with region/city tooltips, and a custom ~300-LOC full-page scrolling engine in vanilla JS (no licensed or third-party dependency)
* **AKmarket40** — e-commerce storefront and admin from Figma to production in 4 months, with a custom drag-and-drop product comparison interface (pure CSS alignment, no JS runtime overhead); traffic and time-on-site grew ~20% after launch
* **AltoCar** — subscriptions, discount-day management, points tracking/redemption; the new points/discount UI cut related support inquiries **~32%**; mobile-first flows (<768px) kept consistent with the React Native app

### Engineering Highlights

* Authored zero-dependency DOM micro-animations on `Element.prototype` (`requestAnimationFrame`), saving ~70–80 KB (~25–30 KB gzip) per page load by replacing a legacy library
* Removed critical UI race conditions between timed video playback, tab switching, and CSS animations with deterministic state-reset logic
* Established reusable component design tokens and resolved 20+ script and styling merge conflicts before production deployments

---

## 🛠 Tech Stack

### Frontend

React (18/19) · Next.js (App Router) · TypeScript · JavaScript (ES6+) · HTML5 · CSS3 · SCSS · CSS Modules · Tailwind CSS · Vite · SPA

### UI & Design

Design Systems · Ant Design · Bootstrap · Radix UI · shadcn/ui · Swiper · Yandex Maps API · Canvas/SVG · CSS Animations · Figma

### State Management & Data Fetching

Redux Toolkit · TanStack Query · Context API · Axios · REST API · OpenAPI/Swagger

### Forms & Validation

React Hook Form · Zod

### Next.js & Server-side

Server Components · Server Actions · Route Handlers · API Routes · SSR

### Backend & Database

Prisma ORM · PostgreSQL · Supabase (Database, Storage) · Auth.js · Stripe (Checkout, Webhooks, Refunds, Idempotency)

### Testing & CI/CD

Vitest · Jest · React Testing Library · GitHub Actions · Vercel Deployment Checks · Docker / Docker Compose

### Accessibility & Web Standards

Web Accessibility · WCAG · Semantic HTML · ARIA · Technical SEO · Schema.org · Core Web Vitals

### Tools

Git · GitHub · Docker · Vercel · ESLint · Prettier · Claude Code (AI-assisted engineering)

### CMS

WordPress · Bitrix · MODX · Tilda · Elementor · PHP template modifications

---

## 📌 Featured Projects

### BookNest — Fullstack Bookstore with Stripe Payments, Tests & CI/CD

**Next.js 16 • React 19 • TypeScript • Prisma • PostgreSQL • Supabase • Auth.js • Stripe • TanStack Query • Redux Toolkit • Vitest • GitHub Actions • Docker Compose**

🔗 [Live](https://murad-booknest.vercel.app) · [Code](https://github.com/murad-proger/booknest)

Production-like online bookstore (storefront + admin panel, user/admin roles via Auth.js) built around a complete Stripe payment lifecycle in test mode: checkout, payment retry, admin refunds, and signature-verified idempotent webhooks with race-condition protection.

**Highlights:**

* Full Stripe payment lifecycle (Checkout, retries, refunds, webhooks) with idempotent, signature-verified webhook handling
* 24 unit and component tests (Vitest, React Testing Library)
* GitHub Actions CI pipeline with Vercel Deployment Checks gating releases
* Multi-tier state: TanStack Query for server caching, Redux Toolkit for client state
* Supabase PostgreSQL and Storage
* Light/dark UI on design tokens with a reusable component kit

---

### Used Cars Marketplace

**Next.js App Router • React • TypeScript • Prisma • PostgreSQL • Supabase • Auth.js • Tailwind CSS**

🔗 [Live](https://used-cars-next.vercel.app) · [Code](https://github.com/murad-proger/car-marketplace-fullstack)

Full-stack marketplace on the Next.js App Router.

**Highlights:**

* Authentication with role-based server-side authorization
* Admin dashboard with CRUD operations
* Favorites, product catalog
* Server-side shopping cart with quantity management, checkout, order confirmation
* URL-based catalog filtering/sorting with shareable links, state persists across navigation and reload
* PostgreSQL database with Prisma ORM, responsive UI, deployed on Vercel

---

### Car Marketplace UI System

**React • Redux Toolkit • TypeScript • React Router • REST API • Vite**

🔗 [Live](https://murad-proger.github.io/car-marketplace-frontend) · [Code](https://github.com/murad-proger/car-marketplace-frontend)

Frontend-focused marketplace demonstrating scalable UI architecture and modular Redux Toolkit state management (catalog, filters, cart, favorites, orders).

**Highlights:**

* Filtering and sorting by price, year, engine displacement, brand, body type
* URL state synchronization
* Reusable UI components
* Async data fetching with Axios and `createAsyncThunk`
* Cart, favorites, checkout, and order history persisted in LocalStorage

---

## ♿ Accessibility & Performance

Interfaces that are not only functional, but also **performant, accessible, and SEO-friendly**. My commercial experience includes:

* Web Accessibility and WCAG principles
* Semantic HTML, ARIA
* Google PageSpeed optimization (57 → 92), conditional script loading, native image lazy loading
* JavaScript and CSS optimization, bundle size reduction
* Technical SEO, Schema.org structured data (Top-5 rankings in Moscow)

---

## 🧩 Development Approach

* Maintainable · Scalable · Well-structured · Easy to extend
* Performance-oriented · Accessible
* Covered by automated tests, shipped through CI/CD

I value clear architecture, reusable components, predictable state management, and code that is easy for other developers to understand and maintain.

---

## 🌐 Languages

Azerbaijani (native) · Russian (native) · English (B1, reads and writes technical documentation fluently)

---

## 📫 Contact

* **LinkedIn:** [linkedin.com/in/murad-sabiroglu](https://linkedin.com/in/murad-sabiroglu)
* **GitHub:** [github.com/murad-proger](https://github.com/murad-proger)
* **Telegram:** [@murad_sabiroglu](https://t.me/murad_sabiroglu)
* **Email:** [murad.proger@gmail.com](mailto:murad.proger@gmail.com)
