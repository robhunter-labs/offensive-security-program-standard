# OSPT — Framework component register

This register lists every component of the OSPT practice framework: its stable ID, public title, type, where it lives, the reader job it does, and its publication status. It records **publication state, not operational adoption** — a guide can be a complete publication while no organization has adopted it, and an adopter can tailor a local copy without making OSPT an external mandate. Those facts stay separate.

The register is the framework's front door: enter through a problem, find the component that bears on it, and see what it assumes before you open it.

## How to read a row

| Column | Meaning |
|---|---|
| **ID** | Stable identifier. Other documents refer to a component by ID, never by filename. |
| **Component** | Public title. |
| **Type** | Guide, Method, Template, Workbook (XLSX), Deck (PPTX + PDF), Diagram (SVG), Catalogue entry, or Register. |
| **Path** | Open the component directly. `downloads/` holds native files; `diagrams/` holds SVGs; everything else is Markdown under `components/` or the repository root. |
| **Reader job** | The one problem the component helps a reader solve. |
| **Status** | **Published** means the component is available in this repository. It does not mean an organization adopted or validated it. |

**Publication is not operational adoption.** A material correction to a component should carry a version note and a link to what changed. Retired IDs stay reserved.

## Reader routes

| Route | First useful question | Walk |
|---|---|---|
| **Practice lead** | What must be in place to run and improve a testing service at my scale? | 0001 → 0003 → 0009 → 0023/0024 → domain methods → 0027/0037 → 0038–0047/0057 → 0048–0052 → 0045 |
| **Working tester** | How do I turn a bounded engagement into defensible tests and evidence? | 0023/0024 → 0025 → 0009 → relevant 0010–0021 (+ 0022 catalogue) → 0029/0030 → 0027 → 0037 → 0035 |
| **Reviewer / assurance** | What was required, performed, reviewed, recorded, and left uncertain? | 0002 → 0003 → 0037 → 0052 → 0048–0051 → 0031 |
| **Adopter / contributor** | What can I copy, tailor, and question without mistaking it for a mandate? | README → 0002 → 0001 → a component's sources → correction route |

---

## Components

### Start here & authority

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0001 | Document Hierarchy & Control | Guide | [components/00-start-here/OSPT-0001-document-control.md](components/00-start-here/OSPT-0001-document-control.md) | Keep one current, traceable version of each standing document, and decide what belongs under control. | Published |
| OSPT-0002 | Framework Component Register | Register | [OSPT-REGISTER.md](OSPT-REGISTER.md) | This document: find any component, its job, type, and status. | Published |
| OSPT-0003 | Authority to Operate | Guide | [components/00-start-here/OSPT-0003-authority-to-operate.md](components/00-start-here/OSPT-0003-authority-to-operate.md) | Define the authority a testing service needs, and what stays the adopter's to grant. | Published |
| OSPT-0004 | Innovation & Capability Charter | Guide | [components/00-start-here/OSPT-0004-capability-charter.md](components/00-start-here/OSPT-0004-capability-charter.md) | Name the capabilities a practice commits to building and maintaining. | Published |

### Engagement setup

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0023 | Engagement Scoping Guide | Guide | [components/10-engagement/OSPT-0023-scoping-guide.md](components/10-engagement/OSPT-0023-scoping-guide.md) | Turn authority into a scoped, testable target without inventing reach. | Published |
| OSPT-0024 | Rules of Engagement — Template | Template | [components/10-engagement/OSPT-0024-rules-of-engagement.md](components/10-engagement/OSPT-0024-rules-of-engagement.md) | Record the permitted actions, limits, identities, and stop conditions for an engagement. | Published |
| OSPT-0025 | Methodology-to-Scoping Map | Guide | [components/10-engagement/OSPT-0025-scoping-map.md](components/10-engagement/OSPT-0025-scoping-map.md) | Choose which methods a given scope requires. | Published |
| OSPT-0026 | Scoping Requirements — Form | Workbook (XLSX) | [downloads/OSPT-0026-scoping-requirements-form.xlsx](downloads/OSPT-0026-scoping-requirements-form.xlsx) (+ [downloads/OSPT-0026-scoping-requirements-example.xlsx](downloads/OSPT-0026-scoping-requirements-example.xlsx)) | Collect the scope facts an engagement needs, with a worked example to exercise first. | Published |
| OSPT-0058 | Engagement Operational Brief — Template | Template | [components/10-engagement/OSPT-0058-operational-brief.md](components/10-engagement/OSPT-0058-operational-brief.md) | Give each engagement a go / no-go brief with its authorities named. | Published |
| OSPT-0053 | Engagement Process Flow | Diagram (SVG) | [diagrams/OSPT-0053-engagement-flow.svg](diagrams/OSPT-0053-engagement-flow.svg) (+ companion [components/10-engagement/OSPT-0053-engagement-flow.md](components/10-engagement/OSPT-0053-engagement-flow.md)) | See one engagement move through authority, design, testing, review, and delivery. | Published |

### Technical methods

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0009 | Methodology — Framework (umbrella) | Method | [components/20-methods/OSPT-0009-method-framework.md](components/20-methods/OSPT-0009-method-framework.md) | The common spine: how an observation becomes a reviewed, defensible finding. | Published |
| OSPT-0010 | Method — Web Application | Method | [components/20-methods/OSPT-0010-web-application.md](components/20-methods/OSPT-0010-web-application.md) | Test a web application against a target-specific plan, not a checklist. | Published |
| OSPT-0011 | Method — API | Method | [components/20-methods/OSPT-0011-api.md](components/20-methods/OSPT-0011-api.md) | Test whether each caller can do and see only what it should, across API styles. | Published |
| OSPT-0012 | Method — Mobile | Method | [components/20-methods/OSPT-0012-mobile.md](components/20-methods/OSPT-0012-mobile.md) | Test a mobile app across platform, build, and backend boundaries. | Published |
| OSPT-0013 | Method — Network | Method | [components/20-methods/OSPT-0013-network.md](components/20-methods/OSPT-0013-network.md) | Test a network's exposure, segmentation, and reachable services. | Published |
| OSPT-0014 | Method — Infrastructure | Method | [components/20-methods/OSPT-0014-infrastructure.md](components/20-methods/OSPT-0014-infrastructure.md) | Test hosts, services, and the paths between them. | Published |
| OSPT-0015 | Method — Database | Method | [components/20-methods/OSPT-0015-database.md](components/20-methods/OSPT-0015-database.md) | Test database access, privilege, links, and data exposure under authority. | Published |
| OSPT-0016 | Method — Thick Client | Method | [components/20-methods/OSPT-0016-thick-client.md](components/20-methods/OSPT-0016-thick-client.md) | Test a thick-client application and its trust and isolation boundaries. | Published |
| OSPT-0017 | Method — Wireless | Method | [components/20-methods/OSPT-0017-wireless.md](components/20-methods/OSPT-0017-wireless.md) | Test wireless networks and clients with ownership established first. | Published |
| OSPT-0018 | Method — NAC | Method | [components/20-methods/OSPT-0018-nac.md](components/20-methods/OSPT-0018-nac.md) | Test network access control without over-claiming a bypass. | Published |
| OSPT-0019 | Method — Physical | Method | [components/20-methods/OSPT-0019-physical.md](components/20-methods/OSPT-0019-physical.md) | Test physical controls safely, with per-technique authorization. | Published |
| OSPT-0020 | Method — Secure Code Review | Method | [components/20-methods/OSPT-0020-secure-code-review.md](components/20-methods/OSPT-0020-secure-code-review.md) | Review source for reachable, demonstrable weaknesses, not pattern counts. | Published |
| OSPT-0021 | Method — AI/LLM | Method | [components/20-methods/OSPT-0021-ai-llm.md](components/20-methods/OSPT-0021-ai-llm.md) | Test an AI/LLM system as a target (AI-as-target extension). | Published |
| OSPT-0022 | Tactical Testing Checklists | Catalogue entry | [components/20-methods/OSPT-0022-tactical-checklists-catalogue.md](components/20-methods/OSPT-0022-tactical-checklists-catalogue.md) | **Catalogue-only — no workbook distributed.** Explains the role of a tactical coverage workbook and directs adopters to maintain their own. | Published |
| OSPT-0032 | Threat-Informed Testing & CTI | Guide | [components/20-methods/OSPT-0032-threat-informed.md](components/20-methods/OSPT-0032-threat-informed.md) | Shape test design with threat intelligence without claiming a running CTI engine. | Published |
| OSPT-0056 | Threat Modeling | Guide | [components/20-methods/OSPT-0056-threat-modeling.md](components/20-methods/OSPT-0056-threat-modeling.md) | Build a threat model that feeds the engagement method. | Published |

### Evidence & reporting

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0027 | Required Testing Archival Files | Guide | [components/30-evidence/OSPT-0027-archival-files.md](components/30-evidence/OSPT-0027-archival-files.md) | Decide what evidence an engagement must retain and why. | Published |
| OSPT-0028 | Archive Storage Authority & Controls | Guide | [components/30-evidence/OSPT-0028-archive-storage.md](components/30-evidence/OSPT-0028-archive-storage.md) | Choose where evidence lives and what compensating controls apply. | Published |
| OSPT-0029 | Credential Handling | Guide | [components/30-evidence/OSPT-0029-credential-handling.md](components/30-evidence/OSPT-0029-credential-handling.md) | Receive, store, rotate, and retire engagement credentials safely. | Published |
| OSPT-0030 | Penetration Testing OpSec | Guide | [components/30-evidence/OSPT-0030-opsec.md](components/30-evidence/OSPT-0030-opsec.md) | Keep testing activity and data within the engagement's boundaries. | Published |
| OSPT-0037 | Report Standard & Template | Template | [components/30-evidence/OSPT-0037-report-standard.md](components/30-evidence/OSPT-0037-report-standard.md) | Write a report whose every finding carries its evidence, with a blank template and one synthetic finding. | Published |

### Operations & people

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0038 | Tester Onboarding | Guide | [components/40-operations/OSPT-0038-onboarding.md](components/40-operations/OSPT-0038-onboarding.md) | Bring a tester to readiness before they touch an engagement. | Published |
| OSPT-0039 | Tester Offboarding & Access Revocation | Guide | [components/40-operations/OSPT-0039-offboarding.md](components/40-operations/OSPT-0039-offboarding.md) | Revoke access and close out when a tester leaves the work. | Published |
| OSPT-0040 | Testing Workstation | Guide | [components/40-operations/OSPT-0040-workstation.md](components/40-operations/OSPT-0040-workstation.md) | Build and keep a controlled testing workstation and evidence custody. | Published |
| OSPT-0041 | Mobile Test Environment Guide | Guide | [components/40-operations/OSPT-0041-mobile-environment.md](components/40-operations/OSPT-0041-mobile-environment.md) | Stand up a mobile testing environment (fast-aging; check currency). | Published |
| OSPT-0042 | RACI Matrix | Workbook (XLSX) | [downloads/OSPT-0042-raci-matrix.xlsx](downloads/OSPT-0042-raci-matrix.xlsx) | Assign decision rights across engagement activities; adopters set their own roles. | Published |
| OSPT-0043 | Team Core Principles | Guide | [components/40-operations/OSPT-0043-team-principles.md](components/40-operations/OSPT-0043-team-principles.md) | The principles a testing team holds itself to. | Published |
| OSPT-0044 | Team Working Agreement | Guide | [components/40-operations/OSPT-0044-working-agreement.md](components/40-operations/OSPT-0044-working-agreement.md) | How the team agrees to work together. | Published |
| OSPT-0046 | Skills Matrix & Certification | Template | [components/40-operations/OSPT-0046-skills-matrix.md](components/40-operations/OSPT-0046-skills-matrix.md) | A blank, locally maintained map of skills and eligibility — no real roster. | Published |
| OSPT-0047 | Program Metrics & KPIs | Guide | [components/40-operations/OSPT-0047-metrics.md](components/40-operations/OSPT-0047-metrics.md) | Measure a testing practice without mistaking activity for health. | Published |
| OSPT-0057 | Managed Test Rig | Guide | [components/40-operations/OSPT-0057-test-rig.md](components/40-operations/OSPT-0057-test-rig.md) | Run a managed, repeatable test rig (fast-aging; check currency). | Published |
| OSPT-0036 | Consulting Training — Deck | Deck (PPTX + PDF) | [downloads/OSPT-0036-consulting-training-deck.pptx](downloads/OSPT-0036-consulting-training-deck.pptx) (+ `.pdf`) | A training deck for the consulting rotation, with a PDF equivalent. | Published |

### Support & assurance

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0031 | Coordinated Vulnerability Disclosure | Guide | [components/50-support/OSPT-0031-coordinated-disclosure.md](components/50-support/OSPT-0031-coordinated-disclosure.md) | Run a disclosure process with clear boundaries. | Published |
| OSPT-0033 | Quick Reaction Force — Urgent Response | Guide | [components/50-support/OSPT-0033-urgent-response.md](components/50-support/OSPT-0033-urgent-response.md) | Route an urgent retest or support surge without claiming a standing QRF. | Published |
| OSPT-0034 | Penetration Testing Consulting Guidebook | Guide | [OSPT-0034_Penetration_Testing_Consulting_Guidebook.md](OSPT-0034_Penetration_Testing_Consulting_Guidebook.md) (repository root) | Give post-test technical questions, retest, closure, escalation, and rotation a reliable home. | Published |
| OSPT-0035 | Closing Meeting — Deck | Deck (PPTX + PDF) | [downloads/OSPT-0035-closing-meeting-deck.pptx](downloads/OSPT-0035-closing-meeting-deck.pptx) (+ `.pdf`) | A closing-meeting template deck, with a PDF equivalent. | Published |
| OSPT-0048 | Audit & External Request Handling | Guide | [components/50-support/OSPT-0048-audit-handling.md](components/50-support/OSPT-0048-audit-handling.md) | Handle an audit or external information request safely. | Published |
| OSPT-0049 | Attestation & Audit Summary — Template | Template | [components/50-support/OSPT-0049-attestation-summary.md](components/50-support/OSPT-0049-attestation-summary.md) | Summarize what testing occurred for an assurance reader. | Published |
| OSPT-0050 | Program-Practice Q&A | Guide | [components/50-support/OSPT-0050-qa-reference.md](components/50-support/OSPT-0050-qa-reference.md) | A repeatable answer discipline for recurring program questions. | Published |
| OSPT-0051 | Audit Request & Disclosure Log — Template | Template | [components/50-support/OSPT-0051-disclosure-log.md](components/50-support/OSPT-0051-disclosure-log.md) | Record what was requested, released, and withheld, and why. | Published |

### Learning & stewardship

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0045 | Lessons-Learned & Continuous Improvement | Guide | [components/60-learning/OSPT-0045-learning-loop.md](components/60-learning/OSPT-0045-learning-loop.md) | Make sure a lesson from one engagement reaches the next. | Published |
| OSPT-0052 | Program Self-Assessment & Internal Audit | Guide | [components/60-learning/OSPT-0052-self-assessment.md](components/60-learning/OSPT-0052-self-assessment.md) | Check the practice against itself and find the gaps. | Published |

### Versioned extensions (AI & R&D)

| ID | Component | Type | Path | Reader job | Status |
|---|---|---|---|---|---|
| OSPT-0005 | Agentic AI Operating Framework | Guide | [components/90-extensions/OSPT-0005-ai-operating-framework.md](components/90-extensions/OSPT-0005-ai-operating-framework.md) | Where an AI agent may act in a human-led practice (AI-as-capability extension). | Published |
| OSPT-0007 | AI Tool Operating Procedure — Template | Template | [components/90-extensions/OSPT-0007-ai-tool-procedure.md](components/90-extensions/OSPT-0007-ai-tool-procedure.md) | A blank procedure for operating a specific AI testing tool. | Published |
| OSPT-0054 | R&D Build & Readiness | Guide | [components/90-extensions/OSPT-0054-rd-readiness.md](components/90-extensions/OSPT-0054-rd-readiness.md) | Decide when an R&D capability is ready to use. | Published |
| OSPT-0055 | AI Leadership Levers & Dials | Guide | [components/90-extensions/OSPT-0055-ai-leadership-levers.md](components/90-extensions/OSPT-0055-ai-leadership-levers.md) | Leadership questions for adopting AI in testing, with measurement first. | Published |

---

## Count and denominator

56 active IDs — **4** start-here & authority · **6** engagement setup · **16** technical methods · **5** evidence & reporting · **11** operations & people · **8** support & assurance · **2** learning & stewardship · **4** versioned extensions. (4 + 6 + 16 + 5 + 11 + 8 + 2 + 4 = 56.) All 56 have a public component here; OSPT-0022 is intentionally catalogue-only. Retired **OSPT-0006** and **OSPT-0008** are reserved history, not active components, and are intentionally absent.

## Native downloads

| ID | File(s) | Note |
|---|---|---|
| OSPT-0026 | [downloads/OSPT-0026-scoping-requirements-form.xlsx](downloads/OSPT-0026-scoping-requirements-form.xlsx), [downloads/OSPT-0026-scoping-requirements-example.xlsx](downloads/OSPT-0026-scoping-requirements-example.xlsx) | Blank fillable form + worked synthetic example. |
| OSPT-0035 | [downloads/OSPT-0035-closing-meeting-deck.pptx](downloads/OSPT-0035-closing-meeting-deck.pptx), [downloads/OSPT-0035-closing-meeting-deck.pdf](downloads/OSPT-0035-closing-meeting-deck.pdf) | Deck + PDF equivalent for readers without PowerPoint. |
| OSPT-0036 | [downloads/OSPT-0036-consulting-training-deck.pptx](downloads/OSPT-0036-consulting-training-deck.pptx), [downloads/OSPT-0036-consulting-training-deck.pdf](downloads/OSPT-0036-consulting-training-deck.pdf) | Deck + PDF equivalent. |
| OSPT-0042 | [downloads/OSPT-0042-raci-matrix.xlsx](downloads/OSPT-0042-raci-matrix.xlsx) | Editable decision-rights matrix. |
| OSPT-0053 | [diagrams/OSPT-0053-engagement-flow.svg](diagrams/OSPT-0053-engagement-flow.svg) | SVG diagram (text, accessible); must agree with OSPT-0009. |
| OSPT-0022 | *(none — catalogue-only)* | No workbook is distributed; adopters maintain their own checklists. |

## How to evaluate and adapt this framework

1. Enter through a reader route, then inspect the component's job, boundaries, local decisions, and sources before adopting it.
2. Use the method's test path or template as a starting point. Bind it to your own written authority, scope, roles, records, and obligations; a published page is not permission to test.
3. Check an external standard in its current edition and decide what applies to the target; this framework does not claim to replace it.
4. Try the native templates in the applications you actually use. The example workbook and [synthetic API walkthrough](examples/api-engagement/README.md) are illustrations, not proof that a practice operates.
5. Report broken links, unsafe implications, stale sources, or contradictions through the correction route below. A component may be improved or withdrawn without renumbering the rest.

## Corrections

Report a broken link, unsafe implication, stale external source, unusable example, or contradiction through the repository's [security and correction route](SECURITY.md) (`hello@robhunterworks.com` for a sensitive report). The register is updated on component release, supersession, or withdrawal — not on a fixed calendar.

---

Copyright © 2026 Rob Hunter. Original material is released under the MIT License.
