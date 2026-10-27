<h1 align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=190&section=header&text=Mahmoud%20Khairy&fontSize=44&fontColor=ffffff&animation=fadeIn&desc=Senior%20Backend%20Engineer%20%C2%B7%20Laravel%20%C3%97%20Angular&descSize=18&descAlignY=68" width="100%" />
</h1>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&random=false&width=640&lines=Modular+Laravel+Architect;Multi-Tenant+E-commerce+at+Scale;API+Platform+%26+Performance+Engineering;Building+CartJoin+%F0%9F%9B%92" alt="Typing SVG" />
  </a>
</div>

<br />

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mahmoud--khairy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-khairy-753b841b4/)
[![Email](https://img.shields.io/badge/Email-mahmoudkhairy159%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mahmoudkhairy159@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B20%20111%20750%207344-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201117507344)
[![GitHub Followers](https://img.shields.io/github/followers/mahmoudkhairy159?style=for-the-badge&color=181717&logo=github)](https://github.com/mahmoudkhairy159)

</div>

---

### 👋 About

Senior Backend Engineer with **5+ years** designing Laravel/PHP platforms for marketplaces, SaaS, fleet operations, EdTech and multilingual content — and the full-stack range to ship the Angular dashboards that sit on top of them. I build **modular monoliths** with real domain boundaries, **multi-tenant architectures** on a single database, and API platforms that stay fast under load. Currently architecting **CartJoin**, a production multi-vendor e-commerce platform spanning a Laravel 12 modular backend and four Angular 22 applications.

<br />

## 🛒 Flagship — CartJoin Platform

> A multi-tenant, multi-vendor e-commerce marketplace: one modular Laravel backend, four purpose-built Angular frontends, isolated per-tenant data with per-tenant domains served through Cloudflare Tunnels.

| | |
|---|---|
| 🏪 **Storefront** | [cart-join.mahmoud-khairy.com](https://cart-join.mahmoud-khairy.com) — customer shopping experience |
| ⚙️ **API** | [app-cart-join.mahmoud-khairy.com](https://app-cart-join.mahmoud-khairy.com) — Laravel 12 modular monolith |
| 🛡️ **Admin** | [admin-cart-join.mahmoud-khairy.com](https://admin-cart-join.mahmoud-khairy.com) — platform-wide control |
| 🏢 **Tenant** | [tenant-cart-join.mahmoud-khairy.com](https://tenant-cart-join.mahmoud-khairy.com) — per-tenant management |
| 🚚 **Vendor** | [vendor-cart-join.mahmoud-khairy.com](https://vendor-cart-join.mahmoud-khairy.com) — vendor portal & settlements |

```text
 ┌────────────┐  ┌────────────┐  ┌────────────┐  ┌────────────┐
 │ Storefront │  │   Admin    │  │   Tenant   │  │   Vendor   │
 │ Angular 22 │  │ Angular 22 │  │ Angular 22 │  │ Angular 22 │
 └─────┬──────┘  └─────┬──────┘  └─────┬──────┘  └─────┬──────┘
       └───────────────┴───────┬───────┴───────────────┘
                        ┌──────┴───────┐
                        │  Laravel 12  │   JWT · 4 auth guards
                        │ Modular Mono │   RBAC/ACL per guard
                        └──────┬───────┘
                     ┌─────────┼─────────┐
                ┌────┴───┐ ┌───┴────┐ ┌──┴──────┐
                │ MySQL  │ │ Redis  │ │Stripe·FCM│
                └────────┘ └────────┘ └─────────┘
```

<details>
<summary><b>Architecture highlights</b> — click to expand</summary>

<br />

- **25+ domain modules** (`nwidart/laravel-modules`) — Cart, Order, Pricing, Wallet, Loyalty, Commission, Flash Sale, Recommendations… each with Controller → Service → Repository layering
- **Single-DB multitenancy** with absolute tenant isolation — `tenant_id` from resolved context, never the request; wrong-tenant reads return 404
- **Four JWT guards** (admin / tenant / vendor / user) with config-driven custom RBAC per surface
- **Full commerce engine**: pricing pipeline, coupons, gift cards, flash sales, wallets, loyalty points, settlements & commissions, invoices, refunds, shipments
- Deployed via **Cloudflare Tunnels** with per-tenant subdomain resolution

📁 **Repos:** [Backend](https://github.com/mahmoudkhairy159/Laravel-Multitenancy-Ecommerce-Single-DB) · [Storefront](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Storefront-Frontend) · [Admin](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Admin-Dashboard-Frontend) · [Tenant](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Tenant-Dashboard-Frontend) · [Vendor](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Vendor-Dashboard-Frontend)

</details>

<br />

## 🚀 Production Work

| Project | What it is | Stack |
|---|---|---|
| [Real Deal Egypt](https://apps.apple.com/eg/app/real-deal-egypt/id6754966163) 📱 | Car marketplace & bidding platform — vendor inventory, subscriptions, real-time bidding | Laravel 12 · Octane · MySQL · Redis · Stripe · FCM · S3 |
| [Edge](https://apps.apple.com/eg/app/edge-innovation-center/id6759037991) 📱 | Facility reservation API for Raya Smart Buildings | Laravel 12 · MySQL · Redis · Stripe · S3 |
| [Envirdian](https://www.envirdian.com) 🎓 | EdTech platform — gamified learning, tiered school licensing | Laravel 12 · Skolon SSO · Redis |
| [GeoFika](https://www.geofika.com) 🌍 | Multilingual geopolitical research platform | Laravel 12 · S3 · i18n |
| Al-Ouf 🚛 | Fleet & transportation ops — modular monolith, K8s deployed | Laravel 12 · Octane/Swoole · K8s |
| [Naya](https://nayauae.com) 🏢 | Corporate platform | Laravel · Next.js · TypeScript |

<br />

## 🧰 Toolbox

<div align="center">

**Backend**
![PHP](https://img.shields.io/badge/PHP_8.2--8.4-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_10--12-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-NestJS-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Data**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)

**Frontend**
![Angular](https://img.shields.io/badge/Angular_22-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React/Next.js-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

**Ops & Quality**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-366488?style=flat-square&logo=php&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

</div>

<br />

## 📊 GitHub Analytics

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mahmoudkhairy159&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9" alt="GitHub Stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=mahmoudkhairy159&hide_border=true&locale=en&background=0d1117&ring=1f6feb&fire=F0883E&currStreakLabel=58a6ff&dates=c9d1d9&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="GitHub Streak" />
</div>
<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahmoudkhairy159&layout=compact&hide_border=true&langs_count=8&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake.svg" />
</picture>

<br />

## 💼 Experience

| | Role | Period |
|---|---|---|
| 🔹 | **Senior Backend Developer** — MENT'ECH | Aug 2025 → Present |
| 🔹 | **Senior Backend Developer** — Wardlin | Nov 2023 → Present |
| 🔹 | **Backend Developer** — Tap | Jan 2025 → Aug 2025 |
| 🔹 | **Backend Developer** — Mushor Technology | Mar 2023 → Jan 2025 |
| 🔹 | **Software Engineer** — AbuDiyab IT Services | Jan 2023 → Nov 2023 |

🎓 **B.Sc. Computer Science** — Cairo University · A+ graduation project (*Fe Sektak* carpooling app)

<br />

<h2 align="center">📬 Let's build something</h2>

<div align="center">
Open to <b>senior backend</b>, <b>Laravel architecture</b>, <b>API platform</b> and <b>performance</b> roles.

<br /><br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-khairy-753b841b4/)
[![Email](https://img.shields.io/badge/Gmail-Say_Hi-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mahmoudkhairy159@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/201117507344)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=120&section=footer" width="100%" />
