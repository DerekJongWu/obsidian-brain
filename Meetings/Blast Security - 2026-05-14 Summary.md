---
type: meeting
date: 2026-05-14
company: Blast Security
attendees: Derek Wu, Richie Chaikof, Boris Vaynberg
meeting_type: demo
transcript: "[[Blast Security - 2026-05-14 Transcript]]"
created: 2026-05-14
tags:
  - meeting
---

# Blast Security Call Summary

> **Company:** [[Blast Security]] | **Date:** 2026-05-14 | **Type:** Demo

**Attendees:** [[Derek Wu]], [[Richie Chaikof]], [[Boris Vaynberg]] (Co-Founder & CEO, [[Blast Security]])

**Transcript:** [[Blast Security - 2026-05-14 Transcript]]

---

### Blast Security Product Demo

- Cloud security platform focused on prevention vs. remediation
  - Generates guardrails based on existing infrastructure/services
  - Provides defense coverage percentage across organization units
  - Four enforcement methods: console, Terraform PR, direct deployment, Jira tickets
- Guardrail example: Prevent S3 uploads with customer-provided encryption keys
  - Stops ransomware attacks that encrypt data with external keys
  - 53% defense coverage shown across partial enforcement in accounts
  - System compares desired state vs. actual state automatically
- Operational impact simulation
  - Analyzes 6+ months of CloudTrail and other log data
  - Shows what would happen if guardrail existed historically
  - Automatic exclusions for system activities (Blast's own collector)
  - Manual exclusion rules with expiration options

### Platform Capabilities & Integration

- Multi-cloud support (10 of 12 accounts monitored in demo environment)
- Integration with security tools ([[Wiz]], Upwind, [[Palo Alto Networks]])
  - Fetches violations from existing tools
  - Maps guardrails to close ~200 Wiz violations with few clicks
- Threat landscape coverage
  - Groups guardrails by security risks: ransomware, lateral movement, privilege escalation
  - MITRE ATT&CK framework mapping
  - Measures coverage for active threat campaigns
- Critical example: Prevent AWS accounts from leaving organization
  - Zero violations detected but critical severity
  - Could result in complete environment loss if exploited

### Go-to-Market Positioning

- Not exposure/vulnerability management — prevention platform
- Makes cloud environments preventative through efficient guardrail deployment
- Targets organizations moving beyond remediation cycles
- Continuous defense platform vs. manual months-long implementations
