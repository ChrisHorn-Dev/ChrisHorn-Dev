<h1 align="center">Chris Horn</h1>

<p align="center">
Engineer focused on building and stabilizing real-world SaaS systems — taking products from early builds to production-ready through debugging, system design, and operational hardening.
</p>

<p align="center">
<a href="https://chrisos.dev">Portfolio (ChrisOS)</a> •
<a href="https://github.com/ChrisHorn-Dev/case-studies">Case Studies</a> •
<a href="https://github.com/ChrisHorn-Dev/media-auth-api">Media Authenticity API</a> •
<a href="https://linkedin.com/in/chris-horn-5b70ab369">LinkedIn</a>
</p>

<p align="center">
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
</p>

<br>

# Featured Work

## Physician Connection Platform

Multi-tenant SaaS platform for rep–practice appointment coordination, scheduling, and operational workflows in a healthcare setting.  
*Source private; detailed technical write-up available in case study.*

`Next.js` · `React` · `TypeScript` · `Drizzle ORM` · `PostgreSQL` · `Vercel` · `Railway` · `Better Auth` · `Cal.com`

**System scope**

- Multi-role architecture spanning representatives, practice staff, physicians, and super-admins  
- Cal.com-backed scheduling workflows with domain-specific calendar behavior  
- Rep request pipeline with lifecycle visibility across dashboards and calendars  
- Authentication and authorization across role-partitioned system boundaries  
- Internal operational tooling for onboarding, debugging, and system support  

**Production hardening & stabilization**

- Resolved failures from using Drizzle’s `transaction()` API with Neon’s HTTP driver, which does not support interactive transactions — refactored to sequential writes with failure-safe cleanup  
- Fixed broken server-side authentication flows and enforced session validation across critical mutations  
- Strengthened role-based access boundaries across server actions and admin operations  
- Added Sentry error capture on critical server paths (e.g. user provisioning, practice setup, Cal proxy failures)  
- Stabilized booking and scheduling flows dependent on external systems (Cal.com)  
- Brought the platform from unstable production behavior → controlled beta readiness  

→ **[Read the case study](https://github.com/ChrisHorn-Dev/case-studies/blob/main/physician-connection.md)**

---

## Elite Touch Cleaning — Client & Operations Portal

Service operations system for a commercial cleaning business, supporting structured requests, emergency handling, and operational visibility.

`Next.js` · `React` · `TypeScript` · `Prisma` · `Twilio` · `Resend`

**Key areas of work**

- Typed request lifecycle (issues, notes, supplies) with threaded messaging, attachments, and status tracking  
- Emergency (SOS) workflow with priority escalation and broadcast notification pipeline (SMS + email)  
- Admin triage interface with filtered queues, request detail views, and operational visibility  
- Manual SMS check-in system and admin-triggered HubSpot contact synchronization  

→ **[Read the case study](https://github.com/ChrisHorn-Dev/case-studies/blob/main/elite-touch-cleaning.md)**

---

## Media Authenticity API

Verification API for analyzing uploaded images and returning structured, signed authenticity records.

`Next.js` · `TypeScript` · `Node.js`

**Core capabilities**

- Detector-driven analysis pipeline supporting single and ensemble modes  
- File-hash caching with optional persistence  
- HMAC-signed authenticity responses with verification endpoint (`POST /api/verify`)  
- In-memory rate limiting and optional API key enforcement  
- Tests covering core analysis and verification behavior  

→ **[View repository](https://github.com/ChrisHorn-Dev/media-auth-api)**

---

## ChrisOS (Resume OS)

Desktop-style portfolio system built as a browser-based workspace with windowed applications and shared state.

`Next.js` · `TypeScript` · `Tailwind CSS` · `Zustand` · `Framer Motion`

**Architecture highlights**

- Window manager with dock, launcher, menu bar, and multi-window coordination  
- Mobile-adapted shell with responsive navigation and app structure  
- Shared state model for window lifecycle and payload-driven navigation  
- Terminal interface integrated into the same application model  
- Structured content system for project deep dives and documentation  

→ **[Open ChrisOS](https://chrisos.dev)** • **[View repository](https://github.com/ChrisHorn-Dev/resume-os)**

---

<br>

# About

I build software that supports real operational workflows — SaaS platforms, scheduling systems, and internal tools used by actual teams.

My work focuses on taking systems from early builds to production-ready: diagnosing failures, tightening architecture, and making behavior predictable under real-world conditions.

I’m particularly interested in product engineering at the system level — where application logic, infrastructure constraints, and real user workflows intersect.

---

# Tech Stack

`Next.js` · `React` · `TypeScript` · `Node.js` · `Tailwind CSS`  
`PostgreSQL` · `Prisma` · `Drizzle ORM` · `Vercel`

---

# Connect

Always happy to talk about SaaS systems, APIs, and product engineering.

<p>
<a href="https://linkedin.com/in/chris-horn-5b70ab369">LinkedIn</a> •
<a href="https://chrisos.dev">Portfolio</a> •
<a href="https://github.com/ChrisHorn-Dev/media-auth-api">Media Authenticity API</a>
</p>
