<a href="https://github.com/mahmoudkhairy159">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:1F6FEB,100:2980B9&height=200&section=header&text=Mahmoud%20Khairy&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Senior%20Backend%20Engineer&descSize=20&descAlignY=60&animation=fadeIn" width="100%" />
</a>

<div align="center">
  <a href="https://github.com/mahmoudkhairy159?tab=repositories">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&pause=1400&color=1F6FEB&center=true&vCenter=true&width=620&lines=Modular+Laravel+architecture.;Multi-tenant+e-commerce+at+scale.;APIs+that+stay+fast+under+load.;Building+CartJoin." alt="typing" />
  </a>
</div>

<br />

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-khairy-753b841b4/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mahmoudkhairy159@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201117507344)

</div>

<br />

| Since 2019 | 25+ | 5 live surfaces | 10+ |
| :---: | :---: | :---: | :---: |
| **building and shipping**<br>production Laravel platforms | **domain modules**<br>in one modular monolith | **one platform,**<br>four Angular apps + an API | **platforms in production**<br>marketplaces, SaaS, EdTech, fleets |

<br />

> **Now:** Senior Backend Developer at **MENT'ECH**, architecting **CartJoin** — a multi-tenant, multi-vendor e-commerce marketplace: one Laravel 12 modular monolith, four purpose-built Angular 22 frontends, per-tenant domains through Cloudflare.

## What I do

I design backend systems the way they need to be built to survive real businesses: **modular monoliths** with genuine domain boundaries instead of tangled single-app codebases, **single-database multitenancy** where tenant isolation is absolute, and API platforms that hold their response times as usage grows. Five-plus years shipping marketplaces, SaaS products, fleet operations, EdTech and multilingual content platforms — with the full-stack range to build the Angular dashboards that sit on top of them.

<br />

## CartJoin — flagship platform

| | |
|---|---|
| 🏪 [**Storefront**](https://cart-join.mahmoud-khairy.com) | The customer shopping experience |
| ⚙️ [**API**](https://app-cart-join.mahmoud-khairy.com) | Laravel 12 modular monolith — 25+ domain modules |
| 🛡️ [**Admin**](https://admin-cart-join.mahmoud-khairy.com) | Platform-wide control plane |
| 🏢 [**Tenant**](https://tenant-cart-join.mahmoud-khairy.com) | Per-tenant business management |
| 🚚 [**Vendor**](https://vendor-cart-join.mahmoud-khairy.com) | Vendor portal, orders & settlements |

```text
 ┌────────────┐ ┌────────────┐ ┌────────────┐ ┌────────────┐
 │ Storefront │ │   Admin    │ │   Tenant   │ │   Vendor   │
 │ Angular 22 │ │ Angular 22 │ │ Angular 22 │ │ Angular 22 │
 └─────┬──────┘ └─────┬──────┘ └─────┬──────┘ └─────┬──────┘
       └──────────────┴──────┬───────┴──────────────┘
                      ┌──────┴───────┐
                      │  Laravel 12  │ 4 JWT guards · per-guard RBAC
                      │ modular mono │ absolute tenant isolation
                      └──────┬───────┘
                ┌────────┬───┴────┬──────────┐
             ┌──┴───┐ ┌──┴───┐ ┌──┴─────┐ ┌──┴───────┐
             │MySQL │ │Redis │ │ Stripe │ │ Cloudflare│
             └──────┘ └──────┘ └────────┘ │  Tunnels  │
                                          └──────────┘
```

<details>
  <summary><b>How it's built</b> — the engineering decisions</summary>

  <br />

  - **Domain boundaries that hold** — Cart, Order, Pricing, Wallet, Loyalty, Commission, Flash Sale, Recommendations and 17 more modules, each with strict Controller → Service → Repository layering
  - **Multitenancy done properly** — `tenant_id` resolves from context, never the request; cross-tenant reads return 404; uniques are per-tenant, not global
  - **Commerce engine, end to end** — pricing pipeline, coupons, gift cards, flash sales, wallets, loyalty, settlements & commissions, invoices, refunds, shipments
  - **Per-tenant domains** — subdomain resolution maps each tenant to its storefront through Cloudflare Tunnels

  📁 [Backend](https://github.com/mahmoudkhairy159/Laravel-Multitenancy-Ecommerce-Single-DB) · [Storefront](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Storefront-Frontend) · [Admin](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Admin-Dashboard-Frontend) · [Tenant](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Tenant-Dashboard-Frontend) · [Vendor](https://github.com/mahmoudkhairy159/Angular-Multitenancy-Ecommerce-Vendor-Dashboard-Frontend)

</details>

<br />

## Selected work

| | |
|---|---|
| **[Real Deal Egypt](https://apps.apple.com/eg/app/real-deal-egypt/id6754966163)** 📱 | Car marketplace with vendor inventory, subscriptions and live bidding — on the App Store. |
| **[Edge](https://apps.apple.com/eg/app/edge-innovation-center/id6759037991)** 📱 | Facility reservation API where a confirmed booking opens the physical door — Raya Smart Buildings. |
| **[Envirdian](https://www.envirdian.com)** 🎓 | EdTech platform with gamified learning and tiered school licensing across Europe. |
| **[GeoFika](https://www.geofika.com)** 🌍 | Multilingual geopolitical research platform — articles, events, initiatives. |
| **Al-Ouf** 🚛 | Fleet & transportation operations as a modular monolith, Kubernetes-deployed. |
| **[Naya](https://nayauae.com)** 🏢 | Corporate platform — Laravel backend, Next.js frontend. |

<br />

## Stack

| | |
|---|---|
| **Backend** | <img src="https://skillicons.dev/icons?i=php,laravel,laravel&no-bg" height="18" alt=""> &nbsp; PHP 8.2–8.4 · Laravel 10–12 · REST APIs · NestJS |
| **Data** | <img src="https://skillicons.dev/icons?i=mysql,redis,mongo&no-bg" height="18" alt=""> &nbsp; MySQL · Redis · Oracle DB |
| **Frontend** | <img src="https://skillicons.dev/icons?i=angular,ts,react,vue&no-bg" height="18" alt=""> &nbsp; Angular 22 · TypeScript · React/Next.js · Vue |
| **Cloud & Ops** | <img src="https://skillicons.dev/icons?i=docker,k8s,gitlab,aws&no-bg" height="18" alt=""> &nbsp; Docker · Kubernetes · GitLab CI/CD · AWS S3 |
| **Payments & Integrations** | Stripe · Firebase FCM · JWT · Skolon SSO |
| **Quality** | PHPUnit · code review culture · clean architecture · performance profiling |

<br />

## Career

**Since 2019, across five companies.**

| When | Role | Where |
| :--- | :--- | :--- |
| 2025 → now | Senior Backend Developer | MENT'ECH |
| 2023 → now | Senior Backend Developer | Wardlin |
| 2025 | Backend Developer | Tap |
| 2023 → 2025 | Backend Developer | Mushor Technology |
| 2023 | Software Engineer | AbuDiyab IT Services |

🎓 B.Sc. Computer Science — Cairo University · graduation project graded **A+** (*Fe Sektak*, carpooling platform)

<br />

<img height="150" src="https://github-readme-stats.vercel.app/api?username=mahmoudkhairy159&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=00000000&title_color=1F6FEB&icon_color=1F6FEB&text_color=8b949e&hide_rank=true" alt="GitHub stats" align="center" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/mahmoudkhairy159/mahmoudkhairy159/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

<br />

## Let's work together

Open to **senior backend, Laravel architecture and API platform roles**, and available for **performance consulting and technical reviews**. Based in Cairo (EET, UTC+3), working remote-first across Egypt, the Gulf and internationally.

<div align="center">

[![Start a conversation](https://img.shields.io/badge/Start_a_conversation-1F6FEB?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:mahmoudkhairy159@gmail.com)

</div>

<br />

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:2980B9,100:1F6FEB&height=110&section=footer" width="100%" />
