# SellerPilot: Problem Definition

## Purpose

Define a focused problem for further UX exploration using the secondary research, competitor analysis, and preliminary service journey.

## Provisional Target User

A small ecommerce merchant who manages customer inquiries and order-related issues.

This user group has been selected for design exploration. We have not established that it experiences the greatest unmet need.

## Scenario

A customer reports that a package has not arrived, but the shipping carrier's tracking system indicates that the package was delivered.

The merchant needs to review available information and determine an appropriate response.

## Preliminary Problem Statement

Small ecommerce merchants handling delivered-but-missing package reports may need clearer ways to review conflicting delivery information and understand possible resolution steps, so they can respond to customers with appropriate context and make informed decisions.

**Status:** Unvalidated problem hypothesis.

## Evidence Supporting Exploration

- E03: One seller reported a delivered-but-missing shipment dispute.
- E01, E04, E05: Official documentation describes resolution responsibilities and procedures across different ecommerce service models.
- C01–C03: Existing products provide relevant order-management, support, tracking, and exception-handling capabilities.
- FP02: Conflicting delivery evidence was selected as a provisional design focus during service journey analysis.

These sources justify investigating the scenario, but do not demonstrate that existing solutions are inadequate.

## Assumptions Requiring Validation

1. Merchants encounter difficulty interpreting contradictory delivery information.
2. Relevant evidence may be difficult to review in existing workflows.
3. Merchants would benefit from structured guidance about resolution options.
4. A focused interface could improve decision clarity.
5. Additional AI functionality might not be necessary.

## Research Limitations

This definition is based on secondary research, not interviews or observed merchant workflows.

We have not measured the frequency, severity, or business impact of this issue.

## Source Traceability

Original URLs, publication details where available, observations, and limitations are documented in:

- secondary-research.md (E01–E05)
- competitor-analysis.md (C01–C03)
- service-journey.md (FP01–FP03 and prioritization)




## How Might We Questions

### HMW01: Evidence Clarity

How might we help small ecommerce merchants understand conflicting delivery information when a customer reports a package missing but tracking indicates delivery?

**Evidence:** E03, FP02.

**Opportunity hypothesis:** Clear presentation of evidence sources, timestamps, and uncertainty may support better understanding.

### HMW02: Resolution Decision Support

How might we help merchants understand the possible next steps in a delivered-but-missing situation without making decisions on their behalf?

**Evidence:** E01, E04, E05, FP03.

**Opportunity hypothesis:** Explaining available options and relevant constraints may support informed decisions.

### HMW03: Customer Communication

How might we help merchants communicate what is known, what remains uncertain, and what will happen next?

**Evidence:** E02, E03, FP01, FP02.

**Opportunity hypothesis:** Clearer communication may help both parties understand the investigation status.

## Preliminary Prioritization

**Primary exploration question:** HMW01: Evidence Clarity.

**Supporting questions:** HMW02 and HMW03.

HMW01 is prioritized because it directly addresses the provisional FP02 scenario and provides a focused interaction-design challenge.

This is a designer-led prioritization, not a validated user preference.

## Design Boundaries

- Do not assume the carrier's delivered status proves the buyer received the package.
- Do not assume the buyer's report is inaccurate.
- Do not recommend automatic refunds or denials without considering applicable policies.
- Do not introduce AI unless a specific benefit can be demonstrated.
- Clearly distinguish confirmed evidence, reported information, and unknowns.

## Next Step

Translate the primary HMW question into a preliminary design goal and testable success criteria.

## Source Traceability

Original source URLs and research limitations are documented in secondary-research.md (E01–E05), competitor-analysis.md (C01–C03), and service-journey.md (FP01–FP03).



## Preliminary Design Goals and Success Criteria

### Primary Design Goal

Explore whether a focused interface can help small ecommerce merchants review conflicting delivery evidence, recognize uncertainty, and identify appropriate next steps when tracking shows delivered but a buyer reports non-delivery.

**Status:** Proposed design goal, not a validated user need.

### Goal 1: Make Delivery Evidence Understandable

The interface should help users distinguish:

- Carrier-reported delivery status.
- Customer-reported non-delivery.
- Available timestamps and evidence sources.
- Information that remains unknown.

**Proposed usability measures:**

- Can participants correctly identify the carrier's status and the buyer's report?
- Can they distinguish verified information from unverified claims?
- Can they identify at least one important unknown?

### Goal 2: Support Informed Decisions

The interface should help users understand possible resolution steps without automatically choosing an outcome.

**Proposed usability measures:**

- Can participants identify relevant next-step options?
- Can they explain what additional information may be needed?
- Can they locate applicable policy or eligibility information when provided?

### Goal 3: Support Clear Customer Communication

The interface should help users explain the current situation and communicate a reasonable next step.

**Proposed usability measures:**

- Can participants draft or select a message that accurately reflects known and unknown information?
- Does the message avoid promising an unsupported outcome?
- Can participants explain what action will happen next?

### Preliminary Test Scenario

A fictional customer contacts a small online merchant:

"My order says delivered, but I haven't received the package."

The prototype presents simulated order information, tracking events, and a customer message.

Participants are asked to review the case, explain the evidence, identify an appropriate next step, and prepare a customer response.

### Evaluation Approach

During Milestone 7, conduct moderated task-based usability sessions, ideally with five participants.

Record:

- Task completion and observed errors.
- Incorrect interpretations of evidence.
- Points of hesitation or confusion.
- Participant explanations and feedback.
- Changes made after testing.

If participants are not actual ecommerce merchants, describe the findings as general interface-usability feedback, not validation of merchant needs.

### What We Will Not Claim

- That the proposed interface improves merchant efficiency before testing.
- That users make better decisions without appropriate evaluation.
- That a small usability sample represents all ecommerce merchants.
- That AI is required to achieve these goals.

### Success Criteria Status

These are proposed evaluation criteria. Quantitative thresholds and final test tasks will be defined when the prototype and testing protocol are prepared.

### Evidence Traceability

Design goals derive from HMW01–HMW03, FP01–FP03, and research evidence E01–E05.

Original source URLs and limitations are documented in the related research files.



## Problem Definition Conclusions

### 1. Provisional Design Direction

SellerPilot will explore a decision-support experience for small ecommerce merchants handling delivered-but-missing package reports.

The focus is on understanding conflicting information and identifying possible next steps, rather than automatically deciding whether to refund or deny a customer request.

### 2. Primary Design Challenge

How might we help merchants understand conflicting delivery evidence while clearly distinguishing known facts, reported information, and uncertainty?

### 3. Supporting Design Challenges

- Explain relevant resolution options and constraints.
- Support clear, accurate customer communication.
- Keep consequential decisions under human control.

### 4. Decisions Made

| Decision | Rationale | Status |
|---|---|---|
| Explore small ecommerce merchants | Provides a focused design scenario | Provisional |
| Focus on delivered-but-missing cases | Supported as a reported scenario by E03 | Provisional |
| Prioritize evidence clarity | Directly relates to HMW01 and FP02 | Designer-selected |
| Explore decision support | Relevant to documented resolution processes | Unvalidated |
| Avoid assuming AI is necessary | Existing tools already offer AI capabilities | Design constraint |

### 5. Assumptions Still Requiring Validation

- Merchants experience meaningful difficulty interpreting conflicting evidence.
- Existing tools do not adequately support this specific scenario.
- Clearer information presentation would improve understanding.
- A dedicated workflow would provide value beyond existing products.

### 6. Next Research and Design Activities

1. Translate the design direction into potential features and interaction requirements.
2. Identify which assumptions can be evaluated through a simulated prototype.
3. Review existing solutions again where capabilities remain uncertain.
4. Prepare task-based usability evaluation criteria.

### 7. Research Integrity

This problem definition is based on secondary research and designer interpretation.

It does not establish a widespread unmet need, demonstrate that competitors are inadequate, or prove that SellerPilot requires AI.

All evidence references and original source URLs remain documented in the related research files.

### Decision Status

**Ready for exploratory design, subject to further validation.**

## Scenario-Specific Competitor Review

**Date accessed:** October 14, 2026
**Method:** Secondary research using official product documentation.

### SC01: AfterShip Delivered-but-Missing Support

**Source 1:** AfterShip. *Where Is My Package?*
https://support.aftership.com/en/tracking/articles/15441909-where-is-my-package

**Source 2:** AfterShip, Harneet Kaur.
*Learn About Delivery Sub-Status.*
https://support.aftership.com/en/tracking/articles/15441382-learn-about-delivery-sub-status

**Source 3:** AfterShip.
*Handle Exception Shipments with AfterShip Agent.*
https://support.aftership.com/en/tracking/articles/15441341-handle-exception-shipments-with-aftership-agent

**Publication dates:** Not established for these specific pages.
**Source type:** Official product documentation.

### Documented Observations

- [1] AfterShip provides guidance for packages marked delivered but not received.
- [2] AfterShip distinguishes delivery sub-statuses, including delivery to a neighbour.
- [3] AfterShip Agent supports shipment exception detection and management.

### UX Interpretation

AfterShip already addresses aspects of delivery-status interpretation and shipment investigation.

However, these sources do not establish how effectively the product supports merchants when customer reports contradict carrier delivery information.

### Remaining Research Question

Can a focused interface help merchants evaluate contradictory delivery evidence and explain next steps more clearly than existing workflows?

### Limitation

No hands-on competitor evaluation or merchant usability testing has been conducted. A product gap has not been validated.

### Design Decision

Continue exploring the delivered-but-missing scenario as a provisional UX design challenge, without claiming that existing tools lack this capability.



## Revised Problem Definition: Two-Sided Experience

### Why the Direction Evolved

Our initial exploration focused on small ecommerce merchants managing missing-delivery reports.

Further reflection on buyer and merchant perspectives suggests that the same delivery dispute may create different information and communication needs for both parties.

This is a designer-led refinement, not a validated research finding.

### Provisional User Groups

**Primary user: Small ecommerce merchant**

Investigates missing-delivery reports, reviews available evidence, evaluates resolution options, and communicates with the customer.

**Secondary user: Online buyer**

Reports a missing package, provides relevant information, receives investigation updates, and understands available next steps.

These roles are provisional and may change after further evaluation.

### Revised Working Problem Statement

When a package is marked delivered but the buyer reports it missing, buyers and merchants may lack a shared understanding of the available evidence, investigation progress, and next steps, making the resolution process harder to navigate.

**Status: Unvalidated problem hypothesis.**

### Shared Goal

Support a fair, understandable, and transparent missing-delivery resolution experience.

### Different User Needs

| Buyer | Merchant |
|---|---|
| Report a missing package | Review the customer's report |
| Understand the reported delivery status | Examine available delivery evidence |
| Know what happens next | Evaluate possible resolution options |
| Receive clear progress updates | Communicate progress and decisions |
| Understand the final outcome | Record and explain the outcome |

### Preliminary Product Direction

Explore a connected experience with:

1. A merchant-facing investigation and decision-support workflow.
2. A buyer-facing reporting and case-status experience.

Both experiences would reference the same fictional case, but display information appropriate to each role.

### MVP Scope Decision

Design the merchant investigation workflow first, followed by a lightweight buyer-facing reporting and status flow.

This is a scope-management decision, not evidence that merchant needs are more important.

### Important Design Boundaries

- A delivered tracking status does not prove the buyer received the package.
- Buyer reports and carrier records must be clearly attributed.
- Private merchant notes and internal decisions should not automatically be visible to buyers.
- Refunds and replacements depend on applicable policies and circumstances.
- Human review remains necessary for consequential decisions.
- AI is optional, not a predetermined requirement.

### Research Gaps

- Do buyers and merchants actually lack shared understanding?
- Which information should be visible to each participant?
- How do existing platforms support shared case progress?
- Would a connected experience improve clarity compared with existing tools?
- Which parts of the proposed workflow are useful without AI?

### Evidence and Limitations

E01, E04, and E05 document platform resolution processes.

E02 and E03 provide individual buyer and seller reports.

C01–C03 document existing product capabilities.

These sources support exploring the scenario but do not validate the revised problem statement or establish an unmet market need.

Original URLs and source details remain in secondary-research.md and competitor-analysis.md.
