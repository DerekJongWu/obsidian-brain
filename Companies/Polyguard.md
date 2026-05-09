---
type: company
sector: cybersecurity
sub_sector: identity verification / anti-deepfake
stage: Pre-Seed
status: sourcing
owner: Daria Davydenko
founded: 2023
hq: Portland, OR
website: https://polyguard.ai
linkedin: https://linkedin.com/company/polyguard-ai
crunchbase: 
pitchbook: https://pitchbook.com/profiles/company/510386-77
deck_link: 
data_room: 
lighthouse_link: 
last_touch: 2026-05-08
created: 2026-05-08
tags:
  - company
---

> [!info] One-Liner
> Just-in-time biometric identity verification platform — combines biometric, document, and geolocation verification with cryptographic certificates ("SSL for humans") to defend audio/video communications against AI-driven fraud and deepfakes.

## Thesis Fit

NHI / identity at the human edge. Detection-only approaches will fall behind deepfake quality; Polyguard bets on friction-based verification — analogous to MFA adoption trajectory. Strong technical founders (CEO from Pivotal/Piston/NASA cloud).

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Joshua McKenty]] | Former VP at Pivotal; Co-Founder & CTO of Piston Cloud (acq. Cisco); Chief Cloud Architect at NASA; OpenStack board member |
| Co-Founder & CTO | Khadem Badiyan | Co-Founder & CEO of Aicon; Howard University; Stanford Online High School |

## Business Description

- **Problem:** Detection of deepfakes and AI-driven fraud will keep losing ground; static identity stacks (Jumio, Persona, etc.) cannot distinguish nation-state actors using American mules from legitimate international founders. Telemedicine, fintech, and high-value transactions need positive identity assurance during live audio/video.
- **Product:** Mobile app for just-in-time biometric verification that combines biometric, document, and geolocation verification, issues cryptographic certificates with chain of trust ("SSL for humans"), and supports live encrypted communications with automated compliance reporting.
- **Wedge:** Healthcare/telemedicine — DEA requires positive identity for controlled-substance prescribing over video.

## Market & Competition

- Detection-vs-friction thesis: organizations will accept higher friction when fraud risk outweighs friction cost — analogous to MFA.
- Indirect comparables: [[Nametag]] (replaced by Jumio for North American ID at one customer), Jumio, Persona — but those are document-centric, not multimodal/live.
- Novel tech:
  - "PG Presence" closes the second-screen gap
  - 3D smartphone data matched against 2D camera data (anti-spoof)
  - GPS-triggered credential step-up (US license outside country requires passport)
  - $10K hardware cost to spoof GPS = meaningful fraud barrier
  - Timestamp analysis detects location replay attacks

## GTM & Business Model

- **Healthcare:** Strongest adoption — telemedicine controlled-substance prescribing; no competitive awareness in vertical.
- **Financial services:** More fragmented — multiple existing vendor relationships create complex integration challenges.
- **Travel fintech pilot:** SEC-registered broker-dealer with novel high-value booking approach.
- **Agentic commerce / fraud:** iFood Brazil (10M deliveries/day) exploring partnership for fraud + agentic commerce.

## Traction

- Headcount: 6 (2 engineering, 3 ops, 2 people) (as of 2026-05-08)
- Product demo-ready since end of January 2026 (Android/iOS parity achieved)
- Started full-time sales February 2024 after Scale partnership ended
- Revenue currently de minimis, mostly healthcare customers (as of 2026-05-08)
- Plan: Close 1 deal/month to reach default-alive (Q3 2026 gap to patch)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| TBD (planned July–August 2024 ... reconfirm timing) | — | — | TBD |

- Not actively raising as of 2026-05-08, but low runway / low revenue / high confidence.
- Founder framed fundraise timing as "July–August 2024" in the call — likely a misstatement; reconfirm intended timing.
- Joshua McKenty was a $20M+ club founder at Piston Cloud (acquired by Cisco).

## Deal Team Notes

- Met 2026-05-08 with Logan Allin, Daria Davydenko, Claire Beale (Fin), Joshua McKenty and Khadem Badiyan (Polyguard). See [[Polyguard - 2026-05-08 Summary]].
- Title "Logan Allin and Joshua McKenty + Khadem Badiyan" — Khadem only attendee captured by Granola email-side; Joshua confirmed in the meeting context.
- No funding info on Harmonic — independently bootstrapped to date per founder.
- Reconfirm fundraise timing — founder said "July–August 2024" which appears to be a misstatement.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Reconfirm fundraise timing (founder said July–August 2024 — likely meant 2026)
- [ ] Healthcare reference checks — telemedicine customers
- [ ] Diligence on iFood Brazil partnership / travel fintech pilot conversion
- [ ] Technical diligence on PG Presence / 3D-2D matching anti-spoof claims
