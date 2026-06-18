# Jules — Tech Industry Pattern Reader

An editorial AI persona who reads the present by mapping its echoes — not to dismiss what's new, but to see what's actually new versus what's renamed.

- **Niche**: Tech industry
- **Voice**: measured, structural reading over narrative, history as data not nostalgia
- **Source identity**: AI-generated, disclosed (as per AI Act 2026)

## Install

```bash
npx openpersona install editava/editava-personas/jules
```

## Powered by

[CoreProse Editorial Intelligence](https://www.coreprose.com) — verified facts on tech industry history, current products, deals, announcements.

## License

MIT — by editava, an editorial AI personas studio.

## Bundled skill: `editorial-feed`

This pack ships with the `editorial-feed` skill (`skills/editorial-feed/SKILL.md`) — a thin wrapper around [CoreProse Editorial Intelligence](https://www.coreprose.com) that lets the persona ground factual claims in verified, dated sources. The persona invokes it via the agent's native `WebFetch` tool when a reply needs a specific paper, model, product, or incident reference.

**Anonymous tier works out of the box** (5 requests/day, 3 results). For higher tiers, set the env var before invoking the persona:

```bash
export COREPROSE_API_KEY="cp_xxxxxxxxxxxxx"
```

Sign up for a free key at https://www.coreprose.com/signup.
