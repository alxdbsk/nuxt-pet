# 📰 Nuxt 3 News Portal – SSR Learning Project

Welcome! This project is designed to help you dive deep into **Nuxt 3**, with a strong focus on **Server-Side Rendering (SSR)** and core framework features.

You’ll build a fully functional **news portal** with categories, dynamic article pages, server-side APIs, SEO optimization, and real SSR deployment.

---

## 🎯 Project Goal

Create a news portal that supports:

- SSR-rendered public pages
- Dynamic routing for articles and categories
- SEO-optimized article pages with Open Graph tags
- Server API routes for articles and categories
- Pinia-based global state
- Middleware and route guards
- Tailwind CSS styling
- Production deployment (Vercel or Netlify)

---

## 📘 What You’ll Learn

- How Nuxt handles SSR and data fetching on the server
- How to use Nuxt’s file-based routing system
- How to build API routes inside a Nuxt app (`/server/api`)
- How to generate meta tags dynamically for SEO and sharing
- How to use middleware and manage app-level logic
- How to structure a Nuxt app for scale and maintainability

---

## 🧠 Key Topics To Explore

### 1. 🔧 Project Setup
- Initialize project: `npx nuxi init nuxt-news-portal`
- Install dependencies: `npm install`
- Dev server: `npm run dev`

### 2. 🌐 Pages & Routing
- Create static pages: homepage (`/`), about (`/about`)
- Dynamic routes:
    - `/article/[slug]`
    - `/category/[slug]`
- Use `definePageMeta()` and `useRoute()` for page-level data

### 3. ⚙️ Server-Side Data Fetching
- Use `useAsyncData()` and `useFetch()` for fetching from APIs
- Prefer server-side fetching for SEO-critical content
- Compare client-side vs SSR fetching in practice

### 4. 🧵 Server API Routes
- Create mock API endpoints in `/server/api/`
    - `GET /api/articles`
    - `GET /api/articles/[slug]`
    - `GET /api/categories`
- Use the server response in pages via composables or directly

### 5. 📦 State Management with Pinia
- Create a store for articles and categories
- Load and cache data in store
- Use `defineStore()` and `storeToRefs()`

### 6. 🧱 Layout System
- Create a global layout with header/footer/navigation
- Use `NuxtLayout` and `slot`
- Add visual differentiation between sections (e.g. category layout)

### 7. 🔐 Middleware & Route Guards
- Add middleware for protected routes (e.g. `/admin`)
- Use global or named middleware

### 8. 🔍 SEO & Meta Tags
- Use `useHead()` to set:
    - Page title & description
    - Open Graph (OG) and Twitter Card tags
- Generate dynamic meta tags based on article data

### 9. 🎨 Styling with Tailwind CSS
- Install and configure Tailwind CSS
- Create reusable components:
    - News cards
    - Category filters
    - Breadcrumbs
    - Article preview

### 10. 📤 Deployment
- Deploy to **Vercel** or **Netlify**
- Ensure `ssr: true` is set in `nuxt.config.ts`
- Test SEO performance with Lighthouse or `view-source:`

---

## ✅ Suggested Features to Implement

- [ ] Homepage with latest news
- [ ] Category pages with filtering
- [ ] Article detail pages with SSR and meta tags
- [ ] Responsive header/navigation
- [ ] Search field (client-side filter or fuzzy search)
- [ ] Simple admin page for creating/editing articles (optional)
- [ ] Dark mode toggle (optional)

---

## 🚀 Optional Enhancements

- Pagination for articles
- Article comments section (mocked)
- Tagging system
- Static content fallback using `.md` files and `@nuxt/content`
- Loading indicators and skeletons

---

## 📚 Recommended Resources

- [Nuxt 3 Documentation](https://nuxt.com/docs)
- [Nuxt Server API Routes](https://nuxt.com/docs/guide/directory-structure/server)
- [Nuxt useFetch & useAsyncData](https://nuxt.com/docs/getting-started/data-fetching)
- [Pinia Docs](https://pinia.vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [SEO in Nuxt](https://nuxt.com/docs/guide/directory-structure/app#head)

---

Take your time, explore, and don't be afraid to experiment.  
This project will give you hands-on experience with the full Nuxt stack.  
Good luck and have fun! 🎉
