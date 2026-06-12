# KPNY-001 Phase 1 — Design Research Report

Date: 2026-06-13
Source: Lazyweb design library (4 desktop searches: dev-tool landing hero, AI agent homepage, CTA/waitlist conversion, dark hero + social proof)

## Top structural patterns (with references)

1. **Dark-theme hero + real product UI screenshot** — Linear (linear.app), Raycast (raycast.com/developers). The dominant pattern for dev/AI-agent products: dark background, large headline, the actual product interface as hero visual. Linear explicitly markets "product development system for teams and AI agents" — closest comp to Kompany.
2. **Hero headline → single primary CTA → social proof logos immediately below** — Replit Agent (replit.com/products/agent), GitHub AI (github.com/features/ai). One CTA above the fold ("Get started"), logos as instant credibility.
3. **Alternating feature blocks: screenshot left/right + short blurb** — Replit Agent, GitHub, Linear. Scroll narrative: what it does → how it works → proof.
4. **Build → Deploy → Optimize diagram section** — OpenAI Agent Platform (openai.com/agent-platform). Lifecycle diagram explains an agent platform's loop better than feature lists. Kompany analog: Directive → CEO routes → Agents execute → Approve/Ship.
5. **Closing "Get started" panel with multiple entry paths + dense footer** — OpenAI API page, MetaMask developer page (docs, code snippet, newsletter).

## Messaging frameworks

- Outcome-framing beats feature-framing: Replit "build production-ready apps", GitHub "AI for every step of your workflow". Headline = what the user ships, not what the tool is.
- Credible vs hype: pages that feel credible show real UI, real code, concrete workflow nouns (PRs, changelogs, approvals). Hype pages (Lyzr, Coveo style) lead with abstract "responsible business growth" copy + partner logos only.
- Recommended Kompany headline direction: "Your AI company that runs itself" class of outcome statement, immediately grounded by real terminal/approval-flow screenshot.

## CTA strategy

- Single primary CTA above fold; repeat at page end (Replit, Linear pattern).
- For pre-launch: minimal waitlist form = email only (Spill waitlist, Tableau "Join the waitlist"). Name/message fields optional at most.
- Avoid demo-form-first (Glean, enterprise pattern) — wrong for indie/dev audience.
- Dev-product alternative: "Read the docs" secondary CTA next to primary (MetaMask, Phantom pattern).

## Competitor teardowns (3)

1. **Linear** — dark hero, product UI as hero image, capability sections (workflows, agents reviewing PRs, analytics), changelog section signals momentum. Best overall structural template for Kompany.
2. **Replit Agent** — outcome headline + Get started + logos; alternating screenshot/blurb sections; community testimonials + explainer video; final CTA. Best conversion-flow template.
3. **OpenAI Agent Platform** — hero, build/deploy/optimize lifecycle diagram, SDK/tooling showcase, "Ready to get started?" multi-path closer. Best for explaining platform mechanics.

## Design direction brief → Phase 2

- **Theme:** dark, Linear/Raycast lineage. Restrained accent color, real UI screenshots (Kompany TUI/approval flow), monospace touches.
- **Page skeleton:** nav → hero (headline + sub + 1 CTA + product screenshot) → logo/social-proof strip (or X-post embeds pre-launch) → 3-4 alternating feature blocks → lifecycle diagram (Directive→Route→Execute→Approve) → testimonial/journal-excerpt section → final CTA panel → footer.
- **Tone:** specific and credible, zero AI-hype adjectives; show the actual product working.
- **CTA:** pre-launch waitlist (email only) or "Star on GitHub" + "Read docs" if repo public.

Reference screenshots: signed URLs valid 365d, in Lazyweb search results (session 2026-06-13).
