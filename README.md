<div align="center">

# Toyo Skills

**The agent skills I use to design, build, market, and ship better work.**

[![Skills](https://img.shields.io/badge/skills-50-6C5CE7?style=for-the-badge)](#skill-library)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-111827?style=for-the-badge)](https://agentskills.io)
[![License](https://img.shields.io/badge/license-MIT-22C55E?style=for-the-badge)](LICENSE)
[![Codex](https://img.shields.io/badge/Codex-ready-0A0A0A?style=for-the-badge)](https://developers.openai.com/codex)

A curated, cross-agent library for Codex, Claude Code, Cursor, and other
tools that support the open Agent Skills format.

</div>

## Quick start

List the available skills:

```bash
npx skills add Toyontewo/toyo-skills --list
```

Install one skill interactively:

```bash
npx skills add Toyontewo/toyo-skills --skill copywriting
```

Install every skill globally for Codex and Claude Code:

```bash
npx skills add Toyontewo/toyo-skills --skill '*' -g -a codex -a claude-code -y
```

Install every skill for every agent detected by the Skills CLI:

```bash
npx skills add Toyontewo/toyo-skills --all
```

## Skill library

Each skill lives in `skills/<skill-name>/` with its `SKILL.md` and any
references, scripts, templates, or assets it needs.

### Design and development

| Skill | What it does | Source | Install |
| --- | --- | --- | --- |
| [`design-taste-frontend`](skills/design-taste-frontend) | Designs distinctive landing pages, portfolios, and redesigns without templated AI aesthetics. | [Leonxlnx][taste-skill] | `npx skills add Toyontewo/toyo-skills --skill design-taste-frontend` |
| [`find-skills`](skills/find-skills) | Finds and installs useful skills from the open agent-skills ecosystem. | [Vercel Labs][vercel-skills] | `npx skills add Toyontewo/toyo-skills --skill find-skills` |
| [`frontend-design`](skills/frontend-design) | Guides intentional typography, layout, color, and motion choices for polished interfaces. | OpenAI Codex | `npx skills add Toyontewo/toyo-skills --skill frontend-design` |
| [`reddit-automation`](skills/reddit-automation) | Finds relevant Reddit conversations and drafts honest, helpful, disclosed replies. | [doany.ai][doany-skills] | `npx skills add Toyontewo/toyo-skills --skill reddit-automation` |
| [`redesign-existing-projects`](skills/redesign-existing-projects) | Audits and upgrades existing websites without breaking their current functionality. | [Leonxlnx][taste-skill] | `npx skills add Toyontewo/toyo-skills --skill redesign-existing-projects` |
| [`stop-slop`](skills/stop-slop) | Removes predictable AI writing patterns and makes prose clearer and more natural. | [Hardik Pandya](https://hvpandya.com) | `npx skills add Toyontewo/toyo-skills --skill stop-slop` |
| [`typesafe-ai`](skills/typesafe-ai) | Builds typed AI judgments for routing, ranking, extraction, verification, and product logic. | [TypeSafe AI][typesafe-skills] | `npx skills add Toyontewo/toyo-skills --skill typesafe-ai` |
| [`web-design-guidelines`](skills/web-design-guidelines) | Reviews interfaces for usability, accessibility, and web-design best practices. | [Vercel Labs][web-guidelines] | `npx skills add Toyontewo/toyo-skills --skill web-design-guidelines` |

### Personal workflow

| Skill | What it does | Source | Install |
| --- | --- | --- | --- |
| [`upwork-ai-automation-proposal-generator`](skills/upwork-ai-automation-proposal-generator) | Produces a tailored proposal, build plan, Loom script, workflow, macro, and teleprompter for AI automation jobs. | [Toyo Ntewo][upwork-skill] | `npx skills add Toyontewo/toyo-skills --skill upwork-ai-automation-proposal-generator` |

### Marketing

| Skill | What it does | Source | Install |
| --- | --- | --- | --- |
| [`ab-test-setup`](skills/ab-test-setup) | Plans experiments, hypotheses, variants, metrics, and decision rules. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill ab-test-setup` |
| [`ad-creative`](skills/ad-creative) | Generates and iterates ad copy for paid-media platforms. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill ad-creative` |
| [`ai-seo`](skills/ai-seo) | Optimizes content for AI answers, citations, and generative search visibility. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill ai-seo` |
| [`analytics-tracking`](skills/analytics-tracking) | Designs and audits analytics, events, attribution, and conversion tracking. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill analytics-tracking` |
| [`aso-audit`](skills/aso-audit) | Audits and improves App Store and Google Play listings. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill aso-audit` |
| [`churn-prevention`](skills/churn-prevention) | Improves cancellation flows, save offers, dunning, and retention systems. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill churn-prevention` |
| [`co-marketing`](skills/co-marketing) | Finds partners and plans joint campaigns, integrations, and cross-promotions. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill co-marketing` |
| [`cold-email`](skills/cold-email) | Writes B2B cold emails and follow-up sequences designed to earn replies. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill cold-email` |
| [`community-marketing`](skills/community-marketing) | Builds community-led growth, engagement, and advocacy programs. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill community-marketing` |
| [`competitor-alternatives`](skills/competitor-alternatives) | Creates competitor, alternative, comparison, and versus pages. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill competitor-alternatives` |
| [`competitor-profiling`](skills/competitor-profiling) | Researches competitors and produces structured competitive profiles. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill competitor-profiling` |
| [`content-strategy`](skills/content-strategy) | Plans content pillars, topic clusters, roadmaps, and editorial direction. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill content-strategy` |
| [`copy-editing`](skills/copy-editing) | Reviews and sharpens existing marketing copy without unnecessary rewrites. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill copy-editing` |
| [`copywriting`](skills/copywriting) | Writes persuasive website, landing-page, pricing, and product copy. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill copywriting` |
| [`customer-research`](skills/customer-research) | Collects and synthesizes interviews, surveys, reviews, and voice-of-customer evidence. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill customer-research` |
| [`directory-submissions`](skills/directory-submissions) | Plans submissions to product, SaaS, AI, review, and discovery directories. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill directory-submissions` |
| [`email-sequence`](skills/email-sequence) | Creates onboarding, nurture, lifecycle, and re-engagement email flows. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill email-sequence` |
| [`form-cro`](skills/form-cro) | Improves lead, contact, demo, survey, and checkout forms. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill form-cro` |
| [`free-tool-strategy`](skills/free-tool-strategy) | Plans useful free tools for lead generation, SEO, and brand awareness. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill free-tool-strategy` |
| [`image`](skills/image) | Creates and optimizes marketing graphics, banners, mockups, and image assets. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill image` |
| [`launch-strategy`](skills/launch-strategy) | Plans product launches, announcements, betas, waitlists, and releases. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill launch-strategy` |
| [`lead-magnets`](skills/lead-magnets) | Plans downloadable resources and offers that convert visitors into leads. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill lead-magnets` |
| [`marketing-ideas`](skills/marketing-ideas) | Generates practical channel and growth ideas for software products. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill marketing-ideas` |
| [`marketing-psychology`](skills/marketing-psychology) | Applies behavioral science, persuasion, and decision-making principles. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill marketing-psychology` |
| [`onboarding-cro`](skills/onboarding-cro) | Improves activation, first-run experience, and time to value. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill onboarding-cro` |
| [`page-cro`](skills/page-cro) | Diagnoses and improves conversion performance on marketing pages. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill page-cro` |
| [`paid-ads`](skills/paid-ads) | Plans targeting, budgets, bidding, retargeting, and campaign optimization. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill paid-ads` |
| [`paywall-upgrade-cro`](skills/paywall-upgrade-cro) | Improves in-product paywalls, upgrade prompts, and feature gates. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill paywall-upgrade-cro` |
| [`popup-cro`](skills/popup-cro) | Improves popups, banners, slide-ins, overlays, and modal conversions. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill popup-cro` |
| [`pricing-strategy`](skills/pricing-strategy) | Develops pricing, packaging, monetization, and value-metric strategy. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill pricing-strategy` |
| [`product-marketing-context`](skills/product-marketing-context) | Captures reusable product, audience, positioning, and market context. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill product-marketing-context` |
| [`programmatic-seo`](skills/programmatic-seo) | Plans scalable, template-driven SEO pages powered by structured data. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill programmatic-seo` |
| [`referral-program`](skills/referral-program) | Designs referral, affiliate, ambassador, and word-of-mouth programs. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill referral-program` |
| [`revops`](skills/revops) | Improves lead lifecycle, scoring, routing, CRM hygiene, and sales handoffs. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill revops` |
| [`sales-enablement`](skills/sales-enablement) | Creates decks, one-pagers, scripts, objection handling, and sales collateral. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill sales-enablement` |
| [`schema-markup`](skills/schema-markup) | Implements and repairs schema.org structured data and JSON-LD. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill schema-markup` |
| [`seo-audit`](skills/seo-audit) | Audits technical SEO, on-page issues, indexing, and organic visibility. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill seo-audit` |
| [`signup-flow-cro`](skills/signup-flow-cro) | Reduces registration friction and improves signup or trial conversion. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill signup-flow-cro` |
| [`site-architecture`](skills/site-architecture) | Plans navigation, page hierarchy, URL structure, and internal linking. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill site-architecture` |
| [`social-content`](skills/social-content) | Creates and repurposes social posts, calendars, threads, and short-form scripts. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill social-content` |
| [`video`](skills/video) | Plans and produces AI-assisted or programmatic video workflows. | [Marketing Skills][marketingskills] | `npx skills add Toyontewo/toyo-skills --skill video` |

## Manual installation

Copy any complete skill folder into the appropriate global directory:

| Agent | Global directory | Project directory |
| --- | --- | --- |
| Codex | `~/.codex/skills/` | `.codex/skills/` |
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Shared/generic agents | `~/.agents/skills/` | `.agents/skills/` |

For example:

```bash
cp -R skills/copywriting ~/.codex/skills/copywriting
```

Always copy the entire folder, not only `SKILL.md`; many skills rely on their
included references, scripts, templates, or assets.

## Licensing and credits

The root [MIT license](LICENSE) covers original work and curation by Toyo
Ntewo. Third-party skills retain their original licenses and attribution. See
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and [`licenses/`](licenses/)
for the complete mapping.

## Pending license review

The following locally used skills are intentionally not published here until
their redistribution rights are confirmed:

- `linkedin-hook-writer`
- `terminal-browser`
- `remotion-best-practices`

## Contributing

Issues and pull requests are welcome. A contributed skill should:

1. Live at `skills/<skill-name>/SKILL.md`.
2. Include a unique `name` and useful `description` in its front matter.
3. Keep every required reference, script, template, and asset in its folder.
4. Include its source, author, and redistribution license.
5. Contain no credentials, machine-specific paths, caches, or nested Git data.

---

<div align="center">

Curated by [Toyo Ntewo](https://github.com/Toyontewo)

</div>

[doany-skills]: https://github.com/doany-skills/skills
[marketingskills]: https://github.com/coreyhaines31/marketingskills
[taste-skill]: https://github.com/Leonxlnx/taste-skill
[typesafe-skills]: https://github.com/typesafe-ai/skills
[upwork-skill]: https://github.com/Toyontewo/upwork-ai-automation-proposal-generator
[vercel-skills]: https://github.com/vercel-labs/skills
[web-guidelines]: https://github.com/vercel-labs/web-interface-guidelines
