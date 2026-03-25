<!-- <img src="github-header.png" width="100%"/> -->

GitHub gives me 80 chars. I needed more space. 👉 https://pdutta25.github.io


## 📌 Pinned

---

# ☀️ Is it Nice (out there) ? 

**10k lines of code**  
**Creator: Caffeine, Claude and me** ☕🤖

**Live App:** [https://isitnice.app](https://isitnice.app)
  
Like texting a buddy who's already outside:  
"Hey, is it nice?"

**Hell yes.** Or **Nope.** Or **Whatever else**

- **Real-time intelligence** from the top 3 pro models (NOAA + ECMWF + GFS)  
- **One smart Nice Score** — one algorithm, one crystal-clear verdict you can trust  
- **Not your dad's radar-cluttered app** — no 47 confusing data points (sorry, Dad ; nobody reads those charts lol)
- **AI algo that actually motivates you** — roasts you into going outside with sassy daily briefings  
- **Custom comfort thresholds** + instant severe weather alerts  
- **100% free** • **Zero ads** • **Zero BS**

**Best part?** It's a lightning-fast **PWA** — just tap “Add to Home Screen” and it feels & works exactly like a native app. No App Store. No downloads. Instant access everywhere.

This isn’t your dad’s weather app.  
This is the fun, addictive daily companion that makes you excited to step outside.

Simple. Smart. Addictive.

If it makes someone's day a little easier, that's the whole point.

---

# 🚲 DevEx Bike Shop

**37k lines of code**  
**Creator: Caffeine, Claude and me** ☕🤖

**Live App:** [https://devexbikeshop.com](https://devexbikeshop.com)

<details>
<summary>😏 Click here for more ... (spoiler: It's very 2026ish .. zero 1960s vibes)</summary>


A full-stack demo e-commerce website for a premium bike shop, built as a complete **developer experience (DevEx)** showcase.  


#### What it actually does:
- Sleek dark-themed storefront with 48 bikes across 8 categories  
- Detailed product pages with custom SVG illustrations  
- Persistent shopping cart (size + color options)  
- Wishlist, search, and mock checkout flow  
- Full admin dashboard: sales KPIs, Recharts revenue graphs, order management, product CRUD, inventory tracking with low-stock alerts, and one-click data seeding  

**Tech Stack**: Next.js 14+ (App Router), TypeScript, Drizzle ORM + SQLite, Tailwind CSS, Zod validation, Recharts, and more.

#### MCP Agents
- Dedicated `mcp-server/` with 4 powerful agents:  
  `get-app-context`, `list-components`, `scaffold-feature`, `revert-feature`  
- Integrated **VS Code Copilot Agent Mode**  
- Teaches Copilot your codebase architecture, design system, and test patterns  
- Accelerates feature development and enables safe rollbacks during rapid iteration  

#### CI/CD Pipeline (fully automated & AI-assisted):

- **Continuous Integration (CI) with GitHub Actions**  
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
  - Demo storyline embedded directly in deploy logs  
  - Smart features: path filtering, concurrency groups, AI-powered PR reviews  

- **Continuous Deployment (CD) with Harness**  
  - 4 release pipelines: **Spring Sale**, Gated, Unified, APR  
  - 5-stage structure: **Start → DEV → STG → PROD → End**  
  - Real-time write-back to GitHub Releases from Harness  
  - **Start Stage**: Trigger validation, manifest processing, telemetry initialization (59 data points per component), release strategy selection  
  - **End Stage**: Release summary, full traceability record, governance checks, telemetry aggregation (including DORA metrics)  
  - Real Render deploy for the storefront in PROD  
  - 13-component deployment (Backend + Frontend groups)  
  - Full observability, audit trail, and notifications throughout  

- **Release Strategy System**  
  - Config-driven routing: **Solo / Gated / Unified**  
  - `manifest-13.json` as the single source of truth for all 13 components  

The entire pipeline — from first line of code to production deployment — was heavily powered by **AI/Copilot**, showcasing modern DevEx with modern development practices.

No bikes were made, sold, or harmed in the making of this project.  🚲

---

## Bikeshop Features

### Storefront
- **Homepage** — Hero section, featured bikes, category grid, promo banner
- **Catalog** — Browse 48 bikes across 8 categories with sort and filter options
- **Product Detail** — SVG bike illustrations, specs table, customer reviews, related products
- **Shopping Cart** — Server-persisted cart with size/color selection
- **Checkout** — Delivery/pickup toggle, shipping address, mock payment form
- **Order Tracking** — Order history with visual status timeline
- **Wishlist** — Save bikes for later
- **Search** — Full-text product search
- **Account** — Cookie-based customer identification (no passwords)

### Admin Dashboard
- **KPI Cards** — Total revenue, orders, average order value, product count
- **Revenue Chart** — 30-day revenue trend (Recharts)
- **Order Management** — View all orders, update status, cancel orders
- **Product CRUD** — Create, edit, delete products with full spec management
- **Inventory** — Stock levels, low-stock alerts, inline stock updates
- **Reports** — Revenue trends, top products, orders by status, category performance
- **Data Seeding** — One-click seed/reset with progress indicators

### Design
- **Dark Theme** — Deep charcoal (`#0f0f1a`) with amber accent (`#f59e0b`)
- **Glassmorphism** — Frosted glass header with scroll detection
- **SVG Illustrations** — Category-themed bike illustrations (no external images)
- **Responsive** — Mobile, tablet, and desktop layouts
- **Animations** — Fade-in, hover effects, gradient shifts, glow shadows

---

</details>



