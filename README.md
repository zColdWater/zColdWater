# OmniForge · Pre-Launch Engineering & Security Tools (`zColdWater`)

Free, zero-signup web diagnostics, open-source MIT checklists, CLIs, and MCP servers for indie builders shipping with **Cursor, Lovable, Bolt, v0, Next.js, Vercel, Cloudflare, and Supabase**.

[![VibeShield Live Audit](https://vibe-checker.appwrite.network/badge/vibe/supabase.com.svg)](https://vibe-checker.appwrite.network)
[![InboxShield DNS Audit](https://inbox-checker.appwrite.network/badge/inbox/stripe.com.svg)](https://inbox-checker.appwrite.network)
[![BrandShield Clearance](https://brand-checker.appwrite.network/badge/brand/OmniForge.svg)](https://brand-checker.appwrite.network)
[![CiteReady AI Search](https://citeready-checker.appwrite.network/badge.svg?url=stripe.com)](https://citeready-checker.appwrite.network)
[![Featured on Awesome Black Friday Deals 2026](https://img.shields.io/badge/Featured_on-Awesome_Black_Friday_Deals_2026-black)](https://github.com/twf-nikhila/Awesome-Black-Friday-Cyber-Monday-deals)

---

## Live Free Web Scanners (Zero Signup, Instant Browser Audit)

| Tool | What It Audits Live | Free Tier | Launch Special Unlock |
| --- | --- | --- | --- |
| **[VibeShield v7.0](https://vibe-checker.appwrite.network)** | 6-phase passive security scan (`116` checks): client JS bundles (52 secret patterns), 10 Mozilla Observatory headers, CSP AST, 28 SPA-filtered paths & safe Supabase/Firebase probes | Full 6-phase score, severity breakdown & live trace | **$2** one-time (was ~~$9~~) — exact line locations + 5-platform fixes ([Unlock](https://omnipulse-x402.appwrite.network/go/gumroad/vibeshield)) |
| **[InboxShield v7.0](https://inbox-checker.appwrite.network)** | 6-phase email DNS & deliverability audit: recursive SPF `<=10` lookup flattener, 24 DKIM selectors, DMARC syntax, MTA-STS, BIMI & 5 DNSBLs | Full DNS score, protocol trace & [SPF Flattener](https://inbox-checker.appwrite.network/spf-flattener) | **$2** one-time (was ~~$9~~) — zero-conflict registrar fix records ([Unlock](https://omnipulse-x402.appwrite.network/go/gumroad/inboxshield)) |
| **[CiteReady v6.0](https://citeready-checker.appwrite.network)** | AI Search & GEO readiness: 10 global & China AI crawlers, Schema.org Entity Graph depth, competitor side-by-side PK & `/llms.txt` compiler | Full AI readiness audit & [`/llms.txt` Generator](https://citeready-checker.appwrite.network/generator) | **$2** one-time (was ~~$12~~) — 5-platform Schema & `/llms.txt` fixes ([Unlock](https://omnipulse-x402.appwrite.network/go/gumroad/citeready)) |
| **[BrandShield v6.2](https://brand-checker.appwrite.network)** | Startup domain & trademark clearance: 78+ TLD direct IANA RDAP, live USPTO Class 009/042 check, aftermarket search & [AI Brand Namer](https://brand-checker.appwrite.network/namer) | **100% Free** (all features unlocked, no paywall) | Free forever |

> **OmniForge Complete Suite (All 3 Pro Unlocks):** **$5** one-time Launch Special (was ~~$29~~, zero monthly subscription, 14-day refund guarantee) — [Gumroad](https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack) · [Direct Checkout](https://omnipulse-x402.appwrite.network/checkout/launch-stack)

---

## Featured 2026 Research & Open-Source Repositories (MIT)

- **[5 Free Live Pre-Launch Diagnostic Tools](https://zcoldwater.github.io/launch-audit-reports/tools/)** — Interactive zero-signup checkers: [SPF 10-Lookup & PermError](https://zcoldwater.github.io/launch-audit-reports/tools/spf-permerror-checker.html) · [DMARC `p=reject` & DKIM](https://zcoldwater.github.io/launch-audit-reports/tools/dmarc-reject-checker.html) · [`/llms.txt` & AI Crawler Validator](https://zcoldwater.github.io/launch-audit-reports/tools/llms-txt-validator.html) · [52-Rule JS Secret Leak Scanner](https://zcoldwater.github.io/launch-audit-reports/tools/js-secret-leak-scanner.html) · [78-TLD & USPTO Trademark Checker](https://zcoldwater.github.io/launch-audit-reports/tools/uspto-domain-checker.html).
- **[State of AI & Vibe-Coded Web App Security (2026)](https://zcoldwater.github.io/launch-audit-reports/vibe-security-2026/)** — Empirical passive audit of 55 freshly launched AI-built web apps (`6,120+` checks; also archived in [`awesome-annual-security-reports`](https://github.com/jacobdjwilson/awesome-annual-security-reports)): `74.5%` ship missing 8–9 of 10 security headers, `20.0%` run live Supabase backends, and `3.6%` leaked client secrets (strictly anonymized). Stack guides: [Lovable](https://zcoldwater.github.io/launch-audit-reports/vibe-security-2026/lovable.html) · [Cursor & Next.js](https://zcoldwater.github.io/launch-audit-reports/vibe-security-2026/cursor.html) · [Bolt & Netlify](https://zcoldwater.github.io/launch-audit-reports/vibe-security-2026/bolt.html) · [Supabase RLS](https://zcoldwater.github.io/launch-audit-reports/vibe-security-2026/supabase.html).
- **[2026 SaaS Email Deliverability Study](https://zcoldwater.github.io/launch-audit-reports/email-deliverability-2026/)** & **[2026 AI Search / `/llms.txt` Study](https://zcoldwater.github.io/launch-audit-reports/ai-search-2026/)** — Live measured DMARC/SPF/MX & AI crawler benchmarks across `228` top SaaS domains.
- **[`vibe-security-checklist` (`v1.0.0`)](https://github.com/zColdWater/vibe-security-checklist)** — Copy-paste MIT `vercel.json`, Next.js `next-headers.mjs`, Netlify `_headers`, Cloudflare Workers, Nginx, Supabase RLS SQL, Firestore rules, `.cursor/rules/security.mdc`, and a zero-dependency local bundle secret guard.
- **[`launch-audit-reports`](https://zcoldwater.github.io/launch-audit-reports/)** — Live measured SPF/DMARC & AI-search benchmarks across `228` SaaS & developer-tool domains, `10` troubleshooting guides, and [4 honest competitor comparisons](https://zcoldwater.github.io/launch-audit-reports/compare/).
- **[`mcp-launch-audit`](https://github.com/zColdWater/mcp-launch-audit)** — Official MCP server exposing 5 read-only pre-launch audit tools (`audit_web_app_security`, `audit_email_deliverability`, `audit_ai_search_readiness`, `check_brand_clearance`, `flatten_spf_record`) for Claude Desktop, Cursor, and Windsurf.
- **GitHub Actions & Agent Skills (`skills.sh`):** [`vibeshield-action`](https://github.com/zColdWater/vibeshield-action) · [`inboxshield-action`](https://github.com/zColdWater/inboxshield-action) · [`citeready-action`](https://github.com/zColdWater/citeready-action) · [`omniforge-skills`](https://github.com/zColdWater/omniforge-skills) ([Vercel `skills.sh`](https://www.skills.sh/zColdWater/omniforge-skills))
- **Open-Source CLIs:** [`vibeshield-cli`](https://github.com/zColdWater/vibeshield-cli) · [`inboxshield-cli`](https://github.com/zColdWater/inboxshield-cli) · [`citeready-cli`](https://github.com/zColdWater/citeready-cli) · [`brandshield-cli`](https://github.com/zColdWater/brandshield-cli)

---

**Contact & Support:** OmniForge · Agent Arena Studio · `agentarenastudio@proton.me` · [@agentarenastudi](https://x.com/agentarenastudi) · [Support Portal](https://omnipulse-x402.appwrite.network/support) · [14-Day Refund Policy](https://omnipulse-x402.appwrite.network/refund-policy)
