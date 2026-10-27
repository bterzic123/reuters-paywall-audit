# Paywall Audit — Reuters

**Live:** https://bterzic123.github.io/reuters-paywall-audit/

Ranked paywall ideas for the Reuters iOS app, each backed by a number from Adapty's
[State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=reuters),
plus a clickable rebuild of the subscription sheet and the moment after it is closed, with a Today / Proposed switch.

## The ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Make Yearly the default, with a free week on it | 5.3 annual-forward layout; 2.6 trial length by plan | ARPU +25–40% (observed in winning A/B tests) |
| 2 | Catch the swipe-down with one more offer | 4.5 second-chance paywalls | ARPU +10–15% (based on Adapty data) |
| 3 | Show how the free week works | 5.3 trial explainer; 1.6 Europe day-one cancellations; 3.4 trial timelines | ARPU +12–36% (observed in winning A/B tests) |
| 4 | Put your 4.8 rating on the sheet | 5.3 social proof; 3.1 share of paywalls with social proof | CR +10–30% (observed in winning A/B tests) |

## Benchmark slice

All categories (the report has no News category), Europe (the paywall audited is the euro storefront),
App Store data, Oct 2025–Sep 2026.

## Grounding

Prices (€4 monthly, €45 yearly), copy and layout come from Reuters' own in-app paywall. The 4.8 rating
and 8.9K ratings come from the US App Store listing. €3.75 is €45 ÷ 12. The 7-day trial and the day-5
reminder are proposals to test, not something Reuters sells today. Impact ranges are observed lifts
from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Reuters.

## Run locally

```
python3 -m http.server 8765
```
