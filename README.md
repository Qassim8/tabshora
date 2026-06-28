**Tabshora** is a lightweight, type-safe School ERP and Financial Management MVP (Minimum Viable Product). It is architected to help schools transition seamlessly from chaotic paper-based records to a streamlined digital ecosystem. The system focuses on high efficiency, data integrity, and optimizing UX for data entry operators and school administrators.

## ✨ Core Features

* **📂 Student Registry & Indexing:** A centralized system to index student profiles, parents' contact info, and academic tracks. Features a one-click **Excel Export** designed to prepare student data sheets for external portal integrations.
* **⏱️ Attendance by Exception:** A smart UI that checks in all students by default, allowing instructors to toggle only the absent ones. This cuts daily data entry time by up to 90%.
* **💳 Automated Invoicing & Installments:** Automatically generates pending future invoices and monthly installments the moment a student is registered, based on their customized financial plan.
* **💰 Quick Payments & Cashflow Insights:** Easily record payments (Cash, Bank Transfer, or Online), instantly flip invoice statuses to `Paid`, and view real-time dashboard analytics tracking daily revenue, pending dues, and net profits.

## 🛠️ Tech Stack & Architecture

The project is built using a modern frontend stack that strictly enforces the **Separation of Concerns** between UI state, server state, and form management:

* **React (Vite) & TypeScript:** Utilizes strict typing to eliminate runtime bugs and enforce structural data safety across components.
* **Zustand:** Manages global UI states (e.g., controlling modal triggers, caching selected rows for editing) smoothly without prop drilling.
* **React Query (TanStack Query):** Handles server state management, caching, background fetching, and instantaneous UI synchronization via query invalidation (`invalidateQueries`).
* **Formik & Yup:** Manages form states, handling complex field destructuring and robust client-side validation schemas.
* **Tailwind CSS (v4):** Powers a fast, responsive, and modern "white-label" dashboard design.

## 🚀 Project Goal

Tabshora is built as a real-world MVP to be deployed and battle-tested in an active educational institution. Development is continuously driven by real-user feedback, performance monitoring, and iterative UI/UX enhancements.
