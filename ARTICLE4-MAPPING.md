# EU AI Act Article 4 -- Twin Ladder Assessment Maturity Model Mapping

**Decision Record** | Date: 2026-03-08 | Status: Reference Document
**Framework Version:** Twin Ladder v1.0.0 (CC BY-SA 4.0)

---

## Table of Contents

1. [Article 4 Full Text and Legislative Context](#1-article-4-full-text-and-legislative-context)
2. [Line-by-Line Mapping to Six Pillars](#2-line-by-line-mapping-to-six-pillars)
3. [GDPR Intersection Mapping](#3-gdpr-intersection-mapping)
4. [Gap Analysis](#4-gap-analysis)
5. [Compliance Floor Justification](#5-compliance-floor-justification)
6. [Sources](#6-sources)

---

## 1. Article 4 Full Text and Legislative Context

### 1.1 Article 4 -- AI Literacy (Regulation (EU) 2024/1689)

> *Providers and deployers of AI systems shall take measures to ensure, to their best extent, a sufficient level of AI literacy of their staff and other persons dealing with the operation and use of AI systems on their behalf, taking into account their technical knowledge, experience, education and training, the context in which the AI systems are to be used, and considering the persons or groups of persons on whom the AI systems are to be used.*

**Entered into force:** 2 February 2025 (first wave of AI Act provisions, alongside Article 5 prohibitions).

**Penalty tier:** General obligations -- up to EUR 15 million or 3% of worldwide annual turnover (Article 99(4)).

### 1.2 Recital 20

Recital 20 provides the legislative intent behind Article 4:

> *In order to obtain the greatest benefits from AI systems while protecting fundamental rights, health and safety and to enable democratic control, AI literacy should equip providers, deployers and affected persons with the necessary notions to make informed decisions regarding AI systems. Those notions may vary with regard to the relevant context and can include understanding the correct application of technical elements during the AI system's development phase, the measures to be applied during its use, the suitable ways in which to interpret the AI system's output, and, in the case of affected persons, the knowledge necessary to understand how decisions taken with the assistance of AI will impact them. In the context of the application of this Regulation, AI literacy should provide all relevant actors in the AI value chain with the insights necessary to ensure the appropriate compliance with and the correct enforcement of this Regulation. Furthermore, the wide implementation of AI literacy measures and the introduction of appropriate follow-up actions could contribute to improving working conditions and ultimately sustain the consolidation and innovation path of trustworthy AI in the Union. The European Artificial Intelligence Board (the 'Board') should support the Commission to promote AI literacy tools, public awareness and understanding of the benefits, risks, safeguards and rights and obligations in relation to the use of AI systems. In cooperation with the relevant stakeholders, the Commission and the Member States should facilitate the drawing up of voluntary codes of conduct to advance AI literacy among persons dealing with the development, operation and use of AI.*

### 1.3 Related Recitals

- **Recital 19:** Addresses the broader importance of AI literacy for the public and for affected persons, connecting it to the fundamental rights framework.
- **Recital 21:** Emphasises the need for proportionality in AI literacy measures, recognising differences between providers and deployers.
- **Recital 91:** Links deployer obligations (Article 26) to human oversight and competence requirements for high-risk systems.
- **Recital 161:** Connects AI literacy to the AI Office's mandate for guidance and best practice sharing.

### 1.4 Key Interacting Provisions

| Provision | Relationship to Article 4 |
|-----------|--------------------------|
| **Article 5** (Prohibited practices) | Literacy needed to recognise prohibited AI uses |
| **Article 9** (Risk management) | Competent staff required to operate risk management systems |
| **Article 14** (Human oversight) | Literacy is prerequisite for meaningful human oversight of high-risk AI |
| **Article 26** (Deployer obligations) | High-risk deployer obligations require "sufficient technical competence, authority and resources" |
| **Article 50** (Transparency for GPAI) | Users must understand AI-generated content; literacy enables this |
| **Article 95** (AI Pact) | Voluntary commitments include AI literacy measures |
| **Article 99** (Penalties) | General obligation violations: up to EUR 15M / 3% turnover |

### 1.5 Commission Guidance and Implementing Measures

**Published:**
- **European Commission AI Literacy Q&A (May 2025):** Clarified that merely directing staff to user manuals is "generally not considered sufficient." Confirmed that the obligation applies from the moment an organisation uses any AI system, with no size threshold. Internal records of training are sufficient documentation; external certification not required.
- **Living Repository of AI Literacy Practices (2025):** Collection of 40+ AI literacy initiatives from AI Pact pledgers and public sector bodies, providing benchmarks for "best extent" compliance.
- **AI Act Service Desk -- Article 4 Guidance:** Operational guidance from the European AI Office on practical implementation.

**Announced / In Development (as of March 2026):**
- **General Purpose AI Code of Practice:** Final version published January 2026; includes literacy-adjacent obligations for GPAI providers regarding transparency and documentation.
- **Harmonised standards under Article 40:** European standardisation bodies (CEN/CENELEC) working on technical standards; AI literacy standards not yet finalised.
- **Commission implementing guidelines for deployers:** Expected to address proportionality in literacy requirements; no formal delegated act announced for Article 4 specifically.

**Notable absence:** No delegated or implementing act has been adopted specifically for Article 4. The Commission has relied on soft-law instruments (Q&A, repository, AI Pact) rather than binding supplementary measures. This leaves "sufficient level" and "best extent" as the primary interpretive standards, to be concretised through enforcement practice.

---

## 2. Line-by-Line Mapping to Six Pillars

### 2.1 Phrase-by-Phrase Analysis

Article 4 is a single sentence containing seven distinct operative elements. Each is mapped below to the Twin Ladder pillars and maturity levels.

---

#### Phrase 1: "Providers and deployers of AI systems"

**Scope:** Captures both sides of the AI value chain. A provider develops or places AI on the market. A deployer uses AI "under its authority." Not limited to high-risk AI -- applies to ALL AI systems including general-purpose tools (email AI features, CRM analytics, content generation, etc.).

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Tools** -- organisation must know which AI systems it operates |
| **Secondary pillar** | **Governance** -- accountability must cover both provider and deployer obligations |
| **Maturity threshold** | Implementing (51+): complete AI systems inventory with role assignments |
| **Observable evidence** | AI systems register with owner, classification (provider/deployer), and date of deployment |
| **Ambiguity** | The boundary between "provider" and "deployer" for customised AI solutions (e.g., fine-tuned models) is not fully resolved. Organisations that customise GPAI models may be both. |

---

#### Phrase 2: "shall take measures"

**Scope:** Mandatory obligation. "Shall" in EU legislative drafting is imperative. No opt-out, no de minimis threshold, no SME exemption from the obligation itself (only from its intensity, via proportionality).

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Governance** -- active measures require governance structures to initiate, fund, and oversee |
| **Secondary pillar** | **Evidence** -- measures must be documented to be demonstrable |
| **Maturity threshold** | Implementing (51+): documented programme with budget allocation and responsible owner |
| **Observable evidence** | Board/management decision authorising AI literacy programme; budget line item; named responsible person or team |
| **Ambiguity** | "Measures" is deliberately broad. The Commission Q&A clarified that a single e-learning module is unlikely sufficient, but did not specify minimum types or frequency of measures. |

---

#### Phrase 3: "to ensure, to their best extent"

**Scope:** Introduces proportionality. An SME with 20 employees is not held to the same standard as a multinational with 50,000. But "best extent" means genuine, documented effort -- not token gestures. The Commission's Q&A confirmed: merely directing staff to user manuals is "generally not considered sufficient."

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Evidence** -- "best extent" can only be demonstrated with documentation of effort proportional to organisational resources |
| **Secondary pillars** | **Policy** -- must define what "best extent" means for the organisation; **Governance** -- must review whether measures are genuinely the organisation's best effort |
| **Maturity threshold** | Implementing (51+): documented needs assessment proportional to size; evidence portfolio; periodic review |
| **Observable evidence** | AI literacy needs assessment document; resource allocation record; periodic review minutes; comparison against Commission's Living Repository benchmarks |
| **Ambiguity** | "Best extent" is the most significant interpretive challenge. It will be defined through enforcement practice. Organisations should benchmark against the 40+ practices in the Commission's Living Repository. A documented gap between available resources and deployed effort creates regulatory risk. |

---

#### Phrase 4: "a sufficient level of AI literacy"

**Scope:** "Sufficient" is context-dependent. The Commission clarified that staff should understand: (a) what AI is, (b) how it works at a conceptual level, (c) which AI systems are in use in their organisation, and (d) the associated opportunities and risks. Depth varies by role.

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Awareness** -- this is the core demand: people must understand AI systems they interact with |
| **Secondary pillar** | **Training** -- literacy is built through structured competence programmes, not osmosis |
| **Maturity threshold** | Implementing (51+): role-differentiated literacy standards defined and delivered |
| **Observable evidence** | Role-based competence matrix; training curricula mapped to roles; competence verification results (scenario-based assessments preferred over quizzes) |
| **Ambiguity** | "Sufficient" is not quantified. The standard is relative to context (see Phrase 6). A data scientist needs different literacy than a receptionist. The absence of a defined curriculum is both a flexibility and a risk -- organisations must make defensible choices about depth. |

---

#### Phrase 5: "of their staff and other persons dealing with the operation and use of AI systems on their behalf"

**Scope:** Extends beyond employees to contractors, consultants, temporary workers, outsourced service providers -- anyone who interacts with AI systems on the organisation's behalf. An organisation cannot satisfy Article 4 by training employees while leaving outsourced operations unaddressed.

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Training** -- programmes must reach all persons, not just employees |
| **Secondary pillars** | **Policy** -- contractual obligations for third parties must address AI literacy; **Tools** -- inventory must track who has access, including external persons |
| **Maturity threshold** | Implementing (51+): training extended to contractors; contractual AI literacy clauses in vendor/outsourcing agreements |
| **Observable evidence** | Contractor onboarding includes AI literacy training; outsourcing contracts include AI competence requirements; third-party access logs cross-referenced with training records |
| **Ambiguity** | The extent of obligation for outsourced providers is unclear. Must the deployer train the provider's staff, or merely require the provider to train its own? The Commission Q&A suggests the deployer must "ensure" literacy, which implies verification, not merely delegation. |

---

#### Phrase 6: "taking into account their technical knowledge, experience, education and training"

**Scope:** Literacy measures must be calibrated to individual characteristics. A legal professional with 20 years' experience needs different training than a recent graduate. A professional with an engineering background needs different training than one with a humanities background. One-size-fits-all training is explicitly insufficient.

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Training** -- programmes must be differentiated based on participant profiles |
| **Secondary pillar** | **Awareness** -- assessment of current literacy baseline required before training design |
| **Maturity threshold** | Implementing (51+): baseline assessment conducted; training differentiated by at least role/seniority level |
| **Observable evidence** | Pre-training diagnostic assessment; differentiated learning paths (e.g., executive track, practitioner track, technical track); participant profile records |
| **Ambiguity** | The granularity of differentiation is unspecified. Must each individual have a personalised programme, or is role-based differentiation sufficient? Practical interpretation: role-based with provision for individual circumstances is likely sufficient at the Implementing level. Full personalisation would be Optimising. |

---

#### Phrase 7: "the context in which the AI systems are to be used, and considering the persons or groups of persons on whom the AI systems are to be used"

**Scope:** This is the provision that makes one-size-fits-all training legally insufficient. Two requirements: (a) context of use -- a customer-facing AI chatbot requires different literacy than an internal analytics tool; (b) impact on affected persons -- an AI system making decisions about employment requires different literacy than one optimising warehouse logistics. The training must match the stakes.

| Mapping | Detail |
|---------|--------|
| **Primary pillar** | **Awareness** -- understanding of context-specific risks and impacts |
| **Secondary pillars** | **Policy** -- policies must reflect context-specific requirements; **Governance** -- oversight must account for impact on affected persons; **Tools** -- AI inventory must classify systems by context and impact |
| **Maturity threshold** | Implementing (51+): AI systems classified by use context and impact level; training content reflects specific use cases and affected populations |
| **Observable evidence** | AI system risk classification (by use context); impact assessments for systems affecting individuals; context-specific training modules (e.g., "AI in hiring" for HR, "AI in legal research" for legal); records of how affected person considerations influenced literacy programme design |
| **Ambiguity** | "Considering the persons or groups of persons on whom the AI systems are to be used" creates a proportionality gradient. AI systems that affect vulnerable populations (welfare recipients, job applicants, patients) demand higher literacy standards than those affecting internal operations. The boundary between "moderate" and "high" impact is left to organisational judgment and will be refined through enforcement. |

---

### 2.2 Summary Mapping Matrix

| Article 4 Element | Awareness | Policy | Training | Tools | Evidence | Governance |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Providers and deployers | | | | **P** | | S |
| Shall take measures | | | | | S | **P** |
| To their best extent | | S | | | **P** | S |
| Sufficient level of AI literacy | **P** | | S | | | |
| Staff and other persons | | S | **P** | S | | |
| Technical knowledge, experience... | S | | **P** | | | |
| Context of use + affected persons | **P** | S | | S | | S |

**P** = Primary pillar, **S** = Secondary pillar

**Key finding:** Every pillar is engaged by at least two operative elements. No pillar is redundant with respect to Article 4. The heaviest burden falls on **Awareness** (2 primary), **Training** (2 primary), **Evidence** (1 primary, appears as enabling factor throughout), and **Governance** (1 primary, appears as enabling factor throughout).

---

## 3. GDPR Intersection Mapping

Article 4 of the AI Act does not exist in a regulatory vacuum. Most organisations deploying AI systems are already subject to GDPR. The intersection creates compounding obligations where a single AI deployment may trigger requirements under both regulations simultaneously.

### 3.1 GDPR Article 5(1)(f) -- Integrity and Confidentiality (Security)

> Personal data shall be processed in a manner that ensures appropriate security... including protection against unauthorised or unlawful processing and against accidental loss, destruction or damage.

| Intersection | Detail |
|---|---|
| **AI Act Art. 4 link** | Staff who handle AI systems processing personal data must understand data security requirements. AI literacy includes knowing what data the AI system accesses, how it is processed, and what security measures apply. |
| **Twin Ladder pillars** | **Awareness** (understanding data flows), **Policy** (AI use policy must address data security), **Tools** (AI tool assessment must include security review) |
| **Maturity requirement** | Implementing (51+): AI literacy programme includes data security module; staff understand data flows in AI systems they use |
| **Compliance risk** | An AI literacy programme that ignores data security creates dual non-compliance: Art. 4 failure (insufficient literacy) and Art. 5(1)(f) failure (insufficient security awareness) |

### 3.2 GDPR Article 22 -- Automated Individual Decision-Making

> The data subject shall have the right not to be subject to a decision based solely on automated processing, including profiling, which produces legal effects concerning him or her or similarly significantly affects him or her.

| Intersection | Detail |
|---|---|
| **AI Act Art. 4 link** | Staff operating AI systems that make or inform decisions about individuals must understand Article 22 rights. This is directly linked to Art. 4's requirement to consider "persons or groups of persons on whom the AI systems are to be used." |
| **Twin Ladder pillars** | **Awareness** (understanding automated decision-making rights), **Training** (specific module on GDPR Art. 22 for relevant roles), **Governance** (oversight of automated decision processes) |
| **Maturity requirement** | Implementing (51+): HR, credit, insurance, and customer service staff trained on Art. 22 implications; human review process documented for automated decisions |
| **Compliance risk** | This is the highest-risk intersection. An employee who does not understand Art. 22 rights may allow AI to make decisions that require human intervention, creating simultaneous AI Act (Art. 4 literacy failure) and GDPR (Art. 22 rights violation) exposure |

### 3.3 GDPR Article 25 -- Data Protection by Design and by Default

> The controller shall implement appropriate technical and organisational measures for ensuring that, by default, only personal data which are necessary for each specific purpose of the processing are processed.

| Intersection | Detail |
|---|---|
| **AI Act Art. 4 link** | AI literacy must include understanding data minimisation in AI contexts. Staff must know not to feed unnecessary personal data into AI systems. This is a literacy requirement (knowing what data is appropriate) and a policy requirement (defining acceptable data inputs). |
| **Twin Ladder pillars** | **Policy** (data protection by design in AI use policy), **Training** (data minimisation training for AI tool users), **Tools** (AI tool configurations enforce data protection defaults) |
| **Maturity requirement** | Implementing (51+): AI use policy addresses data minimisation; training includes practical guidance on data inputs; tools configured with privacy defaults |
| **Compliance risk** | Employees who input excessive personal data into AI systems (e.g., pasting full client files into ChatGPT) violate Art. 25 while simultaneously demonstrating the Art. 4 literacy gap |

### 3.4 GDPR Article 32 -- Security of Processing

> The controller and the processor shall implement appropriate technical and organisational measures to ensure a level of security appropriate to the risk.

| Intersection | Detail |
|---|---|
| **AI Act Art. 4 link** | Organisational measures under Art. 32 include staff competence. An employee who does not understand the security implications of AI tool usage is itself a security gap. AI literacy that excludes security considerations fails both regulations. |
| **Twin Ladder pillars** | **Tools** (security assessment of AI tools), **Policy** (AI security policies), **Training** (security-specific AI training) |
| **Maturity requirement** | Implementing (51+): AI tools undergo security assessment; staff trained on security implications of AI use; incident response procedures address AI-specific scenarios |
| **Compliance risk** | Shadow AI (unapproved tools) is both a security risk (Art. 32) and a literacy gap indicator (Art. 4) |

### 3.5 GDPR Article 35 -- Data Protection Impact Assessment (DPIA)

> Where a type of processing... is likely to result in a high risk to the rights and freedoms of natural persons, the controller shall, prior to the processing, carry out an assessment of the impact.

| Intersection | Detail |
|---|---|
| **AI Act Art. 4 link** | DPIAs are mandatory for many AI deployments (especially those involving profiling, systematic monitoring, or large-scale processing). The persons conducting and reviewing DPIAs need AI literacy to assess AI-specific risks accurately. Art. 4 literacy is a prerequisite for meaningful DPIA completion. |
| **Twin Ladder pillars** | **Evidence** (DPIA documentation), **Governance** (DPIA review process), **Awareness** (understanding when DPIAs are triggered), **Tools** (AI inventory feeds DPIA requirements) |
| **Maturity requirement** | Implementing (51+): AI deployments assessed for DPIA requirement; DPIAs conducted with AI-literate reviewers; DPIA registry maintained |
| **Compliance risk** | A DPIA conducted by staff who lack AI literacy is a deficient DPIA. This creates triple exposure: Art. 35 (deficient DPIA), Art. 4 (insufficient literacy), and the underlying high-risk AI deployment violation |

### 3.6 German National Implementation

#### BDSG (Federal Data Protection Act)

The BDSG supplements GDPR in Germany with sector-specific provisions. Key intersections with AI Act Article 4:

- **Section 26 BDSG** (Employee data processing): AI systems processing employee data require specific justification. Literacy obligations extend to understanding employee data protection rights in AI contexts.
- **Section 37 BDSG** (DPO requirements): Data Protection Officers must have AI literacy to fulfil their advisory and monitoring role effectively.

#### Betriebsverfassungsgesetz (BetrVG) Section 87 -- Works Council Co-Determination Rights

| Intersection | Detail |
|---|---|
| **Section 87(1)(6) BetrVG** | Works councils have co-determination rights regarding "the introduction and use of technical devices designed to monitor the behaviour or performance of employees." AI systems that analyse employee behaviour, productivity, or performance fall squarely within this provision. |
| **AI Act Art. 4 link** | Works council members must themselves have sufficient AI literacy to exercise their co-determination rights meaningfully. An organisation that deploys AI monitoring tools without ensuring works council AI literacy faces dual exposure: AI Act Art. 4 (insufficient literacy for persons dealing with AI use) and BetrVG Section 87 (inadequate co-determination process). |
| **Twin Ladder pillars** | **Governance** (works council involvement in AI governance), **Training** (works council members included in AI literacy programmes), **Policy** (AI policy co-determined with works council) |
| **Practical implication** | In Germany, the "staff and other persons" obligation under Art. 4 extends to works council representatives, even though they may not directly "operate" AI systems. Their oversight role requires literacy to be meaningful. This is a distinctive German requirement with no exact parallel in other Member States. |

### 3.7 Intersection Summary Table

| GDPR Provision | AI Act Art. 4 Element(s) | Twin Ladder Pillars | Risk Level |
|---|---|---|---|
| Art. 5(1)(f) -- Security | Sufficient literacy; context of use | Awareness, Policy, Tools | Medium |
| Art. 22 -- Automated decisions | Affected persons; context of use | Awareness, Training, Governance | **High** |
| Art. 25 -- Privacy by design | Sufficient literacy; context of use | Policy, Training, Tools | Medium |
| Art. 32 -- Security measures | Shall take measures; best extent | Tools, Policy, Training | Medium |
| Art. 35 -- DPIA | Context; affected persons; best extent | Evidence, Governance, Awareness, Tools | **High** |
| BetrVG Section 87 (Germany) | Staff and other persons; governance | Governance, Training, Policy | **High** (Germany only) |

---

## 4. Gap Analysis

### 4.1 Requirements Adequately Covered

The six-pillar model covers the vast majority of Article 4's requirements:

| Article 4 Requirement | Coverage Assessment |
|---|---|
| Organisational awareness of AI systems | **Fully covered** -- Awareness + Tools pillars |
| Formal AI use policies | **Fully covered** -- Policy pillar |
| Structured training programmes | **Fully covered** -- Training pillar |
| AI systems inventory and oversight | **Fully covered** -- Tools pillar |
| Documentation and compliance evidence | **Fully covered** -- Evidence pillar |
| Accountability and oversight structures | **Fully covered** -- Governance pillar |
| Role-based differentiation | **Covered** -- Training pillar (scoring criteria differentiate by role) |
| Ongoing maintenance obligation | **Covered** -- Training pillar (curriculum maintenance question TR-03) |

### 4.2 Gaps and Weaknesses Identified

#### Gap 1: Affected Persons Consideration (MODERATE)

**Article 4 requirement:** "considering the persons or groups of persons on whom the AI systems are to be used"

**Current coverage:** The model addresses organisational stakeholders (staff, contractors) but does not explicitly assess whether literacy programmes account for the impact on affected third parties -- customers, employees, applicants, patients, citizens.

**Affected pillars:** Awareness, Policy

**Recommendation:** Add an assessment question to the Awareness pillar:
> "Does the organisation's AI literacy programme address the impact of AI systems on persons affected by AI-driven decisions (customers, applicants, employees, etc.)?"

And to the Policy pillar:
> "Does the AI use policy differentiate requirements based on the vulnerability or rights sensitivity of affected persons?"

#### Gap 2: Third-Party / Contractor Literacy Verification (MODERATE)

**Article 4 requirement:** "other persons dealing with the operation and use of AI systems on their behalf"

**Current coverage:** The Training pillar addresses employee training but does not explicitly assess whether contractors, outsourced providers, and temporary workers are included in AI literacy measures.

**Affected pillars:** Training, Policy

**Recommendation:** Add an assessment question to the Training pillar:
> "Are contractors, temporary workers, and outsourced service providers included in AI literacy requirements?"

And a policy question:
> "Do outsourcing and vendor contracts include AI competence requirements?"

#### Gap 3: Proportionality Documentation (MINOR)

**Article 4 requirement:** "to their best extent"

**Current coverage:** The Evidence pillar assesses audit readiness and documentation but does not specifically address documentation of proportionality reasoning -- the record of why the organisation's measures are its "best extent" given its resources, size, and AI deployment profile.

**Affected pillars:** Evidence, Governance

**Recommendation:** Add to Evidence pillar:
> "Does the organisation document its proportionality reasoning -- why its AI literacy measures represent its best effort given available resources?"

#### Gap 4: Data Protection Integration (MINOR -- addressed by pillar expansion)

**Article 4 requirement:** Intersection with GDPR (not explicit in Art. 4 text, but implicit in "context of use" and affected persons provisions)

**Current coverage:** The Policy pillar is being expanded to "Policy & Data Protection," which would address this gap. The Tools pillar includes a data protection question (TO-03). The gap is in the Awareness pillar: no assessment question specifically addresses whether staff understand GDPR implications of AI tool use.

**Affected pillars:** Awareness, Policy (expanding)

**Recommendation:** As part of the Policy pillar expansion to "Policy & Data Protection," ensure assessment questions address:
- GDPR awareness in AI contexts (data minimisation, Art. 22 rights, DPIA triggers)
- Data protection impact assessment integration with AI governance

#### Gap 5: Cross-Border and Multi-Jurisdictional Variation (MINOR)

**Article 4 requirement:** Not explicit, but enforcement will vary by Member State given national competent authority discretion.

**Current coverage:** The model is jurisdiction-neutral. This is both a strength (universal applicability) and a weakness (does not flag jurisdiction-specific requirements like German works council obligations).

**Affected pillars:** Governance, Policy

**Recommendation:** This is an implementation-level concern rather than a structural gap in the pillar model. Consider adding a guidance note to the Governance pillar:
> "For organisations operating in multiple EU jurisdictions, governance structures should account for national implementation variations (e.g., German works council co-determination rights under BetrVG Section 87)."

### 4.3 Gap Severity Summary

| Gap | Severity | Action Required |
|---|---|---|
| Affected persons consideration | Moderate | Add 2 assessment questions (Awareness + Policy) |
| Third-party literacy | Moderate | Add 2 assessment questions (Training + Policy) |
| Proportionality documentation | Minor | Add 1 assessment question (Evidence) |
| Data protection integration | Minor | Addressed by Policy pillar expansion |
| Cross-border variation | Minor | Guidance note; no structural change |

**Overall assessment:** The six-pillar model provides **strong structural coverage** of Article 4 requirements. The identified gaps are addressable through question-bank additions (4-5 new questions) and do not require pillar restructuring. The planned expansion of "Policy" to "Policy & Data Protection" addresses the most significant intersection concern.

---

## 5. Compliance Floor Justification

### 5.1 Why the Compliance Floor Is Set at Approximately 50-55

The Twin Ladder Assessment uses a 0-100 scale across four maturity levels:
- **Exploring (0-25):** Ad-hoc, informal, no structured approach
- **Developing (26-50):** Awareness exists, initial structures emerging, incomplete coverage
- **Implementing (51-75):** Structured programmes in place, documented, covering key requirements
- **Optimising (76-100):** Continuous improvement, validated frameworks, proactive adaptation

The Article 4 compliance floor at approximately 50-55 corresponds to the **transition from Developing to Implementing**. This threshold is justified by the following analysis:

### 5.2 What Scores Below 50 Look Like (Non-Compliant)

An organisation scoring 25-50 (Developing) typically exhibits:

| Pillar | Developing (25-50) | Why Insufficient for Art. 4 |
|---|---|---|
| **Awareness** | Leadership aware of AI obligations; most staff have vague understanding; cannot articulate specific risks | Art. 4 requires "sufficient" literacy -- vague understanding fails the "sufficient" standard |
| **Policy** | AI use policy drafted but not enforced; informal guidance on acceptable use | Art. 4 requires "measures" -- an unenforced draft is not a measure |
| **Training** | Generic training available; self-directed learning; no role differentiation | Commission Q&A: generic training insufficient; role differentiation required |
| **Tools** | Partial AI inventory; some tools assessed; human review optional | Cannot demonstrate literacy for systems you don't know exist |
| **Evidence** | Some records exist; no systematic collection; could not survive audit | "Best extent" requires demonstrable effort; informal records fail this |
| **Governance** | Informal responsibility; no dedicated oversight; ad-hoc reviews | Art. 4 "measures" imply intentional governance, not ad-hoc responses |

**Assessment:** An organisation at 25-50 has *awareness* of its obligations but has not operationalised them. This corresponds to the early stages of compliance programmes that regulators routinely find insufficient -- analogous to a GDPR programme that has a privacy policy on the website but no ROPA, no DPIA process, and no trained staff.

### 5.3 What Scores at 51-55 Look Like (Minimum Compliance)

An organisation scoring 51-55 (early Implementing) typically exhibits:

| Pillar | Implementing (51-55) | Art. 4 Compliance Indicator |
|---|---|---|
| **Awareness** | Staff can name AI systems they use; understand key risks; organisation-wide briefing completed | Satisfies "sufficient level" for basic contexts; may need deepening for high-risk uses |
| **Policy** | Active AI use policy; acceptable/prohibited uses defined; enforcement mechanisms exist | Satisfies "shall take measures" -- policy is a documented, enforceable measure |
| **Training** | Role-specific training programme exists; delivered to key teams; not yet comprehensive | Satisfies "taking into account technical knowledge, experience" -- differentiation has begun |
| **Tools** | Complete AI systems inventory; DPIA completed for high-risk tools; human review required for consequential decisions | Satisfies scope awareness requirement; systems are known and classified |
| **Evidence** | Basic evidence portfolio; training records centralised; could demonstrate effort under audit | Satisfies "best extent" -- documented effort exists, even if not exhaustive |
| **Governance** | Named responsible individual; ethics checklist in use; periodic regulatory monitoring | Satisfies "shall take measures" governance dimension -- intentional oversight exists |

**Assessment:** An organisation at 51-55 has a **functional, documented, and enforced** compliance programme. It is not optimal, comprehensive, or fully mature. But it demonstrates the genuine, structured effort that "to their best extent" requires for a mid-sized organisation. It could survive a regulatory inquiry -- not with flying colours, but without penalty.

### 5.4 The Proportionality Rationale

The 50-55 floor is not a universal standard. It reflects proportionality:

- **A 200-person company** scoring 55 across all pillars demonstrates a structured programme appropriate to its resources. This is likely "best extent" for that organisation.
- **A 50,000-person multinational** scoring 55 may NOT satisfy "best extent" because its resources and AI deployment complexity demand more. The same multinational may need 65-70 to demonstrate proportional effort.
- **A 20-person firm** scoring 45-50 may satisfy "best extent" if its AI use is limited and documented, and it has taken genuine measures proportional to its resources.

The 50-55 floor is calibrated to a **typical mid-sized European organisation** (100-500 employees, moderate AI deployment, multiple departments using AI). Smaller organisations may achieve compliance at slightly lower absolute scores; larger organisations may need higher scores.

### 5.5 Pillar-by-Pillar Minimum Indicators at the Compliance Floor

| Pillar | Minimum Indicator at ~50-55 | Art. 4 Phrase Satisfied |
|---|---|---|
| **Awareness** | All staff briefed on AI systems in use and key risks; key teams receive context-specific training | "Sufficient level of AI literacy" |
| **Policy** | Written, enforced AI use policy with defined acceptable/prohibited uses | "Shall take measures" |
| **Training** | Role-differentiated training programme delivered to all AI-interacting staff (including contractors) | "Taking into account technical knowledge, experience, education and training" |
| **Tools** | Complete AI systems inventory with risk classification; human oversight for consequential decisions | "Providers and deployers of AI systems" (scope awareness) |
| **Evidence** | Centralised training records; needs assessment document; evidence portfolio assembled | "To their best extent" (demonstrable effort) |
| **Governance** | Named AI governance owner; periodic review cycle; ethics considerations documented | "Shall take measures" (intentional governance) |

### 5.6 Why Not Lower? Why Not Higher?

**Why not 40 (mid-Developing)?**
At 40, an organisation has awareness and initial structures but lacks enforcement, comprehensive coverage, and documentation sufficient to demonstrate "best extent." The Commission Q&A's explicit rejection of user-manual-only approaches and generic training means that Developing-level measures are insufficient as a matter of regulatory guidance.

**Why not 60 (mid-Implementing)?**
At 60, an organisation has a strong, comprehensive programme. This is clearly compliant. But requiring 60 as the floor would mean that organisations with genuine, structured programmes that have not yet achieved full comprehensiveness (e.g., training delivered to 80% of relevant staff, not yet 100%) would be classified as non-compliant. This contradicts the proportionality principle -- "best extent" acknowledges that compliance is a process, not a binary state.

**The 50-55 threshold thus represents:**
- The point at which an organisation has moved from *awareness* to *action*
- The point at which measures are *documented* and *enforced*, not merely planned
- The point at which role differentiation has *begun*, even if not perfected
- The point at which regulatory inquiry would find *evidence of genuine effort*
- The point below which a regulator would likely find *insufficient measures*

---

## 6. Sources

### Primary Legal Sources

1. **Regulation (EU) 2024/1689** -- EU Artificial Intelligence Act, Article 4 (AI Literacy).
   https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689

2. **Recital 20, Regulation (EU) 2024/1689** -- Legislative intent for AI literacy provisions.

3. **European Commission: AI Literacy -- Questions & Answers (May 2025).**
   https://digital-strategy.ec.europa.eu/en/faqs/ai-literacy-questions-answers

4. **European Commission: Living Repository of AI Literacy Practices (2025).**
   https://digital-strategy.ec.europa.eu/en/library/living-repository-foster-learning-and-exchange-ai-literacy

5. **AI Act Service Desk -- Article 4: AI Literacy.**
   https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-4

6. **Regulation (EU) 2016/679** -- General Data Protection Regulation (GDPR), Articles 5, 22, 25, 32, 35.

7. **Bundesdatenschutzgesetz (BDSG)** -- German Federal Data Protection Act.

8. **Betriebsverfassungsgesetz (BetrVG)** -- German Works Constitution Act, Section 87(1)(6).

### Secondary Analytical Sources

9. **Article 4: AI Literacy -- Analysis and Commentary.** Future of Life Institute.
   https://artificialintelligenceact.eu/article/4/

10. **Travers Smith: The EU AI Act's AI Literacy Requirement -- Key Considerations.**
    https://www.traverssmith.com/knowledge/knowledge-container/the-eu-ai-acts-ai-literacy-requirement-key-considerations/

11. **Ropes & Gray: Five Takeaways from the EU Commission's AI Literacy Q&As.**
    https://www.ropesgray.com/en/insights/viewpoints/102kbn5/five-takeaways-from-the-eu-commissions-ai-literacy-qas

12. **Covington: European Commission Provides Guidance on AI Literacy Requirement.**
    https://www.insideprivacy.com/artificial-intelligence/european-commission-provides-guidance-on-ai-literacy-requirement-under-the-eu-ai-act/

13. **Hunton Andrews Kurth: European Commission Publishes Q&A on AI Literacy.**
    https://www.hunton.com/privacy-and-information-security-law/european-commission-publishes-q-a-on-ai-literacy

14. **DLA Piper: Latest Wave of Obligations Under the EU AI Act (August 2025).**
    https://www.dlapiper.com/en-us/insights/publications/2025/08/latest-wave-of-obligations-under-the-eu-ai-act-take-effect

15. **DLA Piper: GDPR Fines and Data Breach Survey (7th Edition, January 2025).**
    https://www.dlapiper.com/en-us/insights/publications/2025/01/dla-piper-gdpr-fines-and-data-breach-survey-2025

### Twin Ladder Framework Sources

16. **Twin Ladder Methodology v1.0.0** -- framework-version.json; CC BY-SA 4.0.

17. **Question Bank** -- webapp/src/lib/data/question-bank.ts (18 assessment questions across 6 pillars).

18. **"EU AI Act Article 4: The Regulation That Asks Whether Your People Can Handle What You Have Given Them"** -- TwinLadder Research Capstone, February 2026.

19. **"Comfort Over Code: A Workflow-Based Framework for AI Literacy in Professional Practice"** -- TwinLadder Research, March 2026.

---

*This document is a reference artefact for the Twin Ladder Assessment Maturity Model. It should be reviewed and updated as Commission guidance, enforcement practice, and harmonised standards develop. Next review recommended: August 2026 (one year after supervision rules took effect).*
