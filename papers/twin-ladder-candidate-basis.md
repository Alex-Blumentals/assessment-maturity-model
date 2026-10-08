# A Candidate Basis for an AI-Literacy Competence Standard: The Twin Ladder Methodology

### An interest-declared contribution paper, companion to *"The Unmeasured Obligation"* (gap analysis)

**A StandICT.eu 2029 Fellowship contribution toward CEN-CENELEC JTC 21**
**Version 4.2 (draft) · October 2026 · Post-Digital-Omnibus**

> **Declared interest.** This paper is written by the developer of the Twin Ladder methodology (operated through Idea Jet Lab SIA, Latvia) and is an *interested contribution*. It is deliberately separated from the neutral gap analysis it accompanies so that the analysis can be evaluated on its own terms. Nothing here should be read as a claim that Twin Ladder is the only, or the necessary, basis for a European deliverable — it is offered as one candidate input against the requirements the gap analysis established. The methodology is published under CC BY-SA 4.0, so any part of it may be adopted, adapted, or discarded by the committee without licensing constraint.

> **Published openly under CC BY-SA 4.0 · October 2026 (an interest-declared contribution, open for comment).** An interest-declared contribution paper, companion to the neutral gap analysis *"The Unmeasured Obligation."* It maps one open methodology (Twin Ladder) against the properties that analysis identifies, and offers it as a candidate input — not as the answer. The regulatory position is current to the **Digital Omnibus on AI (Regulation (EU) 2026/1744)**, in force 27 July 2026: Article 4 is now a best-efforts duty to *support the development of* AI literacy (with no requirement to guarantee any specific individual level), and Article 26(2) — competent human oversight of high-risk systems — is unchanged.

**Open-access home.** This paper and its companion are published under CC BY-SA 4.0 at **github.com/Alex-Blumentals/assessment-maturity-model/tree/main/papers** — PDFs in the dated release `fellowship-papers-2026-10`.
>
> **Known and unfinished — you need not report these:** the pillar weightings are not externally validated; no inter-rater-reliability or construct-validity study has been done; the proportionality cost model is proposed, not standardised (the figures are indicative); terminology is alignable to ISO/IEC 22989 but not yet formally mapped.
>
> **v4.2 (October 2026) clarifies §2 in response to committee review:** each pillar is now marked for *requirement vs enabling* and *individual competence vs organisational context*, and the Article 14(4) oversight competences are signposted to the pillars that carry them. The substance of the methodology is unchanged.

---

## 1. Purpose

The companion gap analysis (*"The Unmeasured Obligation"*) establishes, product-blind, that no harmonised, Article-4-native, deployer-workforce competence-measurement standard exists, and sets out in its §7 the *properties* such a standard should have. This paper does one thing: it maps an existing open methodology — Twin Ladder — against those properties, so the committee can judge whether it is a useful starting point, a partial input, or not relevant. The burden of proof is on the methodology, not on the reader.

## 2. The seven pillars and the Article 4 mapping

**This section defines the competences.** The seven pillars below *are* the competence areas the instrument measures; §6 gives worked, role-specific descriptors of what each looks like in practice, and the full level definitions are in the published Twin Ladder Standard (v1.1, CC BY-SA 4.0). Two distinctions run through the list and are marked on every pillar, because a first read can otherwise miss them:

- **Requirement vs enabling.** The mapping table further down shows which operative *elements* of Article 4 engage each pillar (primary / secondary). That is not the same as which pillars carry the article's *substantive competence* duty. On that reading only two pillars are competence **requirements** — **Deployment Competence** (the "AI literacy … technical knowledge" itself) and **Training & Development** (its "development"). The others are **enabling**: the organisational conditions under which literacy is built and evidenced. The seventh, AI Decision Boundaries, is not an Article 4 pillar at all — it anchors to **Article 26(2)** high-risk oversight.
- **Individual competence vs organisational context.** The instrument measures on two levels and keeps them separate. Two pillars — **Deployment Competence** and **AI Decision Boundaries** — measure an *individual's* competence (what a named person can do). The other five describe the *organisational context* in which that competence is built, exercised and evidenced. Holding the measurand on the individual for those two is what gives the instrument its Article 4 / Article 26(2) anchor; the organisational pillars are the diligence record around it (§7).

The assessment is also **tiered and risk-based, not uniform**: depth is concentrated where Article 26(2) bites and is lightest for incidental exposure (§4). The pillars are a coverage map derived from the regulation's operative text, not a generic maturity taxonomy.

**The seven pillars** — each marked *requirement / enabling* and *individual competence / organisational context*:

1. **Deployment Competence** — *requirement · individual competence.* Understanding the AI systems one interacts with: what they do, where their limits lie, and the risks they carry in a given context. This pillar carries the individual oversight competences of **Article 14(4)** — correctly interpreting output, staying aware of automation bias, and recognising when a result is wrong — worked out for a named role in §6.
2. **Policy & Data Protection** — *enabling · organisational context.* The organisation's rules for AI use, including the GDPR intersection that most AI deployment triggers.
3. **Training & Development** — *requirement · organisational measure, individual uptake.* Structured, role-differentiated competence-building that reaches staff and the third parties who operate AI on the organisation's behalf.
4. **Technical Infrastructure (Tools)** — *enabling · organisational context.* Knowing which AI systems the organisation actually operates: inventory, classification, and who has access.
5. **Evidence & Documentation** — *enabling · organisational context.* The record that demonstrates measures were taken "to the best extent," proportionate to the organisation's resources.
6. **Ethical & Responsible Use (Governance)** — *enabling · organisational context.* The accountability structures that initiate, fund, oversee and periodically review AI-literacy measures.
7. **AI Decision Boundaries (Authority)** — *Article 26(2) · individual competence + organisational authority.* Who is authorised to act on, override, or stop an AI-influenced decision, and whether they can: the competence-and-authority pairing that Article 26(2) and Article 14(4) require for human oversight of high-risk systems. This is where Article 14(4)'s "decide not to use, override, or halt" is measured as a competence, not only provided for as a control.

**Mapping Article 4 to the pillars.** Article 4 is a single sentence with seven operative elements. Each maps to a primary pillar (**P**) and, where relevant, secondary pillars (**S**):

| Article 4 operative element | Deployment Competence | Policy | Training | Tools | Evidence | Governance |
|---|:--:|:--:|:--:|:--:|:--:|:--:|
| "Providers and deployers of AI systems" | | | | **P** | | S |
| "shall take measures" | | | | | S | **P** |
| "to support the development of" | | S | | | **P** | S |
| "AI literacy" | **P** | | S | | | |
| "of their staff and other persons… on their behalf" | | S | **P** | S | | |
| "technical knowledge, experience, education and training" | S | | **P** | | | |
| "the context… and the persons on whom [AI] is used" | **P** | S | | S | | S |

*Every pillar is engaged by at least two operative elements; none is redundant to Article 4. The heaviest load falls on Deployment Competence and Training (two primary each), with Evidence and Governance recurring as enabling factors throughout.*

**The seventh pillar and the high-risk anchor.** Article 4 does not, on its own, reach the seventh pillar: authority over AI-influenced decisions is a competence Article 4's literacy duty presupposes but does not itself govern. It is **Article 26(2)** — a competent natural person assigned to oversee a high-risk system — read with **Article 14(4)** (the capability to interpret output and to decide not to use, override, or halt) and **Article 17(1)(m)** (the accountability framework setting out staff responsibilities), that gives AI Decision Boundaries its legal anchor. This is why the tiered model in §4 places oversight-critical roles (T1) at the top: the seventh pillar is where a best-efforts literacy duty meets a hard competence duty.

> **Provenance.** The operative elements above are Article 4 **as amended by the Digital Omnibus (Regulation (EU) 2026/1744)**: providers and deployers "shall take measures to support the development of AI literacy," and the amended article expressly does not require guaranteeing any specific level of AI literacy for any individual. The pillar mapping is drawn from the Twin Ladder Standard's published Article 4 analysis (v1.0, CC BY-SA 4.0); the amendment softens the duty's *force* (best-efforts) without changing *which competences* the article engages, so the mapping stands.

## 3. Mapping to the required properties

Taking the §7 properties from the gap analysis in turn:

| Required property (gap analysis §7) | Twin Ladder position | Known limitation |
|---|---|---|
| Competence-specific, deployer-workforce-scoped | Central design purpose: measures literacy of staff who use/oversee AI, via seven assessment pillars (defined in §2) | Pillar weightings not yet externally validated |
| Article-4- & 26(2)-native | Line-by-line mapping of Article 4's requirements to pillars (published), updated to the amended text; Article 26(2) high-risk oversight-competence duty anchors the top tier | Mapped to Article 4 as amended by Regulation (EU) 2026/1744 (best-efforts support duty; no guaranteed individual level); Article 26(2) unchanged |
| Individual & workflow-anchored, but proportionate | Assesses individuals; three layers (strategic/tactical/operational); tiered cost model (§4) | Proportionality model is proposed, not yet standardised; cost figures are indicative |
| Comparable | Four maturity levels + defined threshold; rating discipline adapted from ISO/IEC 33020, with ISO/IEC 33002 assessment rigour (§5); common protocol | No inter-rater reliability or construct-validity study yet |
| Terminologically aligned | Alignable to ISO/IEC 22989 vocabulary | Formal term-by-term mapping not yet done |
| Openly adoptable | CC BY-SA 4.0; free to adopt/adapt | — |

The limitations column is stated deliberately. A contribution that hides its gaps wastes committee time; one that names them invites the collaboration that a standardisation process is for.

## 4. The proportionality problem, addressed

The gap analysis notes that mandating full individual assessment of every member of staff could itself be disproportionate — and Article 4, as amended by the Digital Omnibus (Regulation (EU) 2026/1744, in force 27 July 2026), is now a best-efforts duty: providers and deployers must *take measures to support the development of* AI literacy, and the amended article expressly does not require them to guarantee any specific level of AI literacy in any individual. That qualification cuts toward measurement, not against it — a duty discharged by showing the *measures* taken is one a comparable, proportionate assessment is well suited to evidence. The harder-edged competence duty sits at Article 26(2) (competent human oversight of high-risk systems), which the Omnibus left untouched. A credible standard must therefore be **tiered and risk-based**, not uniform — deepest where Article 26(2) bites, lightest for incidental exposure. The proposed model:

| Tier | Who | Assessment depth | Cadence |
|---|---|---|---|
| **T1 — Oversight-critical** | Persons assigned human oversight of high-risk systems (Art. 26(2), read with Art. 14(4)); high-authority decision roles | Full individual, workflow-anchored assessment | On assignment + on material system change |
| **T2 — Operational users** | Staff who use AI outputs in consequential tasks | Role-based assessment + targeted scenario items | Periodic; sample-verified |
| **T3 — General workforce** | Broad staff with incidental AI exposure | Lightweight attestation + baseline literacy check | Baseline + refresh |

This concentrates measurement effort where the AI Act concentrates risk (Article 26(2) oversight of high-risk systems), and uses attestation/sampling for the long tail — the same risk-tiering logic organisations already apply under three-lines-of-defence and model-risk governance. It answers the practitioner objection that individual assessment "doesn't scale": it is not meant to be applied uniformly.

**Indicative effort model.** Tiering only controls cost if the numbers are stated. The figures below are order-of-magnitude planning estimates for a standard to specify and calibrate — not validated norms — offered so an adopting organisation can size the burden before committing:

| Tier | Typical share of AI-touching staff | Assessor effort per head per cycle | Cycle |
|---|---|---|---|
| **T1 — Oversight-critical** | ~1–5% (named oversight/high-authority roles) | ~2–4 assessor-hours (scenario assessment + review) | Annual + on material system change |
| **T2 — Operational users** | ~15–30% | ~0.5–1 assessor-hour, **sample-verified** (assess a statistically-drawn sample, e.g. a confidence-bounded random sample per role-family, rather than every individual) | Periodic (e.g. 12–24 months) |
| **T3 — General workforce** | remainder | Minutes (attestation + baseline check; no individual assessor time) | Baseline + refresh |

For a 5,000-staff firm this concentrates the expensive T1 assessment on perhaps 50–250 named individuals, verifies T2 by sampling rather than census, and clears T3 by attestation — turning "assess everyone individually" (infeasible) into a bounded, auditable programme. A standard should define the T2 sampling frame and confidence level so "sample-verified" is not a hand-wave an auditor can puncture.

**Tier-classification rule (the contested boundary).** The hardest real-world decision is the T2/T3 line — is a role's AI exposure *consequential* or *incidental*? The proposed rule keys the tier to **authority over the AI-influenced decision**, not to frequency of AI use:

- **T2 (consequential)** — the person can, in the normal course, **act on or materially shape an AI-influenced decision affecting a data subject or a regulated outcome without a mandatory independent human check** (e.g. a retail credit officer acting on an AI affordability score; a KYC analyst accepting an AI risk rating).
- **T3 (incidental)** — AI output is advisory-only, and a downstream human control always intervenes before effect.
- **T1** — roles assigned formal human-oversight duties for high-risk systems, by definition (Article 26(2)).

Classifying and maintaining this mapping as systems change is itself a standing task; a standard should require it to be owned and version-controlled — it is a real line item, not a free one.

## 5. The measurement method: the rating discipline

The gap analysis asks for a **comparable** instrument (§7 of that paper) — results comparable across organisations under a common protocol — and this paper's own declared limitation is that Twin Ladder's four maturity levels are not yet backed by an inter-rater-reliability or construct-validity study (§3). The method below addresses comparability by borrowing an established ISO measurement discipline; it does not pretend to have closed the validation gap.

**From ISO/IEC 33020:2019** *(process measurement framework; ISO/IEC JTC 1/SC 7, the SPICE-lineage process-assessment family)* — not its subject matter, but its **rating architecture**:
- an **ordinal level scale** in which each level is defined by attributes, each attribute rated for **degree of achievement on a four-point scale — N / P / L / F (Not / Partially / Largely / Fully achieved)** against explicit indicators with defined bands, then **rolled up** to a level;
- a level counts as reached only when its attributes are achieved and the lower levels fully so — a cumulative rule that makes a level claim specific and checkable rather than an impression.

Applied here: each pillar (§2) is rated N/P/L/F against defined competence indicators at the person's tier (§4), and the ratings roll up to one of the four maturity levels. This is what turns "level 3" from a label into an evidenced, defensible judgment — the property a standard exists to supply.

**From ISO/IEC 33002:2015** *(requirements for performing process assessment)* — the **assessment-validity requirements**: results must be objective, repeatable and representative; the assessment is a documented process (plan → collect → validate → rate → report), run under a competent assessor with declared independence. These requirements are measurand-neutral and map almost directly onto a defensible person-level assessment — the backbone any competence *credential* needs to survive an auditor or a market-surveillance authority.

**The boundary — borrow the structure, not the content.** The 330xx family measures **process capability and maturity**, not individual human competence; its process-attribute model (is a process defined, managed, quantitatively controlled) is process-shaped, and ISO/IEC 33003's scope is process quality characteristics, not persons. Twin Ladder therefore:
- **keeps** the level-plus-achievement-rating discipline and the 33002 assessor-objectivity requirements;
- **replaces** the process-attribute model with a **competence / performance-criteria model** (knowledge → application → autonomous judgment against real AI-use tasks), which is person-shaped;
- **adds** what 330xx does not supply for a person-level claim — **psychometric validity and reliability evidence**, which is precisely the inter-rater-reliability and construct-validity work this paper lists as open (§3).

The relationship is therefore **adoption by analogy, not conformance**: Twin Ladder is not a 330xx assessment and does not claim to be. It takes a recognised, audited measurement discipline off the shelf for the part that fits — the shape of a defensible rating — and is candid that person-level validation is work for a study period. It sits alongside the **ISO/IEC 17024 / 24773** person-certification machinery the gap analysis identifies: 33020 supplies the *rating* discipline, 17024/24773 the *certification* discipline, and neither has yet been applied to AI-literacy competence.

---

## 6. A worked evidentiary artefact

To make the idea concrete, here is what "sufficient competence" looks like for two contrasting roles under the tiered model — the kind of artefact an organisation could show a market-surveillance authority as evidence of "best extent" measures.

**Role A — Model-risk analyst overseeing a credit-scoring model (Tier 1, high-risk Annex III):**
- *Can recognise* when the model is operating outside its validated population (distribution shift) and knows the escalation path.
- *Can interpret* the model's outputs and its stated limitations (Art. 14(4) "correctly interpret"), including proxy-discrimination and automation-bias risks.
- *Can decide* to override or withhold a decision, and knows the governance under which that override is recorded (Art. 14(4) "decide not to use / override").
- *Evidence:* scenario-based assessment at assignment; re-assessed when the model is retrained; logged against the named individual and named system.

**Role B — Claims-handling clerk using an AI triage suggestion (Tier 2/3, consequential but supervised):**
- *Can recognise* that the AI suggestion is advisory and identify obvious failure signals (e.g. a suggestion inconsistent with the case facts).
- *Knows* when and how to refer to a human supervisor rather than accept the suggestion.
- *Evidence:* role-based literacy check plus a short situational-judgment item set; periodic, sample-verified — not a full individual psychometric assessment, which would be disproportionate to the role.

The contrast is the point: the *same standard* produces a deep, individual, workflow-anchored assessment for Role A and a proportionate, lightweight check for Role B. A standard that could not make this distinction would fail either on rigour or on proportionality.

## 7. From individual results to an organisational view

The core of this methodology is individual (§2–§6), and that is deliberate: the gap analysis locates the standardisation gap at the *person* level, and keeping the measurand on the individual is what gives the instrument its Article-4 anchor and distinguishes it from the organisational-maturity models surveyed in that paper (§3.3). This section adds a second, clearly subordinate level — and is explicit about what it is and is not.

**The roll-up.** Individual results under the tiered model (§4) aggregate naturally into an organisational view — not a self-rated maturity score, but a **coverage-and-maintenance picture built from measured individual competence**: whether every named oversight-critical (T1) role is currently held by an assessed, competent person; whether T2 sampling sits within its confidence bound; and whether those conditions *hold over time* as staff rotate and systems change. Because it is an aggregate of measured persons rather than an organisational opinion survey, it stays distinct from an AIRI-style readiness index even where the topics (governance, oversight, infrastructure) overlap.

**Why the time dimension matters — the legal bridge, stated carefully.** Neither Article 4 nor Article 26(2) mandates an organisational competence measure; both are framed on individuals, and this section is *not* offered as a new AI-Act requirement. But both duties are continuous, not one-off:

- Article 4 (as amended) is a duty to support the *development* of AI literacy — ongoing by its wording;
- Article 26(2) requires competent human oversight *throughout* a high-risk system's operation, not only at deployment.

A point-in-time individual assessment evidences the duty on the day; the organisational view evidences that it is **sustained** — that a competent person stays in each oversight-critical seat as people leave and models are retrained. The cadence rules already in §4 ("on material system change," "periodic") are the mechanics of exactly this.

**The governance rationale (not a compliance claim).** The capability most exposed to erosion is the one the Act most depends on: the **human who can recognise when a model is wrong and override it** (Article 14(4)). As routine judgment is automated, an organisation can lose — quietly, and without a line on any risk register — the bench from which that competence is drawn. Treating oversight competence as an organisational asset to be maintained, rather than a box ticked once, is a governance posture, not a legal obligation; the standard supports it by making that asset **measurable and trendable**, not by asserting the AI Act requires it.

**What this is not.** It is not a repositioning of Twin Ladder as an organisational-maturity model, not a presumption of conformity, and not a claim that the AI Act mandates organisational competence measurement. It is a diligence-and-governance layer, subordinate to the individual core, offered because the duties it supports are continuous and the competence they rely on is the kind that decays. *(Like the pillar weightings, any organisational roll-up thresholds are a matter for calibration and validation, not settled here.)*

## 8. What Twin Ladder does *not* claim

- It does not confer a presumption of conformity. Only an OJ-cited harmonised standard under Article 40 does, and that mechanism runs to the high-risk requirements of Chapter III — it does not extend to Article 4 at all. A Twin Ladder result is *evidence of diligence* — of the measures taken under Article 4 as amended, and of competent oversight under Article 26(2) — not a compliance certificate.
- It does not claim external validation it does not have. Inter-rater reliability, construct validity, and the pillar weightings are open research questions — appropriate work for a study period, not settled facts.
- It does not claim to be the necessary basis for a European standard. It is one open, adaptable input.

## 9. Proposed use in the standardisation process

Consistent with the pathway in the gap analysis (§9): this methodology is offered as a candidate input to be considered *if and when* a preliminary study item or new work item on AI-literacy competence measurement is opened through the LVS national mirror committee into JTC 21, in liaison with ISO/IEC JTC 1/SC 42. Its CC BY-SA 4.0 licence means the committee can take the parts that are useful — the tiered proportionality model, the Article 4 mapping, the pillar structure — and leave the rest, with no licensing entanglement.

---

## Sources
*As per the companion gap analysis. The measurement-framework references drawn on in §5 — ISO/IEC 33020:2019, 33002:2015 and 33003:2015 (ISO/IEC JTC 1/SC 7, the SPICE-lineage process-assessment family) — are listed in that paper's §3.6. Twin Ladder methodology and Article 4 mapping published under CC BY-SA 4.0.*
