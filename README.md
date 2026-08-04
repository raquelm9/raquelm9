## Raquel Mijares

Front end engineer in Calgary, working on consumer streaming products since 2020.

I build and own the parts of a product where mistakes are expensive: checkout and subscriptions, ad attribution, DRM playback, and children's privacy compliance.

### What I work on

Two consumer streaming brands sharing a Nuxt and TypeScript monorepo, plus the surrounding surfaces: a smart TV app, native mobile release pipelines, and a Flutter desktop tool used by live broadcast operators.

**Revenue paths.** Stripe checkout and the subscription lifecycle for both brands, including the failure states most checkouts never handle: script load failures, bfcache restores, plan parameters lost across authentication, and account deletion attempted with an active subscription.

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

`TypeScript` · `Vue 3` · `Nuxt` · `Pinia` · `Tailwind` · `Vitest` · `Playwright` · `Flutter` · `Dart` · `Node` · `AWS` · `GitHub Actions`

### Elsewhere

[raquel-mijares.com](https://www.raquel-mijares.com/)
