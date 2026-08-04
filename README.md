## Raquel Mijares

Software developer in Calgary since 2020.

Most of my work has been on products where being wrong has consequences: payments and subscriptions, children's privacy, emissions reporting, and security compliance. Four industries, one requirement. The edge cases have to actually work, and someone audits them.

### Experience

**A Parent Media Co. (APMC)** — Software Developer · Sep 2024 to present
Consumer streaming platform for two brands on a shared Nuxt and TypeScript monorepo, plus a smart TV app, native mobile release pipelines, and a Flutter desktop tool used by live broadcast operators. I own checkout and subscriptions, ad attribution, DRM playback, and children's privacy compliance.

**Kettl** — Software Engineer · Sep 2023 to Sep 2024
Production management system for live events, built to optimise real time event operations. React and Apollo GraphQL.

**Validere** — Software Developer · May 2023 to Nov 2023
Enterprise platform for the energy industry, replacing spreadsheets and manual workflows with automated, auditable processes for emissions reporting and environmental compliance. JavaScript.

**Tugboat Logic** (acquired by OneTrust) — Front End Developer · Mar 2021 to May 2023
Security assurance platform that automates evidence collection and audit readiness across SOC 2, ISO 27001, GDPR and HIPAA. JavaScript, with MSW for API mocking.

**InceptionU** — Full Stack Developer · Sep 2020 to Feb 2021
Project based full stack program building real software for real clients. Node.js.

### Current work, in depth

**Revenue paths.** Stripe checkout and the subscription lifecycle for two brands, including the failure states most checkouts never handle: script load failures, bfcache restores, plan parameters lost across authentication, and account deletion attempted with an active subscription.

**Ad attribution.** Meta CAPI and TikTok conversion events, last click integrity across `fbclid` and UTM parameters, protection against organic traffic overwriting paid attribution, and ad beacon correctness including quartile deduplication and view count accuracy.

**Playback.** DRM delivery and recovery, playback variant preservation across reloads, DVR and VOD seek behaviour, and caption state that survives track changes.

**Compliance.** kidSAFE COPPA certification surfaces, consent management across web and smart TV, and privacy gating on analytics in a children's product.

**Design systems.** A full migration off a legacy modal stack onto a token driven dialog system across two brands, ending with the deletion of the system it replaced.

### Scale

Over the last two years, across 11 repositories:

- **849 pull requests merged**
- **458 pull requests reviewed** for other engineers
- Around 3,400 commits authored

Most of it is in private repositories, so the graph below understates it.

### Stack

`TypeScript` · `Vue 3` · `Nuxt` · `React` · `Apollo GraphQL` · `Pinia` · `Tailwind` · `Vitest` · `Playwright` · `MSW` · `Flutter` · `Dart` · `Node` · `AWS` · `GitHub Actions`

### Elsewhere

[raquel-mijares.com](https://www.raquel-mijares.com/) · [LinkedIn](https://www.linkedin.com/in/raquelmjrs/)
