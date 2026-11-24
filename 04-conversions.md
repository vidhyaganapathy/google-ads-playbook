# 04 · Conversion goals

Smart Bidding, Performance Max and Demand Gen all optimise toward your conversion goals. **Bad conversion setup means automation optimises for the wrong thing.**

## Checklist

- [ ] Google tag (or Google Tag Manager) installed on every page
- [ ] Key actions tracked: form submit, booking, call, signup, purchase
- [ ] **One clear primary goal** per campaign; everything else secondary
- [ ] Enhanced conversions turned on where it fits, for more accurate matching
- [ ] GA4 linked to Google Ads, with consistent definitions
- [ ] No double counting (e.g. thank-you page view **and** form submit both counted as primary)
- [ ] Test every conversion before launch

## Primary vs secondary

| Action | Primary or secondary |
|---|---|
| Qualified lead / booked meeting | **Primary** (best, if you can import it) |
| Form submit | Primary (if you can't import quality) |
| Page views, scrolls, clicks | Secondary (observe only) |
| Newsletter signup | Secondary, unless it's the actual goal |

## Feed back lead quality

The biggest upgrade for lead gen: **tell Google which leads were good.**

1. Capture the click ID (GCLID) with each lead in your CRM or sheet.
2. When sales marks a lead as qualified or a meeting is booked, import that as an **offline conversion**.
3. Optimise bidding toward that qualified-lead conversion once volume allows.

This shifts Google from "find more form fills" to "find more people like the ones who became meetings."

## UTMs

Google Ads auto-tagging handles GCLID. Add UTMs too, so non-Google tools can read the source:

```
utm_source=google&utm_medium=cpc&utm_campaign={campaignid}&utm_content={adgroupid}&utm_term={keyword}
```
