---
type: company
sector: cybersecurity
sub_sector: security exception / exclusion management
stage: Seed
status: sourcing
owner:
founded: 2025
hq: New York, NY
website: https://qeso.ai
linkedin:
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-18
created: 2026-06-09
tags:
  - company
---

# Qeso

> [!summary] One-Liner
> Control plane and system of record for every security control exclusion across the enterprise — connects to EDR/cloud/network controls plus Slack/Jira/ServiceNow to catalog, cross-correlate, and govern exclusions that today live in spreadsheets and Jira tickets. Founded by the Minerva Labs team (acquired by Rapid7 for $40M+) — raising $10M seed.

---

## Thesis Fit

**Why we like it:**
- Veteran repeat-founder team — Eddy Bobritsky and Eyal Gurevich both came up at Minerva Labs (acquired by Rapid7 in 2023 for $40M + $5M retention; ~$6M ARR on track at exit) and joined Rapid7 through the integration
- 82% of attacks exploit non-malware blind spots (CrowdStrike); 30% of successful ransomware attacks leveraged EDR exclusions (Microsoft, Oct 2025) — clear, validated pain
- AI/vibe coding is accelerating the exclusion-request problem at exponential rates (as of 2026-06-09)
- Cross-correlation of exclusions is the wedge into M&A, GRC, cyber insurance, pen testing — multiple paths to expansion
- One design partner active (CISO at CBC-level firm, ~$200K ARR); second design partner meeting next week (Henry at Barrel Fans, ex-Minerva customer)

**Relevant thesis:** [[]]

**Fin sub-sector:** Cybersecurity / Security Operations / Governance

---

## Team

| Role | Person | Background |
|---|---|---|
| CEO & Co-Founder | [[Eddy Bobritsky]] | 7 years IDF cyber officer (Israeli Navy Lt. + IDF Unit Matzov Captain); Co-Founder & CEO **Minerva Labs** (2014–2023, acquired by Rapid7); Strategy & BD at **Rapid7** post-acquisition (2023–2025); Advisor/Investor at **Suridata** (acquired by Fortinet); active angel via Jibe Ventures |
| COO & Co-Founder | Eyal (Eial) Gurevich | 9 years IDF cyber elite unit (J6 & Cyber Defense Directorate, IDF, 2006–2010); 6 years at **CyberArk** (2011–2016, Sales Engineer ME/Europe → Sales Executive); VP Sales & Strategy at **Minerva Labs** (2019–2023, through Rapid7 exit); Co-Founder & CEO 24 Minutes Media (2016–2019); CRO at OP Innovate + Colugo Systems; currently also VP Revenue & Strategy at Directeam |
| Co-Founder | Dani Kamanovsky | First Minerva employee; led endpoint security group at **Rapid7** across 5 teams and 4 continents (not yet in Harmonic) |

> Per Harmonic, Eddy Bobritsky's current employer is recorded as "Stealth Company (Eddy Bobritsky)" — Qeso.ai is not yet linked to his profile. Eyal Gurevich's current Harmonic employer is Directeam (VP Revenue & Strategy, May 2025–present); his Qeso role is not yet captured. Both confirmed as Qeso founders via meeting attendance and qeso.ai email domains.

---

## Business Description

- **Problem:** Every enterprise accumulates thousands of security control exclusions (EDR, cloud, network, etc.) that are never cleaned up or centrally tracked.
  - Average enterprise runs ~80 security controls; exclusions can number in the hundreds to tens of thousands per tool
  - Simple math: 20 controls × 100 exclusions × 2,000 assets = ~4M blind spots
  - CISOs surveyed couldn't estimate their total exclusion count, let alone which are still needed
- **Structural drivers of the problem:**
  - Disabling a security capability removes vendor liability entirely (per EULA)
  - Vendors have no incentive to add expiry dates: more exclusions = less liability for them
  - Siloed ownership: EDR exclusions owned by security, cloud by DevOps, network by IT; no cross-visibility
  - Currently managed via spreadsheets, Jira, or SharePoint at best
  - SIEMs are blind to exclusions: CrowdStrike stops forwarding logs for excluded assets, so the SOC can't see them either
- **Product (platform vision):** Control plane and system of record for all accepted risk across the org.
  - Connects to security controls, business tools (Slack, Jira, ServiceNow), threat intel, and software vendors
  - Cross-correlates exclusions to map compound attack vectors, not just catalog them
  - Longer-term: agentic infrastructure layer where AI agents request and receive scoped exclusion approvals automatically
- **Product detail (as of 2026-06-18):**
  - Connects to CrowdStrike, Microsoft, and ~50+ other platforms via API
  - Calculates "choke points" — the top 3-5 combined blind spots most likely to enable a breach
  - Also models attack paths from the outside in, narrating exactly how an attacker would move
  - Compensating controls engine: when an exclusion can't be removed, recommends mitigations (Microsoft ASR rules, AppLocker, scoped audit policies); steps ranked by ease of deployment, all free and low-risk
  - Simulation mode shows blast radius before any change is applied
  - Retroactive mapping for new customers — pulls existing exclusions from connected platforms (CrowdStrike API has a clean list); for systems without records (CI/CD, supply chain, internal tools), reconstructs context from experience
  - Day-one POC value: finds orphaned exclusions (deleted users, retired software, 15-year-old AD exceptions)
- **Roadmap highlights (as of 2026-06-18):**
  - Automated cleanup of unused exclusions (no business need = auto-remove)
  - Agentic workflow: developer requests access, security agent evaluates compound risk, grants and auto-revokes
  - Crowdsourced threat intel + vendor feeds to benchmark exclusion hygiene by industry
  - Custom connector builder so customers can onboard internal platforms without waiting for native support
- **Wedge / entry point:** Enterprise CISOs whose teams already feel the operational pain of unmanaged exclusions across 80+ tools — typically late-stage / regulated buyers (CBC-level firms).

---

## Market & Competition

- **Market:** New category — security exception / exclusion management. Today managed manually in spreadsheets, Jira, or SharePoint. No dedicated incumbent.
- **Adjacent expansion use cases:**
  - GRC audit / proof of review
  - M&A due diligence
  - Pen testing (white-box)
  - Cyber insurance underwriting
  - CISO policy enforcement
- **Validating stats (cited 2026-06-09):**
  - 82% of attacks exploit non-malware blind spots (CrowdStrike)
  - 30% of successful ransomware attacks leveraged EDR exclusions (Microsoft, Oct 2025)
- **Accelerant (as of 2026-06-09):** AI / vibe coding is creating exclusion requests at exponential rates from both employees and agents.

## GTM & Business Model

- **Buyer persona:** Enterprise CISOs at CBC-level firms (one active design partner already at this profile)
- **Pricing (as of 2026-06-09):** Design partner #1 at ~$200K ARR
- **Design partners (as of 2026-06-09):**
  - One CISO at CBC-level firm — ~$200K ARR discussion
  - Second design partner meeting next week — Henry at **Barrel Fans** (known from Minerva days)

## Traction

- Pre-product / design-partner phase as of 2026-06-09
- One design partner at ~$200K ARR conversation; one more being closed next week

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| In progress (June 2026) | Seed | $10M target; **Charlie Silverstein committed** | Seeking lead investor (prefer smart money with financial services connections; few weeks into lead conversations) |
| In progress (as of 2026-06-18) | Seed | $10M target; 24-month runway, $2M ARR target | **Silver Standard + one other VC** soft-circled at ~$1M each (not the lead); two Israeli VCs in advanced conversations, either could lead the full round |

- **Stage:** Seed
- **Entity structure:** US-incorporated
- **Team location:** Eyal already in NJ; Eddy and Dani in Israel, plan to relocate post-raise. Development team to be distributed (Israel, Europe, US).
  - **Update (2026-06-18):** Eyal Gurevich (COO) relocating to US post-raise to build US presence; current split is heavy Israel / light US.
- **Note:** Fin's SBIC vehicle has US headcount/operations requirements — worth monitoring against Qeso's planned team distribution.

## Deal Team Notes

- 2026-06-09 — First Granola-captured intro call. Derek Wu and Jake Fuchs on Fin side; Eddy Bobritsky (CEO), Eyal Gurevich (COO), Dani Kamanovsky on Qeso side. Granola id `48b2e2d9-e9b1-4812-9a65-10288cb85956`. See [[Qeso - 2026-06-09 Summary]].
- 2026-06-18 — Follow-up Granola call. Same attendees as 2026-06-09. Deep-dive on platform mechanics (choke-point calculation, attack-path modeling, compensating controls, simulation mode, retroactive mapping, agentic roadmap) and fundraise update (Silver Standard + one other VC soft-circled at ~$1M each; two Israeli VCs in advanced lead conversations). Granola id `3b30ff8d-faf4-4e2d-96a3-443f3129198e`. See [[Qeso - 2026-06-18 Summary]].
- Repeat-founder team out of Minerva Labs / Rapid7 — strong cybersecurity GTM bench. Eddy is a known commodity (Minerva exit, Rapid7 BD, Suridata/Fortinet advisor).
- Category-creation play — no clear incumbent in security exception management. Cross-correlation of exclusions across silos is the unique technical wedge.
- SBIC headcount/operations alignment is a question for diligence given the planned Israel/Europe/US split.
- Granola spelled co-founder name as "Dani Kamanovsky" — not in Harmonic; flagged.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Receive deck from Qeso (committed during call)
- [ ] Derek and Jake to confirm product demo for next week by end of week
- [ ] Validate design-partner #1 ($200K ARR) and confirm Henry at Barrel Fans as design-partner #2
- [ ] Reference Eddy via Rapid7 / Minerva alumni network on operator credibility
- [ ] Diligence the cross-correlation engine — is this just a catalog tool or a true compound-attack-vector mapper?
- [ ] Confirm SBIC headcount compatibility with planned team distribution
- [ ] Warm intros to potential co-investors if Fin moves forward (Derek/Jake)
- [ ] Locate Dani Kamanovsky on LinkedIn and add to Harmonic
