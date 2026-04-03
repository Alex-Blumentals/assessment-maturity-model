# Twin Ladder Assessment Maturity Model v1.1

**Seven-Pillar Rubric for AI Literacy and Competence Assessment**

Framework Version: 1.1.0 | License: CC BY-SA 4.0 | TwinLadder Research

## Overview

This document defines the detailed maturity model for the Twin Ladder Assessment framework's seven pillars: **Awareness, Policy & Data Protection, Training, Tools, Evidence, Governance, and Authority Delegation & Decision Boundaries**. Each pillar is evaluated across four maturity stages:

| Stage | Score Range | Label |
|-------|------------|-------|
| 1 | 0-25 | **Exploring** |
| 2 | 26-50 | **Developing** |
| 3 | 51-75 | **Implementing** |
| 4 | 76-100 | **Optimizing** |

These map to the Twin Ladder Framework levels:
- **Exploring / Developing** = working toward **Level 0 (AI Literacy)** — the Article 4 compliance floor
- **Implementing** = achieving **Level 1 (Professional Twin)** — implied by Article 4's "context" requirement
- **Optimizing** = progressing through **Level 2 (Operational Twin)** toward **Level 3 (Ecosystem Twin)**

The compliance floor (Article 4 baseline) falls at approximately score 50-55. Scores below represent regulatory risk. Scores above represent the competence mission.

### The Competence Paradox

AI simultaneously improves performance and degrades capability. Organisations that adopt AI tools without structured competence development accumulate "competence debt." This model detects and counteracts that paradox.

### Compliance vs. Competence

Article 4 establishes a floor, not a ceiling. This model interprets "sufficient" as requiring at minimum the Developing stage (26-50) across all pillars, with the Expert Standard targeting Implementing (51-75).

### Competitive Positioning

Twin Ladder is the only framework that is simultaneously:

1. **Competence-specific** — centres entirely on individual and organisational AI competence, not governance, risk management, or technical safety
2. **Article 4-native** — purpose-built for the EU AI Act's literacy obligation, not retrofitted from a broader governance model
3. **Open-source** — released under CC BY-SA 4.0; free to adopt, adapt, and redistribute
4. **Individual + organisational** — assesses both per-person competence (Levels 0-3) and organisational maturity (seven-pillar scoring), producing evidence for both Article 4 and ISO 42001 Clause 7.2
5. **Workflow-based** — measures practical competence through task appropriateness, output verification, and risk judgment, not technical knowledge testing

No other framework reviewed — from ISO 42001 to Gartner's five-level model to MITRE's twenty-dimension assessment — combines all five characteristics. Most frameworks treat competence as one dimension among many; Twin Ladder makes it the entire methodology.

---

## Pillar 1: Awareness (AI Literacy & Awareness)

**Weight:** 0.15 | **Expert Standard:** 70

**What this measures:** Whether staff understand what AI systems are used, can articulate limitations and risks, share organisation-wide understanding of Article 4 obligations, and consider the impact on persons affected by AI-driven decisions.

### Level 1 — Exploring (0-25)
No structured approach to AI awareness. Individual staff may use AI informally with no shared understanding.

**Indicators:**
1. No formal communication issued regarding AI use
2. Staff cannot name AI tools embedded in their daily software
3. No assessment of which roles interact with AI systems
4. No one can describe Article 4 requirements
5. AI adoption driven by individual experimentation with no management visibility
6. No consideration of how AI-driven outputs affect customers, applicants, or other third parties

**Threshold:** Fewer than 25% of AI-interacting staff can describe what AI systems do or identify limitations. No documented awareness activity.

### Level 2 — Developing (26-50)
Organisation has begun addressing awareness, typically triggered by regulatory pressure. Some staff received orientation-level information.

**Indicators:**
1. At least one awareness communication distributed organisation-wide
2. Leadership briefed on Article 4 obligations
3. Staff in high-exposure roles can name the AI tools they use
4. Some staff can describe AI limitations in general terms
5. Initial mapping of which roles interact with AI systems
6. Some recognition that AI outputs affect external persons, but no structured assessment of impact

**Threshold:** 50% of AI-interacting roles have received awareness communication. Leadership can articulate Article 4 at a general level.

### Level 3 — Implementing (51-75)
Structured AI literacy programme. Staff understand capabilities and limitations in their specific role context.

**Indicators:**
1. Structured literacy programme with documented objectives and role-specific content
2. Staff can articulate AI limitations specific to their professional context
3. New hires receive AI orientation calibrated to their role
4. Organisation-wide Article 4 awareness demonstrable across operational staff
5. Staff comfort with AI tools measured by periodic assessment
6. AI systems classified by impact on affected persons (customers, applicants, employees, patients); staff in high-impact roles trained on implications for those persons

**Threshold:** 75% of AI-interacting staff completed structured training. Staff identify risks in own workflows. Article 4 awareness extends beyond leadership.

### Level 4 — Optimizing (76-100)
AI literacy embedded in organisational culture. Staff anticipate how emerging capabilities affect their work.

**Indicators:**
1. AI literacy embedded in performance expectations and professional development
2. Staff proactively identify anomalous AI outputs without prompting
3. Organisation tracks emerging AI developments and communicates relevance
4. Peer-to-peer AI knowledge sharing is active and organic
5. Periodic literacy assessments inform targeted refresher training
6. Affected-person impact is a standing element in AI deployment reviews; staff routinely assess how AI outputs affect third parties before acting on them

**Threshold:** 90%+ of AI-interacting staff demonstrate contextual literacy through verified assessment. Staff evaluate new AI tools independently.

---

## Pillar 2: Policy & Data Protection

**Weight:** 0.20 | **Expert Standard:** 60

**What this measures:** Formal, enforced policies governing AI use — acceptable use boundaries, prohibited applications, procurement approval, risk classification — integrated with GDPR-compliant data protection for AI workflows.

### Level 1 — Exploring (0-25)
No formal AI policy. AI use is ungoverned. Shadow AI pervasive. No data classification for AI tools.

**Indicators:**
1. No written document governs AI use
2. Staff use personal AI accounts for work with no oversight
3. No distinction between acceptable and prohibited applications
4. No process for evaluating new AI tools before adoption
5. Confidential information may enter AI tools without controls
6. No data classification for AI tools; staff unaware that sending personal data to LLMs may constitute an international transfer under GDPR

### Level 2 — Developing (26-50)
AI policy exists in draft or initial form. Some boundaries communicated but enforcement inconsistent. Basic data protection awareness emerging.

**Indicators:**
1. Formal AI use policy drafted/published addressing permitted tools, data, and review
2. Acceptable and prohibited use cases defined in writing
3. Basic approval process exists for new AI tools
4. Staff aware policy exists and can locate it
5. Data protection considerations identified
6. Basic data classification exists; approved AI tool list considers data processing locations and arrangements; privacy notices do not yet mention AI-assisted processing

### Level 3 — Implementing (51-75)
Comprehensive, enforced, regularly reviewed policy. Role-specific acceptable use boundaries. GDPR integration operationalised.

**Indicators:**
1. Policy covers all AI-interacting roles, data classification, review requirements, consequences
2. Use cases categorised by risk level
3. Formal approval workflow for AI tool procurement
4. Policy compliance monitored through regular checks
5. Policy undergoes scheduled review (annually minimum)
6. DPIA completed for AI tools processing personal data; DPAs in place with AI providers; staff trained on which data categories are permissible per tool

### Level 4 — Optimizing (76-100)
Living governance instrument, continuously refined. Policy drives strategic AI adoption. Privacy-by-design embedded.

**Indicators:**
1. Version-controlled policy with change logs and event-driven review
2. AI use cases mapped to specific roles, workflows, and decision points
3. Risk-based approval with expedited paths for low-risk tools
4. Policy effectiveness measured through compliance metrics and incident rates
5. Organisation contributes to industry-level policy development
6. Privacy-by-design embedded in AI workflows; automated data classification for AI inputs; regular AI data flow audits; Article 22 GDPR compliance verified for automated decisions affecting individuals

---

## Pillar 3: Training (Training & Development)

**Weight:** 0.20 | **Expert Standard:** 50

**What this measures:** Structured, role-specific AI training building workflow-based competence — output verification, risk identification, ethical boundaries, task appropriateness judgment — for all persons interacting with AI systems on the organisation's behalf, including contractors and outsourced providers.

### Level 1 — Exploring (0-25)
No structured AI training. Staff self-taught through trial-and-error.

**Indicators:**
1. No formal training programme for any role
2. Staff entirely self-taught on AI tools
3. No role-specific training materials
4. AI competence neither assessed nor tracked
5. Any training is generic technical content, not workflow-based
6. Contractors and outsourced service providers receive no AI literacy training or requirements

### Level 2 — Developing (26-50)
Initial training provisions. Some structured content exists, beginning to shift to practical competence.

**Indicators:**
1. At least one structured training module available
2. Content addresses practical skills — verification, limitation recognition
3. Training available for high-exposure roles
4. Self-assessment mechanisms exist
5. Training completion recorded
6. Some awareness that contractors need AI training, but no formal inclusion in programme

### Level 3 — Implementing (51-75)
Comprehensive role-specific programme. Workflow-based methodology. Competence assessed through practical evaluation.

**Indicators:**
1. Role-specific programmes for all major AI-interacting functions
2. Workflow-based approach with scenarios from actual practice
3. Competence assessed through practical evaluation, not just knowledge testing
4. Materials updated quarterly
5. Continuous learning infrastructure beyond initial training
6. Contractors, temporary workers, and outsourced providers included in AI literacy requirements; outsourcing contracts include AI competence clauses

### Level 4 — Optimizing (76-100)
Continuously optimised based on competence data. Self-sustaining learning ecosystem.

**Indicators:**
1. Validated competence framework with measurable benchmarks per role
2. Training effectiveness measured through outcome metrics
3. Periodic reassessment with personalised development paths
4. Internal AI competence certification recognised as meaningful
5. Deliberate practice and AI-free assessments address competence paradox
6. Third-party competence verification integrated into vendor management; AI literacy requirements in procurement specifications

---

## Pillar 4: Tools (Technical Infrastructure)

**Weight:** 0.15 | **Expert Standard:** 55

**What this measures:** Control over AI technical infrastructure — tool inventory, human oversight mechanisms, data protection compliance, risk classification.

### Level 1 — Exploring (0-25)
No visibility into AI tools. Shadow AI prevalent. No oversight mechanisms.

**Indicators:**
1. No inventory of AI tools exists
2. Staff use consumer-grade AI (personal accounts) for work including sensitive info
3. No human review requirement for AI outputs
4. No DPIAs for AI tools
5. No risk-level distinction between AI tools

### Level 2 — Developing (26-50)
Begun documenting AI tool landscape. Partial inventory. Some review processes.

**Indicators:**
1. Partial AI tool inventory covering primary tools known to management
2. Human review required for high-risk AI outputs
3. Basic data protection checks for primary tools
4. Basic risk classification (approved vs not-yet-assessed)
5. Some controls to limit unapproved tools

### Level 3 — Implementing (51-75)
Comprehensive maintained inventory with risk classifications. Systematic oversight.

**Indicators:**
1. Complete tool inventory with ownership, purpose, data classification, risk, review dates
2. Systematic human oversight defined by risk level
3. DPIAs completed for all relevant tools
4. Tools classified by risk with corresponding controls
5. Technical controls complement policy (enterprise accounts, DLP, access controls)

### Level 4 — Optimizing (76-100)
Strategic AI tool management. Live registries. Continuous monitoring. Proactive evaluation.

**Indicators:**
1. Live AI tool registry with usage metrics as management tool
2. Audit trails linking AI outputs to human review decisions
3. Continuous performance monitoring including accuracy and drift detection
4. AI-specific incident response process
5. Proactive risk-based evaluation with post-deployment monitoring

---

## Pillar 5: Evidence (Evidence & Documentation)

**Weight:** 0.15 | **Expert Standard:** 40

**What this measures:** Whether the organisation can demonstrate compliance if audited — training records, competence assessments, policy documents, incident logs, decision trails, and proportionality reasoning.

### Level 1 — Exploring (0-25)
No systematic documentation. Nothing to show a regulator.

**Indicators:**
1. No centralised repository for AI compliance documentation
2. Training completions not tracked
3. AI-related decisions not documented
4. Incidents not logged
5. No evidence portfolio, no audit preparation

### Level 2 — Developing (26-50)
Begun building evidence base. Training records captured for recent activities. Some documentation exists.

**Indicators:**
1. Training completion records exist for recent activities
2. AI policy document maintained in retrievable format
3. Some incidents documented, though inconsistently
4. Basic evidence could be assembled if requested — scattered but extant
5. Retention policy developing

### Level 3 — Implementing (51-75)
Comprehensive audit-ready evidence portfolio. Systematic capture and retrieval.

**Indicators:**
1. Centralised evidence portfolio with sections per compliance pillar
2. Training records include competence assessment results
3. Structured incident documentation (what, when, tool, impact, corrective action)
4. Timestamped evidence with version information
5. Defined retention policy aligned with regulatory expectations
6. Proportionality reasoning documented — a record of why the organisation's AI literacy measures represent its best effort given available resources, organisational size, and AI deployment profile

### Level 4 — Optimizing (76-100)
Living compliance instrument. Automated capture. Evidence drives continuous improvement.

**Indicators:**
1. Automated evidence capture (training completions, competence scores, usage data)
2. Independent verification elements (external audits, third-party certifications)
3. Evidence analysis drives governance decisions (trends, gaps, effectiveness)
4. Lessons-learned process feeds into policy and training updates
5. Portfolio structured for regulatory engagement
6. Proportionality reasoning reviewed annually and updated when resources, headcount, or AI deployment profile changes

---

## Pillar 6: Governance (Ethical & Responsible Use)

**Weight:** 0.15 | **Expert Standard:** 45

**What this measures:** Accountability structures, ethical oversight, regulatory monitoring. The capstone pillar ensuring all other pillars function as an integrated system.

### Level 1 — Exploring (0-25)
No one responsible for AI governance. No ethical review. No regulatory monitoring.

**Indicators:**
1. No designated AI governance responsibility
2. Ethical considerations not part of AI deployment decisions
3. No monitoring of AI regulatory developments
4. No escalation path for ethical concerns
5. No coordination between compliance activities

### Level 2 — Developing (26-50)
Governance responsibility assigned informally. Some ethical consideration. Some regulatory awareness.

**Indicators:**
1. Named individual responsible for AI governance (even as additional duty)
2. Basic ethical checklist for significant AI decisions
3. Monitoring of major regulatory developments
4. Mechanism to raise ethical concerns
5. Some cross-pillar coordination through governance lead

### Level 3 — Implementing (51-75)
Dedicated governance structure. Ethical review integrated. Systematic regulatory monitoring.

**Indicators:**
1. Dedicated AI governance team/committee with defined mandate and cadence
2. Ethical review process for AI deployments above risk threshold
3. Systematic regulatory monitoring with governance actions
4. Cross-pillar coordination ensuring coherence
5. Governance reporting to senior leadership/board
6. For organisations operating in multiple EU jurisdictions: governance structures account for national implementation variations (e.g., German works council co-determination rights under BetrVG Section 87 for AI systems monitoring employee behaviour or performance)

### Level 4 — Optimizing (76-100)
Strategic governance function with board visibility. Ethics review has authority. Sector leadership.

**Indicators:**
1. Board-level AI governance reporting with KPIs
2. Ethics review with decision-making authority (can block deployments)
3. Organisation contributes to sector-level governance standards
4. Proactive regulatory intelligence anticipating changes
5. Governance enables responsible innovation within clear guardrails
6. Jurisdiction-specific compliance requirements mapped and monitored; national enforcement practice differences integrated into governance decisions

---

## Pillar 7: Authority Delegation & Decision Boundaries

**Weight:** ~0.14 (1/7) | **Expert Standard:** 50

**What this measures:** How well the organisation defines, documents, and monitors the boundaries of AI decision-making authority. This pillar assesses whether delegation of decisions to AI systems is explicit, bounded, monitored, and reversible.

### Level 1 — Exploring (0-25)
No formal mapping of where AI systems make or influence decisions. Authority delegation is implicit and undocumented.

**Indicators:**
1. No decision inventory exists
2. AI systems operate with default vendor configurations
3. Nobody can identify where AI makes autonomous decisions vs assists humans
4. No escalation paths defined for situations outside AI authority boundaries
5. Authority boundaries not discussed at any governance level
6. No consideration of whether AI decision scope has changed since initial deployment

**Threshold:** Organisation cannot identify which decisions are made or influenced by AI. No documented authority boundaries for any AI system.

### Level 2 — Developing (26-50)
Organisation has begun identifying where AI makes decisions. Initial awareness of authority delegation risks.

**Indicators:**
1. Partial decision inventory for highest-risk systems
2. Some documentation of where AI output is used without human review
3. Leadership aware that authority delegation is a governance gap
4. Basic escalation paths defined for critical systems
5. Some stakeholders aware they interact with AI-assisted decisions
6. Initial assessment of delegation risk for highest-profile AI systems

**Threshold:** 50% of high-risk AI decision points identified. Leadership can articulate authority delegation as a governance concern.

### Level 3 — Implementing (51-75)
Structured authority boundary documentation. Decision inventory maintained. Escalation paths operational.

**Indicators:**
1. Complete decision inventory covering all AI systems
2. Documented authority boundaries (what the AI may decide, what requires human approval)
3. Operational escalation paths with named owners
4. Human override capability verified for high-risk systems
5. Stakeholder awareness of decision scope — affected persons know when AI influences decisions about them
6. Delegation risk assessment conducted for each AI system with documented proportionality reasoning

**Threshold:** All AI systems have documented authority boundaries. Escalation paths tested and operational. Human override verified for high-risk decisions.

### Level 4 — Optimizing (76-100)
Proactive authority governance. Continuous monitoring for authority creep. Board-level visibility.

**Indicators:**
1. Authority creep monitoring with automated alerts when AI systems exceed delegated scope
2. Regular authority boundary reviews (quarterly minimum) with documented outcomes
3. Accountability chains documented end-to-end — for every AI-assisted decision, the responsible human is identifiable
4. Board reporting on AI decision scope changes
5. Organisation contributes to sector authority delegation standards
6. Independence between AI systems and the governance mechanisms that oversee them

**Threshold:** 90%+ of AI systems under active authority monitoring. Board receives quarterly reports on delegation scope. Authority creep incidents detected and resolved proactively.

---

## Pillar Weight Rationale

The seven pillars are weighted as follows:

| Pillar | Weight |
|--------|--------|
| Awareness | ~0.14 |
| Policy & Data Protection | ~0.14 |
| Training | ~0.14 |
| Tools | ~0.14 |
| Evidence | ~0.14 |
| Governance | ~0.14 |
| Authority Delegation | ~0.14 |

**Why equal weighting?**

All seven pillars are necessary; none alone is sufficient. An organisation with excellent training but no policy is not compliant. An organisation with comprehensive governance but no evidence cannot demonstrate compliance. An organisation with strong governance but no clarity on which decisions AI is making has a structural blind spot. Article 4 does not prioritise any dimension over others — it requires "measures" (plural) addressing literacy holistically.

With the addition of Authority Delegation in v1.1, the weighting has been equalised across all seven pillars (~0.14 each, i.e. 1/7). The v1.0 slight overweighting of Training and Policy (0.20 each) has been retired in favour of uniform distribution. This reflects the recognition that authority delegation is as fundamental to AI competence as any other pillar — an organisation that cannot identify where AI makes decisions cannot meaningfully claim compliance with any other pillar.

These weights reflect the current calibration of the standard. They may be adjusted by the Standard Governance Board based on enforcement practice data, national competent authority guidance, and empirical evidence from assessment deployments. Any weight adjustment will follow the public comment process described in the Versioning & Governance section.

---

## Cross-Pillar Dependencies

### Dependency Matrix

Pillars do not exist in isolation. Maturity in one pillar often depends on maturity in another. The following matrix identifies the primary dependencies:

| Pillar | Depends On | Rationale |
|--------|-----------|-----------|
| **Awareness** | Tools | You cannot build awareness of AI systems you have not inventoried. Tool discovery precedes literacy. |
| **Policy** | Awareness | Policy requires understanding what AI is used and how — awareness informs policy design. |
| **Policy** | Tools | Policy must reference specific tools and data flows; a policy without a tool inventory is abstract. |
| **Training** | Awareness | Training content derives from awareness of what systems exist and what risks they present. |
| **Training** | Policy | Training teaches the rules; those rules must exist in policy first. |
| **Evidence** | Tools | You cannot document AI usage you do not know exists. Tool inventory is the evidence foundation. |
| **Evidence** | Training | Evidence of competence requires a training programme that produces assessable results. |
| **Governance** | Policy | Governance enforces and reviews policy; without policy, governance has nothing to govern. |
| **Governance** | Evidence | Governance decisions require evidence of current state; without evidence, governance is uninformed. |
| **Authority Delegation** | Tools | You cannot map decision boundaries for AI systems you have not inventoried. Tool discovery precedes authority mapping. |
| **Authority Delegation** | Governance | Authority boundaries must be embedded in governance structures; without governance, delegation is unaccountable. |
| **Authority Delegation** | Policy | Authority boundaries operationalise policy rules; without policy, delegation has no framework. |
| **Governance** | Authority Delegation | Governance oversight requires visibility into what AI systems are authorised to decide; without authority mapping, governance is incomplete. |

### Anomaly Detection Rules

When pillar scores are inconsistent with the dependency matrix, the assessment should flag the anomaly for review. Inconsistent scores often indicate either measurement error or a structural gap that undermines the higher-scoring pillar.

| Anomaly Pattern | Interpretation | Action |
|----------------|---------------|--------|
| Tools < 25, Evidence > 50 | Cannot document what you do not know exists | Verify Evidence pillar responses; likely overestimated |
| Policy < 25, Training > 50 | Training without policy boundaries is unanchored | Assess whether training content actually references enforceable standards |
| Awareness < 25, Policy > 50 | Policy exists but no one understands the landscape it governs | Policy may be aspirational rather than operational |
| Training < 25, Evidence > 50 | Evidence of competence without a training programme | Evidence may consist of policy documents only, not competence records |
| Tools < 25, Governance > 50 | Governing AI without knowing what AI is deployed | Governance may be performative rather than substantive |
| Tools < 25, Authority Delegation > 50 | Mapping decision boundaries without knowing what AI exists | Authority boundaries likely incomplete or aspirational |
| Authority Delegation < 25, Governance > 50 | Governance without knowing what AI is authorised to decide | Governance cannot oversee what it cannot see |
| Policy < 25, Authority Delegation > 50 | Authority boundaries defined without policy framework | Delegation rules lack enforceable foundation |

**Tolerance threshold:** A difference of more than 40 points between dependent pillars (where the dependency scores lower) should trigger manual review. A difference of more than 50 points should be flagged as a likely measurement error.

### The Lowest-Pillar Principle

An organisation's compliance posture is only as strong as its weakest pillar. Sophisticated training cannot compensate for absent governance. Comprehensive evidence cannot substitute for missing policy. This principle has practical consequences:

- An organisation scoring 80 across six pillars but 20 on Tools has a **systemic blind spot** — it does not know what AI systems are in use, making all other pillars unreliable.
- An organisation scoring 70 across six pillars but 15 on Evidence **cannot demonstrate compliance** — regardless of actual competence, it will fail a regulatory inquiry.
- An organisation scoring 65 across six pillars but 10 on Governance **lacks accountability** — no one is responsible for ensuring the other pillars function as a system.
- An organisation scoring 75 across six pillars but 5 on Authority Delegation **cannot articulate what AI decides** — without knowing where authority has been delegated, oversight is performative.

The weighted overall score may mask these vulnerabilities. The Lowest-Pillar Principle ensures they surface.

### Certification Requirements

**Certified** status requires overall weighted score >= 75 AND every pillar >= 50.

### Twin Ladder Level Mapping

| Twin Ladder Level | Score Range | Regulatory Status |
|---|---|---|
| Level 0 — AI Literacy | 40-55 | Article 4 compliance floor |
| Level 1 — Professional Twin | 55-70 | Implied by "context" requirement |
| Level 2 — Operational Twin | 70-85 | Strategic advantage |
| Level 3 — Ecosystem Twin | 85-100 | Market leadership |

---

## Scoring Layers

The maturity model produces data at three levels of abstraction, each designed for a different audience and decision context.

### Strategic Layer (Board / C-Suite)

**Audience:** Board members, CEO, COO, General Counsel
**Cadence:** Quarterly reporting; event-driven updates on material changes

**Metrics:**
1. **Overall maturity score** — single weighted number (0-100) representing organisational AI competence posture
2. **Compliance risk exposure** — traffic-light classification (Red: below compliance floor on any pillar; Amber: within 10 points of compliance floor; Green: all pillars above floor with margin)
3. **Investment priorities** — rank-ordered list of pillars requiring budget allocation, derived from gap analysis
4. **Sector benchmark position** — percentile ranking against peer organisations in same sector and size band (when benchmark data is available)
5. **Trend direction** — quarter-over-quarter change in overall score and per-pillar scores

The Strategic Layer answers: *Are we compliant? Where should we invest? How do we compare?*

### Tactical Layer (Department Heads)

**Audience:** Department heads, HR directors, compliance officers, CTO/CIO
**Cadence:** Monthly review; post-assessment update

**Metrics:**
1. **Per-pillar scores** — seven individual scores with level classification (Exploring / Developing / Implementing / Optimizing)
2. **Gap analysis** — for each pillar, the specific indicators not yet satisfied and the distance to the next maturity level
3. **Training recommendations** — prioritised list of training interventions by department and role, derived from pillar scores and dependency analysis
4. **Implementation roadmap** — sequenced action plan respecting cross-pillar dependencies (e.g., complete tool inventory before attempting evidence portfolio)
5. **Anomaly flags** — any cross-pillar inconsistencies detected by the dependency matrix

The Tactical Layer answers: *Where exactly are the gaps? What should we do next? In what order?*

### Operational Layer (Individual)

**Audience:** Individual professionals, team leads, learning and development coordinators
**Cadence:** Per-assessment; continuous for learning path tracking

**Metrics:**
1. **Personal Twin Ladder level** — individual classification (Level 0: AI Literacy, Level 1: Professional Twin, Level 2: Operational Twin, Level 3: Ecosystem Twin)
2. **Learning path** — personalised sequence of modules addressing individual competence gaps, calibrated to role and current level
3. **Competence verification results** — per-skill assessment outcomes (workflow-based scenario performance, not quiz scores)
4. **Progress tracking** — movement toward next level with specific milestones identified
5. **Peer comparison** — anonymised position within role cohort (optional, organisation-configurable)

The Operational Layer answers: *Where am I? What should I learn next? Can I demonstrate competence?*

---

## Design Principles

1. **Comfort over code.** Indicators measure practical competence, not technical AI knowledge.
2. **Workflow-based assessment.** Anchored in observable workplace practices.
3. **Compliance as floor, competence as mission.** Distinguishes meeting Article 4 from building advantage.
4. **Competence paradox addressed.** Higher levels specifically counter AI dependence risks.
5. **Proportionality.** Maturity should be proportionate to AI risk profile.

---

## Appendix A: Article 4 Compliance Mapping

The following matrix maps each operative phrase of Article 4 to the Twin Ladder pillars it engages. **P** indicates the primary pillar; **S** indicates a secondary pillar.

| Article 4 Phrase | Awareness | Policy & Data Protection | Training | Tools | Evidence | Governance | Authority Delegation |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| "Providers and deployers of AI systems" | | | | **P** | | S | S |
| "shall take measures" | | | | | S | **P** | S |
| "to ensure, to their best extent" | | S | | | **P** | S | |
| "a sufficient level of AI literacy" | **P** | | S | | | | S |
| "of their staff and other persons dealing with the operation and use of AI systems on their behalf" | | S | **P** | S | | | |
| "taking into account their technical knowledge, experience, education and training" | S | | **P** | | | | |
| "the context in which the AI systems are to be used, and considering the persons or groups of persons on whom the AI systems are to be used" | **P** | S | | S | | S | **P** |

**Key findings from the mapping:**
- Every pillar is engaged by at least two operative elements. No pillar is redundant.
- The heaviest regulatory burden falls on **Awareness** (2 primary mappings), **Training** (2 primary), **Authority Delegation** (1 primary — the "context of use" and "affected persons" phrase directly requires understanding of AI decision boundaries), **Evidence** (1 primary, enabling factor throughout), and **Governance** (1 primary, enabling factor throughout).
- The "staff and other persons" phrase extends the obligation beyond employees to contractors, consultants, temporary workers, and outsourced service providers.
- The "context of use" and "affected persons" phrases make one-size-fits-all training legally insufficient. They also require organisations to understand where AI makes decisions that affect people — the core of Authority Delegation.

For the full line-by-line analysis including ambiguity notes, GDPR intersection mapping, and compliance floor justification, see the companion document: [ARTICLE4-MAPPING.md](ARTICLE4-MAPPING.md).

---

## Appendix B: Versioning & Governance

### Document Version

| Field | Value |
|-------|-------|
| **Version** | 1.1.0 |
| **License** | CC BY-SA 4.0 |
| **Published** | 2026-04-03 |
| **Next scheduled review** | August 2026 (aligned with Article 4 enforcement commencement) |

### Review Cadence

- **Annual major review** (x.0.0): structural changes to pillars, weights, scoring methodology, or maturity level definitions. Triggered by significant enforcement practice developments, Commission delegated acts, or harmonised standard publication.
- **Quarterly minor adjustments** (x.y.0): indicator refinements, new assessment questions, benchmark data updates, and editorial corrections. Triggered by user feedback, deployment data, or minor regulatory guidance.
- **Patch updates** (x.y.z): typographical corrections, formatting, and non-substantive clarifications.

### Standard Governance Board

The Twin Ladder Assessment Maturity Model is governed by a Standard Governance Board with the following structure:

- **Permanent chair:** Twin Ladder (as originating organisation and standard maintainer)
- **Board composition:** Representatives from adopting organisations, legal practitioners, data protection officers, and academic researchers. Composition to be formalised as adoption grows.
- **Decision authority:** Major version changes require Board approval. Minor adjustments may be published by the permanent chair with Board notification.

### Public Comment Process

Major version changes (x.0.0) follow a public comment process:

1. **Draft publication** — proposed changes published with rationale and impact assessment
2. **Comment period** — minimum 30 days for public comment via the project repository
3. **Response document** — all substantive comments addressed in a published response
4. **Final publication** — updated version published with change log

### Repository

The canonical version of this document and the associated assessment methodology are maintained at the Twin Ladder project repository. Contributions, issues, and proposed changes are welcome through the standard open-source contribution process.

---

*This document is the open-source standard for AI competence assessment under the Twin Ladder framework. It should be reviewed and updated as Commission guidance, enforcement practice, and harmonised standards develop.*
