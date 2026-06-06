---
type: company
sector: cybersecurity
sub_sector: Cyber resilience / AI-native recovery
stage: Seed
status: sourcing
owner:
founded: 2024
hq: Israel
website: https://vivid.security
linkedin: https://linkedin.com/company/vivid-security
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-05
created: 2026-06-05
tags:
  - company
---

> [!info] One-Liner
> AI-native cyber resilience platform purpose-built for the NIST "Recover" pillar — continuously maps and tests an organization's full recovery stack (backups, infrastructure, dependencies) pre-incident, rather than reactively after a ransomware event. Founded by Unit 8200 Israel Defense Prize winners and backed by General Catalyst at seed.

## Thesis Fit

- Cyber resilience / recovery is a structurally underserved pillar of NIST — most security spend is in Identify / Protect / Detect / Respond; the Recover pillar is dominated by point backup tools rather than continuous testing of the full recovery stack.
- Strong founder pedigree: Ron Blachar (CEO) and Alum Feldman (CTO), both Unit 8200, with prior AI research that won the Israel Defense Prize.
- General Catalyst seed lead (Mark Crane as partner) — bluechip seed signal.
- Concrete six-figure-minimum ACVs already validated; one financial-services customer paid $600K for a single point-in-time DR assessment.

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Ron Blachar]] | Co-Founder & CEO at Vivid Security; ex-Unit 8200, Israel Defense Prize winner (AI research) |
| Co-Founder & CTO | Alum Feldman | Co-Founder & CTO at Vivid Security; ex-Unit 8200, Israel Defense Prize winner (AI research) |

> Co-founder names confirmed via the 2026-06-05 Granola summary. Harmonic returns only sparse data for vivid.security and a stale legacy "Vivid Security" record (an unrelated MSP) — co-founder profiles not yet linked into the canonical entity; flagged in Next Steps for manual enrichment.

## Business Description

- **Problem:** Recovery from cyber attacks is broken.
  - 93% of organizations take >4 days to recover from attacks; 34% take >3 weeks
  - Losses averaging $8M / day during recovery
  - 50%+ of organizations have misconfigured backups that fail ransomware best practices
  - Recovery is assumed based on backups + hope, but production environments constantly drift away from the backup assumption
- **Product:** First AI platform purpose-built for the NIST "Recover" pillar.
  - **Pre-incident** analysis vs. the reactive "doomsday button" approach
  - Continuously maps and tests the full recovery stack across backups, infrastructure, and dependencies
- **Three core components:**
  1. **Unified backup assessment** across multi-cloud / on-prem
     - 20–65% coverage gaps found in production customers
     - Enforces ransomware best practices (immutability, air gaps, encryption, MFA)
     - 20–50% cost-reduction opportunities identified
  2. **Dependency mapping** using military-grade graph technology
     - Maps interdependencies between priority assets
     - Surfaces how priority-3 asset failures break priority-0 recovery
     - Eliminates the need for traditional BIA (Business Impact Analysis) assessments
  3. **AI-powered recovery simulation** ("recovery pen testing")
     - Autonomous backup-restore testing at scale
     - Isolated-environment proof-of-concept validation
     - Growing toward full application-functionality testing

## Market & Competition

- **Market:** NIST Recover pillar — cyber resilience, BCP/DR automation, ransomware recovery testing
- **Adjacent / displacement targets:**
  - Traditional VM backup providers (Veeam, Rubrik, Cohesity, Commvault) — Vivid sits above them and tests / unifies them
  - EDR / detection-tier incumbents (CrowdStrike, SentinelOne) — Vivid customer cited paying 2x CrowdStrike rate for Vivid
- **Differentiation:** Pre-incident continuous recovery testing vs. reactive recovery tools; unified across multi-cloud / on-prem; military-grade dependency-graph technology from the founders' Unit 8200 background.

## GTM & Business Model

- All deals are **six-figure minimum**, including smaller orgs
  - One customer pays 2x CrowdStrike rate, more than VM-backup provider
  - Financial services customer (30K employees) paid **$600K for a single point-in-time DR assessment**
- **Target segments:** Manufacturing, healthcare, SaaS (uptime-critical), smaller financial services
  - Large banks show overconfidence — Vivid prefers approaching them with more traction first
  - Insurance and tier-2/3 financial institutions more receptive
- Current status: Handful of paying production customers; multi-cloud deployment achieved in 3 months with 5 engineers

## Traction

- Handful of paying production customers (as of 2026-06-05)
- All deals six-figure minimum
- One $600K single point-in-time DR assessment closed with a 30K-employee financial-services customer
- Multi-cloud deployment built out in 3 months with a 5-engineer team

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| Seed (per Granola, 2026-06-05) | Seed | TBD | General Catalyst (lead, Mark Crane partner) |

- Not actively fundraising as of 2026-06-05, but **open to right partner / terms given strong runway**.
- Harmonic does not yet have a clean canonical funding record for vivid.security — flagged in Next Steps.

## Deal Team Notes

- 2026-06-05 — Intro / first meeting with Ron Blachar (CEO) on Teams. Granola id `e2afccdf-1352-4e8e-bed6-88906b3a7c61`. Fin attendees: Derek Wu, Jake Fuchs. See [[Vivid Security - 2026-06-05 Summary]].
- Vivid was originally surfaced via Seth Spergel (Merlin Ventures) on the 2026-05-21 catch-up — Seth offered to intro Ron to Derek, and this is the resulting first meeting (~2 weeks turnaround).
- General Catalyst (Mark Crane) led the seed — bluechip seed signal; reconfirm round size and syndicate during follow-up.
- Harmonic canonical record for vivid.security is sparse (id 63203951; no description / headcount / employees / location). A separate legacy "Vivid Security" entity (urn:harmonic:company:32954870, founded 2000, MSP-style description, headcount 1) was Harmonic's typeahead best match — kept separate; the legacy record is NOT this company.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Fin to provide sales collateral for network pressure testing (commitment made on call)
- [ ] Fin to identify tier-2 / tier-3 financial institutions for warm intros
- [ ] Schedule product demo for Fin team to better visualize the platform
- [ ] Confirm seed round size, full syndicate, and Vivid's runway position
- [ ] Confirm co-founder Alum Feldman's full name spelling (Granola rendering — "Alum Feldman") and link both founders to the canonical Harmonic record (vivid.security id 63203951)
- [ ] Diligence: validate the "$600K single point-in-time DR assessment" pricing benchmark with one or two FS reference accounts
- [ ] Submit Harmonic data-report to disambiguate vivid.security (active cyber-resilience startup) from the legacy "Vivid Security" MSP record
