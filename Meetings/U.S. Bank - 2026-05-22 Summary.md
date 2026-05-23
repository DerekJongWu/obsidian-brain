---
type: meeting
date: 2026-05-22
company: "U.S. Bank"
attendees: "Derek Wu, Jake Fuchs, David Ridgway"
meeting_type: "LP working session — security / vulnerability mgmt"
transcript: "[[U.S. Bank - 2026-05-22 Transcript]]"
created: 2026-05-22
tags:
  - meeting
---

**[[U.S. Bank]]** | 2026-05-22 | Security working session — AI vulnerability remediation / CTEM

## Attendees

**Fin Capital:**
- [[Derek Wu]]
- [[Jake Fuchs]]

**U.S. Bank:**
- [[David Ridgway]] (Security — vulnerability management / CTEM)

## Transcript

[[U.S. Bank - 2026-05-22 Transcript]]

## US Bank Security Urgency & Context

- Leadership call triggered immediate need for AI vulnerability remediation solutions
  - Don (group leader) asked for companies "ready to go" for quick commercialization
  - Mythos announcement created an "oh shit moment" anticipation across the team
  - Concern: vulnerability volume could explode from 5 → 5,000+ once Mythos lands
- Traditional approach insufficient for new threat landscape
  - Previous focus: finding vulnerabilities, manual staff remediation
  - New challenge: attackers string multiple CVEs into complex attack patterns
  - Unclear which vulnerabilities pose real threats when combined
- US Bank's AI adoption constraints
  - GPT models available internally but deployment is slow
  - Security approval bottlenecks delay new model access
  - Speed mismatch: external tech advancement vs. internal processes

## Vulnerability Management Market Landscape

- Two distinct approaches identified:
  1. **Preemptive posture management**
     - Companies: [[Reach Security]], Audit Security, Doks
     - Focus: misconfiguration prevention, tech-stack optimization
     - "Patching walls before attackers arrive"
  2. **Reactive remediation**
     - Companies: Depth First, Backline
     - Focus: analyzing scanner telemetry, automated patching
     - Sits behind existing code scanners
- David's initial research focused on code-vulnerability scanning
  - Companies reviewed: Snyk, Barracuda Code, Aikido, Aisle (early-stage)
  - Snyk positioned more in application security vs. exposure management
- Mythos impact assessment
  - Initial fear: vulnerability-management companies obsolete
  - Reality: massive tailwind for existing players
  - Founders report increased demand, not decreased
  - Mythos detection vs. comprehensive remediation gap

## Remediation Spectrum & Next Steps

- Critical distinction: mitigation vs. full remediation
  - **Mitigation**: patching without core architecture changes (lower risk)
  - **Remediation**: fundamental code/configuration changes (higher impact)
- Build vs. buy consideration for US Bank
  - Mythos provides foundation but requires significant internal development
  - Alternative: purpose-built CTEM programs from specialized vendors

## Next Steps

- [[David Ridgway]] to clarify Don's specific requirements (posture management vs. code scanning)
- Fin to share company-overview document with US Bank leadership
- Determine whether Don's ask was off-the-cuff vs. strategic initiative
- Potential follow-up call with Don if interested
