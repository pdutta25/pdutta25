<div align="center">


🔗 [![Portfolio](https://img.shields.io/badge/Portfolio-pdutta25.github.io-FF6B35?style=for-the-badge&logo=github&logoColor=white)](https://pdutta25.github.io)


</div>

---

### Shipped for Fun, Built to Learn

<table>
<tr>
<td width="50%" valign="top">

#### ☀️ Is It Nice (out there)?

![LOC](https://img.shields.io/badge/10k+_LOC-0d1117?style=flat-square) ![Stack](https://img.shields.io/badge/React_+_Vite_+_Tailwind_+_CF_Workers-FFAB40?style=flat-square&logoColor=white) ![Repo](https://img.shields.io/badge/Private_Repo-555?style=flat-square)

**Live:** [isitnice.app](https://isitnice.app) &nbsp;|&nbsp; Private Repo ☕🤖

Like texting a buddy who's already outside: *"Hey, is it nice?"*

**Hell yes.** Or **Nope.** Or **Whatever else.**

Not your dad's radar-cluttered app. One 'nice' score. AI powered Scoring Algorithm. Real-time Models. Sassy Briefings.

<details>
<summary><strong>See what's under the hood</strong></summary>

<br/>

- **Real-time intelligence** from the top 3 pro models (NOAA + ECMWF + GFS)
- **One smart Nice Score** — one algorithm, one crystal-clear verdict you can trust
- **Not your dad's radar-cluttered app** — no 47 confusing data points (sorry, Dad; nobody reads those charts lol)
- **AI algo that actually motivates you** — roasts you into going outside with sassy daily briefings
- **Custom comfort thresholds** + instant severe weather alerts
- **100% free** · **Zero ads** · **Zero BS**

**Best part?** It's a lightning-fast **PWA** — just tap "Add to Home Screen" and it feels & works exactly like a native app. No App Store. No downloads. Instant access everywhere.

This isn't your dad's weather app.
This is the fun, addictive daily companion that makes you excited to step outside.

Simple. Smart. Addictive.

*If it makes someone's day a little easier, that's the whole point.*

</details>

</td>
<td width="50%" valign="top">

#### 🚲 DevEx Bike Shop

![LOC](https://img.shields.io/badge/37k+_LOC-0d1117?style=flat-square) ![Stack](https://img.shields.io/badge/Next.js_14_+_TypeScript_+_Drizzle_+_SQLite-FFAB40?style=flat-square&logoColor=white) ![Repo](https://img.shields.io/badge/Public_Repo-58A6FF?style=flat-square)

**Live:** [devexbikeshop.com](https://devexbikeshop.com) &nbsp;|&nbsp; [View Repo](https://github.com/pdutta25/devex-bike-shop) ☕🤖

An e-commerce app nobody buys from. Seeded catalog, mocked payments, no real transactions. First full build co-authored with Claude - turns out human + AI can co-create worthwhile things really well !

MCP Agents. GitHub Actions + Harness CI/CD. Security/Quality baked in. Observability. Commit telemetry and traceability — push to prod.

<details>
<summary><strong>See what's under the hood</strong></summary>

<br/>

**What it actually does:**
- Sleek dark-themed storefront with 48 bikes across 8 categories
- Detailed product pages with custom SVG illustrations
- Persistent shopping cart (size + color options)
- Wishlist, search, and mock checkout flow
- Full admin dashboard: sales KPIs, Recharts revenue graphs, order management, product CRUD, inventory tracking with low-stock alerts, and one-click data seeding

**Tech Stack:** Next.js 14+ (App Router), TypeScript, Drizzle ORM + SQLite, Tailwind CSS, Zod validation, Recharts, and more.

---

**MCP Agents**
- Dedicated `mcp-server/` with 4 powerful agents: `get-app-context`, `list-components`, `scaffold-feature`, `revert-feature`
- Integrated **VS Code Copilot Agent Mode**
- Teaches Copilot your codebase architecture, design system, and test patterns
- Accelerates feature development and enables safe rollbacks during rapid iteration

---

**CI/CD Pipeline (fully automated & AI-assisted):**

**Continuous Integration (CI) with GitHub Actions**
- Triggers on every push and pull request to `main`
- Production build with artifact upload
- ESLint linting, 67 Vitest unit tests
- Security scans (Trivy filesystem + npm audit)
- Code quality analysis with SonarCloud
- 📦 Fake JFrog Artifactory publish (13 components published one-by-one)
- ✅ Compliance stage (SBOM generation, signature verification, license & CVE checks, deployment attestation)
- 🤖 Dependabot Audit (queries all merged Dependabot PRs with direct links)
- 📝 AI-generated release notes
- 📚 Auto-generated Wiki docs (published to GitHub Wiki)
- Rich `$GITHUB_STEP_SUMMARY` markdown reports on every job
- GitHub Release automatically created with full CI results
- Smart features: path filtering, concurrency groups, AI-powered PR reviews

**Continuous Deployment (CD) with Harness**
- 4 release pipelines: **Spring Sale**, Gated, Unified, APR
- 5-stage structure: **Start → DEV → STG → PROD → End**
- Real-time write-back to GitHub Releases from Harness
- **Start Stage**: Trigger validation, manifest processing, telemetry initialization (59 data points per component ~ 600 for pipeline), release strategy selection
- **End Stage**: Release summary, full traceability record, governance checks, telemetry aggregation (including DORA metrics)
- 13-component deployment (Backend + Frontend groups)
- Full observability, audit trail, and notifications throughout

**Release Strategy System**
- Config-driven routing: **Solo / Gated / Unified**
- `manifest-13.json` as the single source of truth for all 13 components

The entire pipeline — from first line of code to production deployment — was heavily powered by **AI/Copilot**, showcasing modern DevEx development practices.

*No bikes were made, sold, or harmed in the making of this project.* 🚲

---

**Storefront Features**
- Homepage — Hero section, featured bikes, category grid, promo banner
- Catalog — Browse 48 bikes across 8 categories with sort and filter options
- Product Detail — SVG bike illustrations, specs table, customer reviews, related products
- Shopping Cart — Server-persisted cart with size/color selection
- Checkout — Delivery/pickup toggle, shipping address, mock payment form
- Order Tracking — Order history with visual status timeline
- Wishlist — Save bikes for later
- Search — Full-text product search
- Account — Cookie-based customer identification (no passwords)

**Admin Dashboard**
- KPI Cards — Total revenue, orders, average order value, product count
- Revenue Chart — 30-day revenue trend (Recharts)
- Order Management — View all orders, update status, cancel orders
- Product CRUD — Create, edit, delete products with full spec management
- Inventory — Stock levels, low-stock alerts, inline stock updates
- Reports — Revenue trends, top products, orders by status, category performance
- Data Seeding — One-click seed/reset with progress indicators

**Design**
- Dark Theme — Deep charcoal (`#0f0f1a`) with amber accent (`#f59e0b`)
- Glassmorphism — Frosted glass header with scroll detection
- SVG Illustrations — Category-themed bike illustrations (no external images)
- Responsive — Mobile, tablet, and desktop layouts
- Animations — Fade-in, hover effects, gradient shifts, glow shadows

</details>

</td>
</tr>
</table>

---

### 

<div align="center">

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=pdutta25&theme=dark&background=0d1117&ring=FFAB40&fire=FF6B35&currStreakLabel=FFAB40&sideLabels=f5e6d8&dates=a07858&border=3a1f0e)

</div>

---

### Achievements Unlocked

<table>
<tr>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/drknzz/GitHub-Achievements/main/Media/Badges/Pull-Shark/PNG/PullShark_Gold.png" width="120"/>
<br/>
<strong>Pull Shark</strong>
<br/>
<img src="https://img.shields.io/badge/🥇_GOLD-135_merged_PRs-FFAB40?style=for-the-badge&labelColor=0d1117"/>
<br/><br/>
<sub>Earned by merging accepted pull requests.</sub>
<br/>
<sub>🥉 2 &nbsp;→&nbsp; 🥈 16 &nbsp;→&nbsp; 🥇 128 &nbsp;→&nbsp; 🏅 1,024</sub>
<br/>
<sub><strong>Next: Platinum at 1,024 PRs</strong></sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/drknzz/GitHub-Achievements/main/Media/Badges/Pair-Extraordinaire/PNG/PairExtraordinaire_Gold.png" width="120"/>
<br/>
<strong>Pair Extraordinaire</strong>
<br/>
<img src="https://img.shields.io/badge/🏅_PLATINUM_x2-727_co--authored-FF6B35?style=for-the-badge&labelColor=0d1117"/>
<br/><br/>
<sub>Earned by co-authoring commits on merged PRs.</sub>
<br/>
<sub>🥉 1 &nbsp;→&nbsp; 🥈 10 &nbsp;→&nbsp; 🥇 24 &nbsp;→&nbsp; 🏅 48</sub>
<br/>
<sub><strong>Maxed out. Absolute unit.</strong></sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/drknzz/GitHub-Achievements/main/Media/Badges/YOLO/PNG/YOLO_Badge.png" width="120"/>
<br/>
<strong>YOLO</strong>
<br/>
<img src="https://img.shields.io/badge/✅_UNLOCKED-135_no--review_merges-58A6FF?style=for-the-badge&labelColor=0d1117"/>
<br/><br/>
<sub>Earned by merging a PR without code review.</sub>
<br/>
<sub>No tiers — you either live dangerously or you don't.</sub>
<br/>
<sub><strong>I chose violence. 135 times.</strong></sub>
</td>
</tr>
</table>

---

### Tier Guide

```
🥉 Bronze      Just getting started
🥈 Silver      Consistent contributor
🥇 Gold        Serious builder
🏅 Platinum    Elite tier — x2, x3, x4 multipliers at scale
```

<sub>GitHub displays your highest tier earned. Higher tiers replace lower ones on your profile.</sub>

---

<div align="center">

*1,226 commits · 135 merged PRs · built with ☕ and an AI that doesn't sleep*

</div>
