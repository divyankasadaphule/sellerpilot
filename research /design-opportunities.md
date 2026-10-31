
# SellerPilot | Design Opportunities & Research Handoff

**Milestone:** 2 – Product Discovery
**Updated:** October 30, 2026
**Status:** Ready for exploratory UX design

## 1. Purpose

Translate secondary research, competitor analysis, and
primary research findings into provisional design
opportunities for SellerPilot.

This document guides UX architecture, service design,
interaction design, and prototyping in Milestone 3.

## 2. Research Summary

Two Shopify business owners participated in exploratory
primary research.

**P01: Fashion business owner**
- Business started March 2026.
- Reported no significant shipping issues.
- Described Shopify fulfillment as seamless.
- Identified lead generation as the biggest challenge.

**P02: Pooja samagri business owner**
- Business started August 11, 2025.
- Reported missed pickups, delayed deliveries,
  lost shipments, and incorrect deliveries.
- Uses Shopify, logistics software, and Excel.
- Requested better visibility into shipping delays
  and pickup problems.

### Research Interpretation

Shipping challenges are not universal among small sellers.

P02's experience provides initial evidence of logistics
coordination difficulties, while P01's experience
challenges broad assumptions about seller needs.

The differences may relate to order volume, logistics
arrangements, business maturity, or other factors.

These explanations have not been validated.

## 3. Provisional Product Direction

SellerPilot will explore an AI-assisted shipping exception
management workspace for small ecommerce sellers.

The initial experience will focus on helping sellers:

1. Identify shipments requiring attention.
2. Investigate shipping exceptions.
3. Understand available information and possible actions.
4. Coordinate with customers and logistics providers.
5. Track issues through resolution.

This is an evidence-informed design concept,
not a validated product solution.

## 4. Design Opportunities

### DO01: Shipping Exception Visibility

**Evidence:** P02 reported missed pickups, delays,
and the need to continually monitor shipments.

**Potential user need:**
Sellers experiencing recurring logistics problems may
need clearer visibility into shipments requiring action.

**Design opportunity:**
Explore a centralized view of shipping exceptions.

**Possible concepts:**
- Exception overview dashboard.
- Shipment status indicators.
- Delayed pickup notifications.
- Orders requiring attention.

**Validation question:**
Can sellers identify which shipments need attention
and understand why they have been flagged?

### DO02: Shipment Investigation

**Evidence:** P02 described incorrect deliveries,
shipping delays, and logistics-related problems.

**Potential user need:**
Sellers may need to understand what happened before
deciding how to respond.

**Design opportunity:**
Explore a structured shipment investigation experience.

**Possible concepts:**
- Shipment timeline.
- Tracking event history.
- Carrier information.
- Clear distinction between confirmed information,
  reported issues, and unknowns.

**Validation question:**
Can sellers understand the shipment issue and identify
information needed for further investigation?

### DO03: Resolution Guidance

**Evidence:** P02 described coordinating replacement
fulfillment and a logistics claim after an incorrect
delivery.

**Potential user need:**
Sellers may benefit from understanding available
resolution options and outstanding actions.

**Design opportunity:**
Explore contextual next-step guidance.

**Possible concepts:**
- Investigation checklist.
- Suggested next actions.
- AI-assisted case summaries.
- Human approval before consequential actions.

**Validation question:**
Can sellers identify appropriate next steps without
mistaking suggestions for verified decisions?

### DO04: Communication and Coordination

**Evidence:** P02 described communicating with a customer
and logistics provider to resolve an incorrect delivery.

**Potential user need:**
Sellers may need a clearer way to coordinate
communication during shipping investigations.

**Design opportunity:**
Explore seller-controlled communication support.

**Possible concepts:**
- Customer response drafts.
- Communication history.
- Logistics follow-up reminders.
- Case notes.

**Validation question:**
Can sellers prepare an accurate customer update and
identify who needs to be contacted next?

### DO05: Resolution Tracking

**Evidence:** P02 described repeated monitoring and
follow-up during logistics problems.

**Potential user need:**
Sellers may benefit from tracking unresolved shipment
issues and outstanding actions.

**Design opportunity:**
Explore a structured case-management workflow.

**Possible concepts:**
- Open, investigating, and resolved statuses.
- Outstanding action indicators.
- Case activity timeline.
- Resolution notes.

**Validation question:**
Can sellers determine the current case status and
what remains to be done?

## 5. Preliminary Prioritization

| Priority | Opportunity | Rationale |
|---|---|---|
| P1 | DO01: Exception visibility | Directly relates to P02's requested improvement |
| P1 | DO02: Investigation | Supports understanding shipping problems |
| P1 | DO03: Resolution guidance | Supports seller decision-making |
| P2 | DO04: Communication | Relevant to P02's incorrect-delivery example |
| P2 | DO05: Resolution tracking | Potential support for ongoing follow-ups |

Priorities are designer-selected for exploratory prototyping,
not validated user preferences.

## 6. MVP Scope

### Primary Experience: Seller

The seller can:

- View shipments requiring attention.
- Open an exception case.
- Review shipment details and tracking evidence.
- Explore suggested next steps.
- Prepare a customer communication.
- Update and track case status.

### External Participants

**Logistics provider:**
Responsible for physical pickup, transportation,
tracking updates, and delivery.

**Customer:**
Receives order updates and may report problems.

Neither will have a dedicated SellerPilot interface
in the initial prototype.

### Out of Scope

- Live Shopify integration.
- Live logistics-provider integrations.
- Real customer messaging.
- Automated refunds or replacements.
- Full inventory management.
- Accounting and marketing.
- Buyer-facing application.

## 7. Design Constraints

- Use fictional order and shipment data.
- Attribute information to its source.
- Distinguish confirmed facts from reported issues.
- Avoid unsupported shipping or delivery claims.
- Do not automate consequential decisions.
- Keep sellers in control of actions.
- Treat AI suggestions as potentially incorrect.
- Design accessible and understandable interfaces.
- Do not claim live integrations exist.

## 8. Research-to-Design Handoff

### Primary User

Small ecommerce seller personally managing fulfillment
and recurring shipping exceptions.

### Primary Scenario

A seller needs to identify and investigate a shipment
that has not progressed as expected.

The prototype may explore missed pickup, delayed
delivery, or incorrect-delivery scenarios.

### Proposed Seller Flow

Open exception overview
→ Select affected shipment
→ Review shipment information
→ Understand the issue
→ Identify possible actions
→ Prepare follow-up
→ Track resolution

This is a proposed workflow, not an observed sequence.

## 9. Information Architecture Questions

- How should exceptions be organized and prioritized?
- What information belongs in the shipment overview?
- How should tracking events be displayed?
- How should confirmed facts and unknowns be distinguished?
- Where should suggested next steps appear?
- How should unresolved actions be represented?
- How should case history and communication be organized?

## 10. Milestone 3 Deliverables

1. As-is seller journey map.
2. Service blueprint.
3. Information architecture.
4. Seller task flows and user flows.
5. Low-fidelity wireframes.
6. Interaction design rationale.
7. Initial accessibility considerations.

## 11. Evaluation Plan

Later usability testing will involve:

- Two small ecommerce business owners.
- Three non-business owners.

Evaluation will explore:

- Exception identification.
- Shipment information comprehension.
- Understanding of next-step options.
- Navigation and task completion.
- Communication clarity.
- Resolution-status comprehension.

Seller-specific feedback will be distinguished
from general interface usability feedback.

## 12. Evidence and Limitations

Primary research:
- primary-research.md
- primary-research-synthesis.md

Secondary research:
- secondary-research.md
- competitor-analysis.md
- service-journey.md

Problem definition:
- problem-definition.md

Historical direction:
- problem-definition-initial.md

The existing research does not establish that SellerPilot
offers capabilities unavailable in competing products.

The need for AI, market demand, and effectiveness of
the proposed workflows remain unvalidated.

## 13. Handoff Decision

Proceed to Milestone 3 with shipping exception visibility
and coordination as the initial design focus.

This direction is provisional and may be refined through
prototype evaluation and further research.
