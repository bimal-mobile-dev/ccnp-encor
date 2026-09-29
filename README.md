# CCNP Enterprise – ENCOR (350-401) Study Resources

Material and resources for pursuing the **Cisco Certified Network Professional (CCNP) Enterprise** core exam — built from the current **350-401 ENCOR v1.2** exam topics, current as of September 2026.

## A note on currency

**v1.2 is the current blueprint** — a targeted refresh, not a full overhaul (contrast this with CCNA's upcoming v2.0 rebuild, covered in the separate CCNA guide in this collection). The six core domains and their weights are unchanged from v1.1, but the content within them moved meaningfully: the automation domain was **renamed "Automation and Artificial Intelligence"** with increased emphasis and updated Cisco platform names (**DNA Center is now Cisco Catalyst Center** throughout the blueprint), vendor-specific orchestration tool names (Chef, Puppet, Ansible, SaltStack) were removed from the blueprint wording in favor of general orchestration concepts, and the Security domain added explicit wireless authentication topics (802.1X, WebAuth, PSK, EAPOL 4-way handshake) while removing older NAC-specific wording. If your study material still says "DNA Center" or names specific automation tools in the objective text, it's teaching v1.1.

## Table of contents

- [Overview](#overview)
- [Practice with Edureify](#-practice-with-edureify)
- [Reference Material](#reference-material)
- [Study Guides By Domain](#study-guides-by-domain)

## Overview

- **Who is it for?** ENCOR is the mandatory core exam for the entire CCNP Enterprise track, and also qualifies toward CCIE Enterprise Infrastructure and CCIE Enterprise Wireless — the professional-level step up from CCNA (see the separate CCNA guide in this collection), aimed at network engineers with several years of hands-on enterprise infrastructure experience.
- **Core exam + concentration exam**: passing ENCOR alone doesn't earn the CCNP Enterprise certification — you also need to pass **one concentration exam** of your choice (e.g., SD-WAN, Advanced Routing, Wireless Design, or SD-Access), tailored to your specialization. This guide covers **ENCOR only**, the shared core every CCNP Enterprise candidate must pass.
- **No formal prerequisite** is enforced, but Cisco explicitly designs ENCOR assuming solid CCNA-level foundations (subnetting, OSPF single-area, basic switching) are already second nature — this is not a first networking exam.
- **Exam format**: 120 minutes, roughly 100 questions, multiple-choice, drag-and-drop, and simulation-based questions, delivered via Pearson VUE at a cost of around $400 USD. Passing score is reported on Cisco's internal 1000-point scale; **825 is the commonly cited passing threshold**, though Cisco doesn't publish this as an official fixed number.
- **Domain weights (v1.2):**

| Domain | Weight |
|---|---|
| 1.0 Architecture | 15% |
| 2.0 Virtualization | 10% |
| 3.0 Infrastructure | 30% |
| 4.0 Network Assurance | 10% |
| 5.0 Security | 20% |
| 6.0 Automation and Artificial Intelligence | 15% |

- **Test-taking strategies**
  - **Infrastructure alone is nearly a third of the exam** — OSPF (multi-area, well beyond CCNA's single-area treatment), EIGRP, BGP fundamentals, and Layer 2 technologies (VLANs, STP/RSTP, EtherChannel) are the highest-yield topics on the entire exam; a widely used study plan spends two full months here before moving to anything else
  - Security (20%) and Automation and AI (15%) together are more than a third of the exam and are the two domains that changed the most in v1.2 — don't rely on older study material for either
  - Hands-on lab practice (Cisco's own DevNet sandbox, or GNS3/EVE-NG) matters disproportionately for the simulation-based questions — reading alone won't build the muscle memory these require

## 🎯 Practice with Edureify

- 🤖 [AI Tutor](https://edureify.com/certification/exam/ccnp-encor)
- 🎓 [Training](https://edureify.com/certification/networking/ccnp-encor/training)
- 📝 [Practice Test](https://edureify.com/certification/networking/ccnp-encor/practice-test)
- 🎯 [Mock Exam](https://edureify.com/certification/networking/ccnp-encor/mock-exam)
- 📊 [Readiness Test](https://edureify.com/certification/networking/ccnp-encor/readiness-test)
- 📄 [Cheat Sheet](https://edureify.com/certification/networking/ccnp-encor/cheat-sheet)
- 📖 [Study Guide](https://edureify.com/certification/networking/ccnp-encor/study-guide)
- 🏠 [Exam Landing Page](https://edureify.com/certification/networking/ccnp-encor/landing)

## Reference Material

- [Official Cisco 350-401 ENCOR exam topics](https://learningnetwork.cisco.com/s/encor-exam-topics) — always verify against the current version here, and confirm you're viewing v1.2
- [Cisco DevNet Sandbox](https://developer.cisco.com/site/sandbox/) — free hands-on lab environments for automation and API practice
- [Cisco Learning Network](https://learningnetwork.cisco.com/) — official community forums and study resources

## Study Guides By Domain

- [Domain 1 - Architecture (15%)](ENCOR-Domain-1-Objectives.md)
- [Domain 2 - Virtualization (10%)](ENCOR-Domain-2-Objectives.md)
- [Domain 3 - Infrastructure (30%)](ENCOR-Domain-3-Objectives.md)
- [Domain 4 - Network Assurance (10%)](ENCOR-Domain-4-Objectives.md)
- [Domain 5 - Security (20%)](ENCOR-Domain-5-Objectives.md)
- [Domain 6 - Automation and Artificial Intelligence (15%)](ENCOR-Domain-6-Objectives.md)
