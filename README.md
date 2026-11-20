# Growth Audit — Yoga-Go (paywall)

**Live:** https://plykhvar-glitch.github.io/yogago-paywall-rebuild/
**Paywall on a phone:** https://plykhvar-glitch.github.io/yogago-paywall-rebuild/?view=proto

Yoga-Go asks 34 steps of questions (goal, weight, goal weight, age, a special occasion and its date) and draws the user’s own curve on “Your 4-week yoga plan is ready!”. The paywall that follows reads “Get unlimited access to your personal yoga plan!”, the same for everyone. This audit rebuilds that one screen so it carries the plan back, in Yoga-Go’s own design and at Yoga-Go’s own prices. Three phones show the three people Yoga-Go’s Meta ads speak to: a weight-loss Tai Chi beginner, a 63-year-old on Chair Yoga, a woman over 50 on Wall Pilates. Their answers can be changed under each phone.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Name their goal in the paywall headline | CR +15–20% |
| 02 | Put 4.6 stars and 30 million people by the plans | CR +10–15% |
| 03 | Tick 12 months and show it per week | ARPU +10–15% |
| 04 | Show their curve and first week above the plans | CR +5–10% |
| 05 | Make the button say what it starts | CR +3–8% |

Closing the paywall goes straight into the app. There is no second paywall.

**Grounding.** Screens and copy from the Yoga-Go iOS onboarding and paywall. Prices ($14.99 a month, $44.99 for 3 months, $69.99 for 12 months) from the US App Store in-app purchase list, 20 November 2026. 4.6 from 90K ratings and the Ksnazzy review from the US App Store listing; 47M+ downloads and the reviews by Anna in Cornwall and Patti from yogago.welltech.com; “30+ million users have chosen us” from the app’s welcome screen. Ads from the Meta Ad Library, 20 November 2026. 61% is $69.99 against 12 × $14.99 = $179.88; $1.35 a week is $69.99 ÷ 52. Weights and dates in the prototype are sample values.

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps, not measured lift for Yoga-Go.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
