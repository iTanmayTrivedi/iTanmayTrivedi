<div align="center">

# Tanmay Trivedi
### Full-Stack Developer building production-grade software for the Japanese market

*"言葉より、コードで語る。"* — *Let the code speak louder than words.*

**Kanpur, India → Japan** · Open to Bridge Engineer / Full-Stack roles · shinsotsu 2029

</div>

<br>

```
$ whoami
> Tanmay Trivedi — Full-Stack Developer, Kanpur, India
> B.Tech Biotechnology, Rama University — Class of 2029
> Building bilingual, production-grade software for the Japanese market
> JLPT N1 — in progress
> Target: Bridge Engineer / Full-Stack Developer, shinsotsu 2029
```

<br>

### Contents
[About](#about) · [Currently Building](#currently-building) · [Flagship Project](#flagship-project) · [Projects](#projects) · [By the Numbers](#by-the-numbers) · [How I Build](#how-i-build) · [Research](#research) · [Certifications](#certifications) · [Tech Stack](#tech-stack) · [Japan Journey](#japan-journey) · [Hobbies Corner](#hobbies-corner) · [Reach Me](#reach-me)

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## About

I'm a full-stack developer from Kanpur, India, completing a B.Tech in Biotechnology while building bilingual, production-grade software aimed squarely at the Japanese market. I'm preparing for JLPT N1 and targeting **Bridge Engineer / Full-Stack Developer** roles at Japanese tech companies ahead of my June 2029 graduation.

Every project below ships with the same non-negotiables: full EN/日本語 parity, Postgres Row-Level Security on every public table, server-side AI with no exposed keys, and a demo a recruiter can evaluate in under a minute — no signup required.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Currently Building

**Lynt**
Japan career & relocation SaaS — bilingual onboarding, a JIS-compliant Rirekisho builder, a 30+ visa-type eligibility engine, and AI-assisted resume tooling for international talent moving to Japan.
`14+ onboarding routes` `30+ visa types modeled` `20+ production screens` `6 RLS-secured tables`

**悠 Yuki AI — "Think Deeper."**
A Japan-specialist bilingual AI assistant with multi-provider fallback, honorific register handling, and a custom intent classifier.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Flagship Project

### 楽天市場 — Rakuten Ichiba, Reimagined

A full-stack marketplace built to reproduce the patterns that make Japanese e-commerce structurally different from Western retail: points-first pricing, seller-first storefronts, information-dense layouts, and Japanese as the source of truth for every UI string.

`React 18` `TypeScript (strict)` `Supabase` `9 tables, 100% RLS coverage` `23 bilingual routes` `AI shopping assistant + seller/admin AI tools` `Sub-1.5s first paint via mock-data fallback`

**[→ View the repo](https://github.com/iTanmayTrivedi/RakutenJapan)**

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Projects

| Project | What it does | Highlights |
|---|---|---|
| [**Rakuten Reimagined**](https://github.com/iTanmayTrivedi/RakutenJapan) | Bilingual e-commerce marketplace clone with multi-role auth and AI shopping/seller tools | 23 routes · 9 RLS-secured tables · AI shopping assistant, SEO copy, BI insights |
| **Lynt** *(private)* | Bilingual career & relocation OS for international talent moving to Japan | JIS-compliant Rirekisho builder · 30+ visa types · 0–100 Readiness Score engine |
| **悠 Yuki AI** *(private)* | Japan-specialist bilingual AI assistant | Multi-provider fallback · honorific register handling · custom intent classifier |
| [**BookFlow**](https://github.com/iTanmayTrivedi/ServiceScheduleJapan) | Bilingual appointment & reservation platform with AI-assisted scheduling | 0.8s median TTI · AI no-show prediction · zero-signup Demo Mode |
| [**Kaizen**](https://github.com/iTanmayTrivedi/GlobalSaaSDashboardJapan) | Multi-tenant bilingual AI operations platform for Japanese business teams | 7 AI tools behind one gateway · 1,200+ EN/JP string pairs · keigo checker |
| [**SysMonitor**](https://github.com/iTanmayTrivedi/SystemMonitoringJapan) | Real-time observability platform with AI-assisted incident diagnostics | <800ms first paint · 60fps under 500 logs/sec · AI root-cause analysis |
| [**TeamHub**](https://github.com/iTanmayTrivedi/TeamManagementSystemJapan) | Bilingual team & task management platform | 3-role RBAC · AI daily summaries · UTF-8 BOM CSV export for Japanese Excel |
| **[私の縁側 (Watashi no Engawa)](https://tanmaytrivedi.dev)** *(private repo)* | Personal portfolio built as an interactive slice-of-life narrative for Japanese recruiters | Lighthouse 96/100 · 100/100 Accessibility · 24 bespoke micro-interactions, 0 animation-runtime deps |

> Repo links follow my standard naming convention — happy to point directly to a specific one if you're reviewing.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## By the Numbers

*Rolled up across shipped production projects — counted directly from each build, not vanity metrics.*

| Metric | Total |
|---|---|
| Production projects shipped solo | 8 |
| Postgres tables secured with Row-Level Security | 44+ |
| AI-powered Edge Functions in production | 17+ |
| Bilingual (EN/日本語) production applications | 6 |
| Recruiter-ready demo modes (zero signup required) | 5 |
| Best Lighthouse Performance score shipped | 96 / 100 |

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## How I Build

Patterns that show up in every project, not just the polished one:

- **Security is a schema decision, not a UI afterthought.** Roles live in a dedicated `user_roles` table behind a `SECURITY DEFINER has_role()` function — never on the profile row — across every project, eliminating an entire class of privilege-escalation and RLS-recursion bugs by default.
- **AI stays server-side, always.** Every AI feature is proxied through an Edge Function; no API key has ever shipped in a client bundle.
- **Localization is a type-system problem.** EN/日本語 parity is enforced at compile time — typed translation keys, generated DB types — rather than checked by hand, so drift gets caught before it ships.
- **Demoability is a feature.** Every recruiter-facing project ships with a zero-signup demo mode, because a login wall is the easiest way to lose a 12-second first impression.
- **Ship vertically, not wide.** Each project proves schema → API → UI → AI end-to-end rather than gluing together a wide, shallow feature set.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Research

Lead researcher and first author on a published bioinformatics paper at Rama University, with an accompanying tool built to support the research — bridging my biotechnology background with applied software engineering.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Certifications

| Certification | Provider |
|---|---|
| Foundational C# with Microsoft | freeCodeCamp |
| AWS S3 Basics | Amazon Web Services |
| Azure Cognitive Services | Microsoft |
| MCP Advanced Topics | Anthropic |
| Elements of AI | University of Helsinki |

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Backend** | Node.js · PostgreSQL · Supabase · Redis · Go · MongoDB |
| **Infrastructure** | Docker · AWS · CI/CD |
| **AI / Tooling** | Gemini · Groq · Claude · GitHub Copilot |

**Recurring engineering patterns across every project:** Row-Level Security on every public table · roles in a dedicated `user_roles` table with a `SECURITY DEFINER has_role()` function · server-side AI Edge Functions only · EN/日本語 parity enforced at the type level.

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Japan Journey

```
📍 Kanpur, India → 🇯🇵 Japan (target: shinsotsu 2029)
🈺 JLPT N1 — in progress
🎯 Bridge Engineer / Full-Stack Developer track
📚 B.Tech Biotechnology, Rama University — Class of 2029
```

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Hobbies Corner

Outside of shipping code, I'm usually deep in an anime backlog:

- 呪術廻戦 — **Jujutsu Kaisen**
- **Citrus**
- **BLEACH**
- 鬼滅の刃 — **Demon Slayer**
- 彼女、お借りします — **Kanojo, Okarishimasu (Rent-a-Girlfriend)**

<br>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Reach Me

- **Portfolio** → [tanmaytrivedi.dev](https://tanmaytrivedi.dev)
- **LinkedIn** → [in/itanmaytrivedi](https://www.linkedin.com/in/itanmaytrivedi)
- **Email** → [tanmay.trivedi.jp@gmail.com](mailto:tanmay.trivedi.jp@gmail.com)

<br>

<div align="center">

*「一目で分かる、本気で作る。」*
*Built to be understood at a glance — made with real intent.*

</div>
