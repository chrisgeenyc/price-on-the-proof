# Price on the Proof — a Claude skill for pricing expertise

A pricing method for solopreneurs, consultants, coaches, agencies, and course
creators — anyone who sells expertise instead of software. Most pricing advice is
built for SaaS (tiers, seats, MRR). This is built for services: you price the
**transformation** you create, discipline it against the **market**, and defend
it with **proof** instead of gut.

## What it does

When active, the skill walks you through a 6-step method and returns a specific,
defensible price:

1. Name the transformation (before → after)
2. Quantify the Year-1 value created (time saved, capacity gained, cost avoided)
3. Set a candidate fee as a *fraction* of that value (the ROI-to-Rate / capture-rate step)
4. Discipline it against real market comparables
5. Position within the band by your authority/proof
6. Package three ways (project / retainer / productized) and present value-first

Plus a quarterly **Close-Rate Diagnostic** for knowing when to raise your prices.

## Install (Claude Code)

Copy the `price-on-the-proof/` folder into your skills directory:

```bash
cp -r price-on-the-proof ~/.claude/skills/        # global
# or
cp -r price-on-the-proof .claude/skills/          # project-level
```

Then just ask: *"What should I charge for this engagement?"* or *"Am I underpriced?"*

## Use it in Claude.ai or the API

Upload the skill folder per the
[Claude skills docs](https://support.claude.com/en/articles/12512180-using-skills-in-claude).

## Files

- `SKILL.md` — the method and instructions
- `references/market-bands.md` — how to build a market band + illustrative benchmarks

## Credits & Attribution

"Price on the Proof" builds on open-source work:

- The value-based **pricing** logic and the **`product-marketing.md`** context
  pattern are adapted from [Corey Haines' marketing-skills](https://github.com/coreyhaines31/marketingskills)
  (MIT licensed) — Corey Haines, [corey.co](https://corey.co).
- The willingness-to-pay step uses the **Van Westendorp** Price Sensitivity Meter.
- The method itself — three-anchor triangulation, the ROI-to-Rate capture-rate
  step, market-band research, and the quarterly Close-Rate Diagnostic — is by
  **Chris Gee**.

## License

[MIT](LICENSE). Free to use and adapt.
