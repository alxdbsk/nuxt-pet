# 📰 NewsCraft – SSR News Portal (Nuxt 3 Pet Project)

## 🚀 Goal

This project simulates the architecture of a real-world, high-traffic news portal with **400k daily users**. It is built using **Nuxt 3** and focuses on **Server-Side Rendering (SSR)**, SEO, performance optimization, and developer workflows.

The goal is to train a Junior Frontend Developer to understand SSR deeply and to gain practical experience with scalable architecture, rendering strategies, data fetching, caching, and deployment.

---

## 📦 Stack

- **Nuxt 3** with Nitro (SSR)
- **Vue 3 Composition API**
- **Tailwind CSS**
- **Pinia** (State Management)
- **Public Mock API**

---

## 🧩 Key Features to Implement

| Feature | Purpose |
|--------|---------|
| SSR-rendered homepage with news list | Learn `asyncData`, SSR fetch lifecycle |
| Dynamic article pages by `slug` | Dynamic routing, meta tags, head setup |
| Categories and tags pages | Filtering via query and dynamic routes |
| Search page (SSR) | Query handling, debounce, SSR API calls |
| Pagination | Query params, slicing, SSR rendering |
| Sitemap.xml | Server route, SEO |
| RSS Feed | Server route, content generation |
| 404 and error pages | Nuxt error handling, fallback logic |
| Middleware for logging/auth | Learn Nuxt middlewares |
| Admin login (client-side route) | Auth guard, layout switching |
| Page view tracking (basic analytics) | Middleware, server route logging |
| Caching for popular pages (optional) | SSR output caching (in-memory or Redis) |
| ISR-like refresh strategy | Manual or automated revalidation |

---

## 🎓 Learning Outcomes

- SSR vs CSR vs SSG vs ISR
- Nuxt `asyncData`, `useFetch`, `definePageMeta`, `defineNuxtRouteMiddleware`
- Page-level and layout-level rendering flows
- API consumption (public or internal)
- Content-based routing, SEO techniques, canonical/meta/og tags
- Middleware structure (auth, logging)
- Error and fallback rendering in Nuxt
- Sitemap and RSS generation
- SSR caching strategies

---

## ✅ Milestones

- [ ] Project setup with Nuxt 3, Tailwind, API integration
- [ ] Home + dynamic article page (SSR)
- [ ] Search, category filter, pagination
- [ ] Sitemap and RSS
- [ ] Admin routes and middleware
- [ ] SEO meta and OpenGraph tags
- [ ] Caching and performance profiling
