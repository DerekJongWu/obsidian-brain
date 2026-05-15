---
type: company
sector: "cybersecurity"
sub_sector: "preemptive cloud security"
stage: "Seed"
status: "sourcing"
owner:
founded: 2024
hq: "New York, United States"
website: "https://blast.security"
linkedin: "https://linkedin.com/company/blast-security"
crunchbase:
pitchbook: "https://pitchbook.com/profiles/company/791786-71"
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-14
created: 2026-05-04
tags:
  - company
---

# Blast Security

> [!summary] One-Liner
> Preemptive cloud security platform that uses cloud-native guardrails (resource control policies, service control policies, KMS key policies) to prevent — rather than detect — misconfigurations and misuse across AWS, Azure, and Kubernetes, including AI/agentic workloads.

---

## Thesis Fit

**Why we like it:**
- Repeat cybersecurity founding team that previously built and sold Solebit (Solved IT) to Mimecast — Boris, Roi, and Ido worked together 11+ years
- Differentiated wedge in cloud security: preemptive prevention via cloud-native guardrails vs. reactive detection from CSPM/CNAPP incumbents
- Strong fit for Fin's financial-services LP base — every CISO is reevaluating cloud security stacks against rapidly evolving threats and AI workloads

**Relevant thesis:** [[]]

**Fin sub-sector:** Cybersecurity / Cloud Security

---

## Team

| Role | Person | Background |
|------|--------|------------|
| Co-Founder & CEO | [[Boris Vaynberg]] | 25 years cybersecurity; Co-Founder & CEO Solebit (acq. by Mimecast 2018); GM Mimecast Israel / VP Advanced Threat Detection; Elbit Systems (Intelligence & Cyber Products); Comsec; IDF (Network Security) |
| Co-Founder & CPO | Ido Bukra | ex-Staff PM SentinelOne; Senior PM Mimecast (2019–2022); Head of Customer Operations Solebit; IDF Security Research Team Leader (Unit work, 2012–2017); MBA + BSc College of Management Academic Studies |
| Co-Founder & CTO | Roi Panai | R&D Director Mimecast (2021–2022); Security R&D Group Leader Mimecast (2018–2021); Director of Research / Security R&D Team Leader Solebit; IDF Unit Matzov (Software Team Leader / Project Manager / C++ Dev); MS Open University of Israel |

---

## Business Description

- **Problem:** Existing cloud security stacks (CSPM, CNAPP, posture management) are reactive — they detect misconfigurations and risks after the fact, leaving 85–90% of preventable security gaps to be patched downstream by overstretched security teams.
- **Product:** Preemptive cloud security platform that programs cloud-native guardrails (AWS resource control policies, service control policies, KMS key policies; Azure / Kubernetes equivalents) using AI-generated security policies. Integrates with existing tools (Orca, Palo Alto, Wiz, Upwind) instead of replacing them. Covers infrastructure security and AI/agentic workloads (Bedrock, SageMaker guardrails).
- **Wedge / entry point:** Sit alongside existing CSPM/CNAPP deployments and turn detected risks into enforced cloud-native controls — addresses ~85–90% of security gaps via prevention.
- **Product capabilities (as of 2026-05-14, from demo):**
  - Generates guardrails based on existing infrastructure/services with defense-coverage % across organization units
  - Four enforcement methods: console, Terraform PR, direct deployment, Jira tickets
  - Operational impact simulation analyzes 6+ months of CloudTrail / log data to show historical effect of a proposed guardrail; auto-exclusions for Blast collector, manual exclusion rules with expiration
  - Multi-cloud (10 of 12 accounts monitored in demo environment)
  - Fetches violations from existing tools (e.g., Wiz, Upwind, Palo Alto) and maps guardrails to close ~200 Wiz violations with few clicks
  - Threat landscape coverage grouped by risk (ransomware, lateral movement, privilege escalation); MITRE ATT&CK framework mapping; coverage measurement for active threat campaigns
- **Concrete guardrail examples (as of 2026-05-14):**
  - Prevent S3 uploads with customer-provided encryption keys → stops ransomware attacks that encrypt data with external keys (53% defense coverage shown across partial enforcement)
  - Prevent AWS accounts from leaving organization — zero violations detected today but critical severity (could result in complete environment loss if exploited)

---

## Market & Competition

- **Market size:**
- **Key competitors:** 6 direct competitors per founder (some raising Series A pre-product); adjacent / integration partners include [[Orca]], Palo Alto, Wiz, Upwind
- **Differentiation:**
  - Preemptive (prevention via cloud-native guardrails) vs. reactive detection
  - Integrates with — rather than replaces — existing CSPM/CNAPP tools, lowering rip-and-replace risk
  - Coverage extends to AI/agentic workloads (Bedrock, SageMaker guardrails)
- **Positioning sharpened (as of 2026-05-14):** Not exposure/vulnerability management — prevention platform. Makes cloud environments preventative through efficient guardrail deployment. Targets orgs moving beyond remediation cycles; continuous defense platform vs. manual months-long implementations.

---

## GTM & Business Model

- **Buyer persona:** CISOs / cloud security leaders at cloud-native or cloud-heavy enterprises with existing CSPM solutions (transportation, financial services, tech design partners cited)
- **Pricing model:**
- **ACV:**
- **Contract structure:**

**Distribution strategy:**
- Land alongside existing CSPM/CNAPP deployments; expand via guardrail coverage across infra and AI workloads
- Potential leverage of Fin financial-services LP network (BlackStone, Citigroup, US Bank, MetLife) for enterprise design partnerships

---

## Traction

- 1.5 years operating (as of 2026-05-04)
- 5 paying customers — 4 closed, 1 in procurement (as of 2026-05-04)
- <$500K ARR; $1.1M total revenue (as of 2026-05-04)
- Design partners across transportation, financial services, and tech — all cloud-native/cloud-heavy with existing CSPM
- Headcount: 21 (4 engineering, 8 operations, 8 other per Harmonic 2026-05-04)
- Founder describes product as "mature" relative to a 1.5-year-old company

---

## Financing

| Date | Round | Amount | Investors |
|------|-------|--------|-----------|
| 2025-11-19 | Seed | $10M | 10D (lead), MizMaa Ventures |

**Current round:**
- Founder framing fundraising as opportunistic — driven by competitive market timing rather than capital need (as of 2026-05-04)
- Next steps: demo this week, off-the-shelf diligence materials to follow

---

## Deal Team Notes

- 2026-05-04: Intro call with Boris Vaynberg (CEO); Derek Wu and Richie Chaikof on Fin side
- Israeli founding team, 11+ years working together; 9 months of IDF reserve duty post-Oct 7
- Prior exit (Solebit → Mimecast): $10M ARR, customers including Cisco and Akamai
- Potential partnership angle via Fin's financial-services LP network (BlackStone, Citigroup, US Bank, MetLife)
- Adjacent Fin portfolio context: Witness AI (agentic security), Symphony (Sequoia-backed, confidential)
- 2026-05-14 product demo with [[Boris Vaynberg]] (CEO); Derek Wu and [[Richie Chaikof]] on Fin side. See [[Blast Security - 2026-05-14 Summary]]. Demo walked through guardrail authoring, operational-impact simulation, Wiz violation mapping, and MITRE ATT&CK coverage view.

---

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

---

## Next Steps

- [x] Product demo completed 2026-05-14
- [ ] Boris to send off-the-shelf diligence materials
- [ ] Evaluate partnership fit against Fin's financial-services LP base (CISO intros)
- [ ] Map competitive overlap vs. [[Witness AI]] and Symphony in agentic-security pillar
- [ ] Drill into 6-competitor landscape — which are pre-product vs. shipping?
- [ ] Validate Wiz / Upwind / Palo Alto integration paths (channel + co-sell potential)
