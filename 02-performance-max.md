# 02 · Performance Max

Performance Max runs one campaign across Google's inventory (including Search, YouTube, Display, Discover, Gmail and Maps) and uses automation to find conversions. It's powerful, and it will optimise toward exactly what you tell it to, so the inputs matter.

## Before you launch

- [ ] Conversion tracking is accurate and the **primary goal is the one you actually want** (see 04-conversions.md)
- [ ] Search campaigns are already running, so you have a baseline
- [ ] Enough budget for the campaign to learn
- [ ] Strong assets ready: images, logos, video, headlines, descriptions

## Asset groups

Build **one asset group per audience or offer theme**, not one for everything.

```
Campaign: PMax_Leads_AU
├── Asset group: Service A (assets + signals for service A buyers)
├── Asset group: Service B
└── Asset group: Lead magnet
```

Each asset group needs:
- **Headlines and descriptions** written for that theme
- **Images** in the required ratios
- **Video** (if you don't add one, Google may auto-generate one; supply your own where you can)
- **Final URL** that matches the theme

## Audience signals

Signals are hints, not hard targeting. Give the strongest ones you have:
1. **Your data:** customer lists, website visitors, converters
2. **Custom segments:** people searching for terms like your best keywords, or visiting competitor-type sites
3. **Interests and demographics:** a supporting layer only

## Guardrails

| Setting | Why |
|---|---|
| **Brand exclusions** | Stop PMax claiming credit for brand searches your Search campaign would catch anyway |
| **Final URL expansion** | Turn off or limit if it sends traffic to irrelevant pages |
| **Search themes** | Guide which searches the campaign explores |
| **Account-level negatives** | Keep irrelevant queries out |

## How I judge it

- Cost per **qualified** lead, not just conversions
- Search term insights: is it finding new intent, or just brand traffic?
- Asset performance: replace low-performing assets regularly
- Give it time to learn before big changes
