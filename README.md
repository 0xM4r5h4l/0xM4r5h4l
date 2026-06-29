<div align="center">

# Hey, I'm Mostafa Abdelrazek 👋
### Laravel Backend Developer | Ex-Security Researcher (IBM Discloser) | SaaS Developer

<p>
  <img src="https://img.shields.io/badge/PHP-8.2+-090A0F?style=flat-square&logo=php&logoColor=777BB4&labelColor=090A0F" />
  <img src="https://img.shields.io/badge/Laravel-12-090A0F?style=flat-square&logo=laravel&logoColor=FF2D20&labelColor=090A0F" />
  <img src="https://img.shields.io/badge/MySQL-Primary%20Store-090A0F?style=flat-square&logo=mysql&logoColor=4479A1&labelColor=090A0F" />
  <img src="https://img.shields.io/badge/Filament-Admin%20Panels-090A0F?style=flat-square&logo=php&logoColor=FDAE4B&labelColor=090A0F" />
  <img src="https://img.shields.io/badge/Docker-Deployment-090A0F?style=flat-square&logo=docker&logoColor=2496ED&labelColor=090A0F" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-Styling-090A0F?style=flat-square&logo=tailwindcss&logoColor=06B6D4&labelColor=090A0F" />
</p>

</div>

---

### 🚀 About Me

I write Laravel backends the way I'd want to inherit them: typed, layered, and hard to break by accident.
 
One year in professionally, but the way I work doesn't read like a first-year project — `Service Layer` between controllers and Eloquent, `DTOs` at every boundary instead of loose arrays, and a habit of asking *"what happens when a tenant tries to read another tenant's data"* before I write the happy path.
 
I write 100% of my own backend code. I use AI tooling for frontend implementation (Blade/Tailwind), which lets me put my actual hours into the part I care about: how the system is built underneath.

```
🌍  Cairo, Egypt (UTC+2) — open to remote / contract roles
📦  Currently shipping a confidential enterprise multi-tenant SaaS platform
```

#### ⚡ What I Bring to Your Team:
* **Clean Architecture:** Keeping controllers thin by routing business logic through Services and using strongly-typed DTOs.
* **Database & Performance:** Heavily utilizing eager loading to eliminate N+1 query problems, alongside effective caching strategies to prevent bottlenecks.
* **Multi-Tenancy:** Managing strict tenant isolation (database, cache, and filesystem) dynamically based on the active domain.
* **Security & Auth:** Building custom OAuth flows on top of Laravel Breeze and implementing telemetry layers to protect sessions against hijacking.
* **AI-Assisted Efficiency:** Using AI tools to quickly build and prototype frontends (Blade & Tailwind) to keep my focus on backend architecture.

---
 
### Current Focus
 
- 🏗️ Deepening multi-tenant architecture patterns — tenant isolation at the data, cache, and filesystem layers
- 🔐 Security-first backend design — custom OAuth flows, token encryption, abuse/hijacking detection
- ⚡ Performance under load — eager loading discipline, cache stampede prevention, deferred service providers
- 🧱 Clean architecture in PHP/Laravel — Service Layer + DTOs as the default, not an afterthought
<!-- - 🛡️ Security research: [add real detail here if applicable — program name, what was reported, acknowledgment status] -->
 
---

### How I Build
 
| Layer | Approach |
|---|---|
| **Controllers** | Thin. Validate, delegate, respond. No business logic. |
| **Service Layer** | Owns the business logic. Testable independent of HTTP and Eloquent. |
| **DTOs** | Typed data crossing every layer boundary — no untyped arrays passed between services. |
| **Multi-Tenancy** | Tenant context resolved via middleware on every request; isolation enforced at query, cache, and filesystem level. |
| **Security** | Tenant-scoped authorization on every query; encrypted tokens; session anomaly checks. |
| **Performance** | Eager loading by default (zero N+1), Redis-backed caching with jitter to prevent stampede, deferrable providers to keep cold boot fast. |
 
---
 
### Stack
 
<p>
  <img src="https://skillicons.dev/icons?i=php,laravel,mysql,tailwind,docker,nginx,git&theme=dark" />
</p>

---
 
### Featured Project
 
**Multi-Tenant SaaS Platform** — *Enterprise engagement (NDA — implementation private, architecture below is public)*
 
A multi-tenant SaaS platform supporting three distinct roles — **System Owner**, **Merchant**, and **Client** — each scoped to its own permissions, data, and workflows, structurally similar to Shopify's tenancy model.
 
- Multi-tenancy via dynamic filesystem/cache isolation + tenant middleware on every request
- Custom multi-tenant OAuth flow with AES-256 token encryption and session anomaly telemetry
- MVC + Service Layer + DTOs, with Eloquent polymorphic relationships where domains genuinely overlap
- Zero N+1 by default (eager loading enforced), cache stampede prevention via jitter, deferrable service providers
📄 Full architecture write-up (no source code, per NDA): **[link to your case-study doc]**


---


## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=0xM4r5h4l&show_icons=true&theme=dark&hide_border=true&bg_color=09090b&title_color=34d399&icon_color=818cf8&text_color=a1a1aa" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=0xM4r5h4l&theme=dark&hide_border=true&background=09090b&stroke=18181b&ring=34d399&fire=818cf8&currStreakLabel=34d399" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xM4r5h4l&layout=compact&theme=dark&hide_border=true&bg_color=09090b&title_color=34d399&text_color=a1a1aa" width="40%" />

</div>

<br>

## 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mustafa-abdelrazek)
[![Portfolio](https://img.shields.io/badge/Portfolio-09090b?style=for-the-badge&logo=googlechrome&logoColor=34d399)](https://#)

</div>
