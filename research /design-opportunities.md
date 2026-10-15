# SellerPilot: Design Opportunities & Research Handoff

## Purpose

Translate the findings from secondary research, competitor analysis, service journey mapping, and problem definition into provisional design opportunities.

These opportunities will guide exploratory UX architecture and prototyping during Milestone 3.

## Provisional Product Direction

Explore a connected missing-delivery resolution experience for buyers and small ecommerce merchants.

The initial scenario involves a buyer reporting that a package is missing even though carrier tracking indicates delivery.

This is a designer-selected scenario, not a validated widespread user problem.

## DO01: Evidence Clarity

**Related research:** E02, E03, FP01, FP02, HMW01.

**Potential user need:** Buyers and merchants may benefit from understanding what the available delivery information does and does not establish.

**Design opportunity:** Explore ways to present carrier tracking, buyer reports, timestamps, and unknown information clearly.

**Possible interaction concepts:**
- Delivery evidence timeline.
- Clearly attributed information sources.
- Visible distinction between reported, confirmed, and unknown information.

**Validation question:** Can users accurately interpret the information without assuming that a delivered status proves receipt?

## DO02: Resolution Guidance

**Related research:** E01, E04, E05, FP03, HMW02.

**Potential user need:** Buyers and merchants may benefit from understanding relevant next steps and responsibilities.

**Design opportunity:** Explore contextual guidance that explains possible actions without guaranteeing outcomes.

**Possible interaction concepts:**
- Guided investigation checklist.
- Explanation of possible resolution options.
- Human review before consequential actions.

**Validation question:** Can users identify appropriate next steps and recognize when additional information is required?

## DO03: Transparent Communication

**Related research:** E02, E03, FP01, FP02, HMW03.

**Potential user need:** Buyers and merchants may benefit from clearer communication about case progress and uncertainty.

**Design opportunity:** Explore a shared case-status experience with role-appropriate information.

**Possible interaction concepts:**
- Buyer-facing case-status page.
- Merchant-facing communication history.
- Clear next-step and progress updates.

**Validation question:** Can both user groups understand the current case status and what will happen next?

## Preliminary Scope

**Merchant experience (primary prototype focus):**
- Review a missing-delivery case.
- Examine available evidence.
- Consider possible next steps.
- Communicate an update.

**Buyer experience (supporting prototype flow):**
- Report a missing package.
- View case progress.
- Understand the merchant's response.

These are candidate interactions, not committed MVP requirements.

## Design Constraints

- Use fictional or simulated order data.
- Clearly attribute carrier information and buyer statements.
- Do not treat tracking status as proof of receipt.
- Protect private merchant information.
- Do not automate refunds, denials, or other consequential decisions.
- Do not assume AI is necessary.
- Avoid claiming the prototype integrates with live ecommerce platforms.

## Evidence and Limitations

All design opportunities are hypotheses derived from secondary research and designer interpretation.

No primary interviews, observed workflows, or usability testing have validated these needs.

Source references:
- secondary-research.md (E01–E05)
- competitor-analysis.md (C01–C03)
- service-journey.md (FP01–FP03)
- problem-definition.md (HMW01–HMW03)

Original URLs and source details are maintained in the referenced research documents.



## Research-to-Design Handoff

### 1. Research Outcome

Secondary research identified a specific scenario worth exploring: a buyer reports that a package is missing although carrier tracking indicates delivery.

The research does not establish that existing products are inadequate or that this is a widespread unmet need.

### 2. Provisional Product Concept

SellerPilot is an exploratory two-sided missing-delivery resolution experience.

It will consider both buyer and merchant needs, with a merchant investigation flow and a lightweight buyer reporting and status flow.

### 3. User Roles for Milestone 3

**Merchant**
- Reviews reported delivery issues.
- Examines available evidence.
- Considers possible next steps.
- Communicates case updates.

**Buyer**
- Reports a missing package.
- Provides relevant information.
- Reviews case progress.
- Receives an explanation of the outcome.

### 4. Candidate User Flows

**Merchant flow:**
Open case → Review evidence → Identify unknowns → Consider options → Communicate update.

**Buyer flow:**
Open order → Report missing package → Provide details → Track case → View response.

These are proposed flows, not observed user behavior.

### 5. Information Architecture Questions

- What information belongs in a case overview?
- How should evidence sources and timestamps be organized?
- Which information should buyers and merchants share?
- Which merchant notes should remain private?
- How should status changes and next actions be represented?

### 6. Design Opportunities

| ID | Opportunity | Proposed Exploration |
|---|---|---|
| DO01 | Evidence clarity | Evidence timeline and source attribution |
| DO02 | Resolution guidance | Investigation checklist and option explanations |
| DO03 | Transparent communication | Role-appropriate case status and updates |

These are candidate concepts, not validated requirements.

### 7. Milestone 3 Deliverables

1. Provisional user roles and goals.
2. MVP scope and exclusions.
3. Information architecture.
4. Merchant user flow.
5. Buyer user flow.
6. Low-fidelity wireframes in Figma.
7. Initial interaction decisions and rationale.

### 8. Prototype Constraints

- Fictional case and order data only.
- No live Shopify, Etsy, eBay, or carrier integrations.
- No automatic refunds or dispute decisions.
- No unsupported claims of AI capabilities.
- Clearly distinguish reported facts, carrier records, and unknowns.
- Keep buyer and merchant permissions separate.

### 9. Evaluation Plan

Later usability testing will assess whether participants can:

- Identify contradictory delivery information.
- Distinguish evidence from assumptions.
- Understand available next steps.
- Interpret case status and communication.

Testing with non-merchants will evaluate interface comprehension, not validate real merchant needs.

### 10. Research Traceability

- E01–E05: secondary-research.md
- C01–C03: competitor-analysis.md
- FP01–FP03: service-journey.md
- HMW01–HMW03: problem-definition.md
- DO01–DO03: design-opportunities.md

Original source URLs, dates where available, and limitations are retained in the research files.

### Handoff Status

Ready to begin exploratory UX architecture and low-fidelity design.

Product need, differentiation, and effectiveness remain unvalidated.
