# SellerPilot: Missing-Delivery Service Journey

## Purpose

Map the interactions between buyers, merchants, shipping carriers, and ecommerce platforms during a missing-delivery issue.

This journey will help identify potential coordination challenges and unanswered research questions before defining SellerPilot's product requirements.

## Scenario

A buyer reports that an online order has not arrived. The merchant must understand the delivery status, communicate with the buyer, and determine the appropriate next step.

The scenario is informed by evidence E01–E05 but is not a reconstruction of one verified customer's experience.

## Participants

- **Buyer:** Reports the missing order and provides relevant information.
- **Merchant:** Reviews order details, communicates with the buyer, and considers resolution options.
- **Shipping carrier:** Provides tracking information and may investigate delivery issues.
- **Ecommerce platform:** Provides order-management and support processes, depending on the platform.

## Research Approach

This is a preliminary, evidence-informed service journey based on secondary research.

We will distinguish:

- Documented process steps supported by sources.
- Reported experiences from individual buyers or sellers.
- Hypothetical steps and potential friction points requiring validation.

## Evidence Sources

- E01: Etsy official missing-delivery process.
- E02: Buyer-reported missing-delivery experience.
- E03: Seller-reported missing-delivery experience.
- E04: eBay official missing-delivery process.
- E05: Shopify merchant-led resolution process.
- C01–C03: Shopify, Gorgias, and AfterShip capability reviews.

Original URLs and source details are recorded in `secondary-research.md` and `competitor-analysis.md`.

## Limitations

This journey does not represent a universal workflow across Etsy, eBay, and Shopify. Their policies and responsibilities differ.

At the time this preliminary journey was created, no primary interviews or observed workflow tests had been conducted. Two exploratory seller interviews were subsequently completed and documented separately.



## Preliminary Service Journey Map

| Stage | Buyer | Merchant | Carrier | Platform / Tool | Potential UX Question | Evidence |
|---|---|---|---|---|---|---|
| 1. Order placed | Places an order and receives confirmation | Receives and prepares the order | Not yet involved or awaiting shipment | Records order and transaction | What information is available to both parties? | E01, E04, E05; C01 |
| 2. Delivery issue emerges | Notices that an order has not arrived or tracking appears inconsistent | May receive a shipping alert or customer inquiry | Supplies shipment status and tracking events | Displays available tracking information | How do users interpret incomplete or conflicting statuses? | E02, E03; C01, C03 |
| 3. Buyer reports issue | Contacts the merchant or uses the relevant platform support process | Reviews the request and responds | May be contacted for clarification | Provides messaging or case tools, depending on platform | Are next steps and responsibilities clear? | E01, E04, E05; C01, C02 |
| 4. Investigation | May provide address details or other relevant information | Reviews order details, tracking, messages, and available evidence | May investigate or provide delivery confirmation | May offer tracking, ticketing, or exception-management tools | How is evidence gathered and interpreted? | E03; C01, C02, C03 |
| 5. Resolution decision | Seeks an outcome or explanation | Considers applicable refund, replacement, claim, or escalation options | May process an eligible shipping claim | Policies and supported actions vary by platform | How are options and constraints communicated? | E01, E04, E05; C01, C02, C03 |
| 6. Resolution and follow-up | Receives an update or outcome | Communicates the decision and completes applicable actions | May provide final investigation or claim information | Records supported case or order actions | How does each party know the issue is resolved? | E01, E04, E05; C01, C02 |

### How to Interpret This Map

This is an **illustrative, evidence-informed journey**, not an observed end-to-end user journey.

- Evidence IDs identify relevant documentation or individual reported experiences, not proof that every step happens in every case.
- Platform responsibilities differ across Etsy, eBay, and Shopify.
- Potential UX questions are hypotheses requiring further investigation.
- Refunds, replacements, claims, and escalations are conditional options, not guaranteed outcomes.

### Initial Research Insight

The investigation and decision stages deserve further examination because they may involve multiple information sources and responsibilities.

However, existing tools already support parts of these activities. The current evidence does not establish that a new product is necessary.

**Source traceability:** Original URLs, dates, and source limitations are documented in `secondary-research.md` (E01–E05) and `competitor-analysis.md` (C01–C03).



## Potential Friction Points

### FP01: Delivery Status Uncertainty

**Journey stage:** 2. Delivery issue emerges

**Evidence:** E02 (buyer-reported experience)

**Observation:** A buyer reported receiving a shipment notification while carrier tracking appeared to show only that a label had been created.

**Potential friction (hypothesis):** Buyers may struggle to understand what a shipping status means and when they should take further action.

**Validation needed:** Review additional cases and test how buyers interpret shipment statuses.

### FP02: Conflicting Delivery Evidence

**Journey stage:** 4. Investigation

**Evidence:** E03 (seller-reported experience)

**Observation:** A seller described a shipment marked delivered while the buyer reported not receiving it.

**Potential friction (hypothesis):** Merchants may find it difficult to evaluate conflicting information and determine an appropriate next step.

**Validation needed:** Investigate existing merchant workflows and how support tools handle delivered-but-missing reports.

### FP03: Resolution Process Coordination

**Journey stages:** 3–5. Reporting, investigation, and decision

**Evidence:** E01, E04, E05 (official platform documentation)

**Observation:** Resolution procedures can involve buyer contact, merchant response, tracking information, platform escalation, or carrier claims. Responsibilities vary across platforms.

**Potential friction (hypothesis):** Users may have difficulty understanding responsibilities, requirements, or the sequence of next steps.

**Validation needed:** Conduct task-based usability evaluation of existing resolution instructions and workflows.

## Evidence Strength Assessment

| Friction Point | Evidence Type | What We Can Conclude | What We Cannot Conclude |
|---|---|---|---|
| FP01 | One self-reported buyer account | This situation was reported | That it is common among buyers |
| FP02 | One self-reported seller account | This situation was reported | That most merchants struggle with it |
| FP03 | Official platform procedures | Multiple process steps and responsibilities exist | That these steps are confusing or inefficient |

## Preliminary Opportunity Areas

1. Clarifying shipment status and appropriate next steps.
2. Helping merchants organize and interpret conflicting delivery evidence.
3. Making resolution responsibilities and options easier to understand.

These are **opportunity hypotheses**, not validated requirements.

## Research Limitations

At the time this preliminary journey was created, no primary interviews or observed workflow tests had been conducted. Two exploratory seller interviews were subsequently completed and documented separately.

Evidence references and original source URLs are recorded in `secondary-research.md` (E01–E05).



## Friction Point Prioritization

### Prioritization Method

The three potential friction points were assessed qualitatively using:

1. Evidence strength: How directly does available research support the issue?
2. Product relevance: How closely does the issue relate to missing-delivery resolution?
3. Scope: Could the issue be explored through a focused UX prototype?
4. Existing solutions: What capabilities do competitors already provide?

These are designer assessments, not measured user-impact scores.

### Prioritization Matrix

| ID | Potential Friction | Evidence Strength | Product Relevance | Scope | Decision |
|---|---|---|---|---|---|
| FP01 | Delivery status uncertainty | Low | Medium | Focused | Secondary investigation |
| FP02 | Conflicting delivery evidence | Low | High | Focused | Provisional design focus |
| FP03 | Resolution process coordination | Moderate process evidence; usability impact unknown | High | Broad | Supporting context |

### Provisional Focus: FP02

**Scenario:** A merchant receives a customer message reporting that an order is missing, even though carrier tracking shows it as delivered.

**Why investigate this scenario?**

- E03 contains a seller-reported example of this contradiction.
- The situation involves information interpretation and consequential decisions.
- It can be explored through a narrow, realistic prototype scenario.
- Competitor research C01–C03 shows relevant existing capabilities but does not establish whether they adequately support this exact situation.

### What This Decision Does Not Mean

- FP02 is not a validated widespread problem.
- We have not proven existing products handle it poorly.
- We have not established that merchants are the most affected user group.
- We have not determined whether AI is needed.

### Next Validation Questions

1. What evidence does a merchant need when tracking says delivered but a buyer reports non-delivery?
2. How do current tools display and explain that evidence?
3. What resolution options are available under different merchant and platform policies?
4. Which parts of the workflow, if any, cause uncertainty?
5. Could a simple guided interface improve clarity without making automated decisions?

### Decision Status

**Provisional design direction for exploration only.**

This direction may change following further evidence review, usability evaluation, or prototype testing.

### Evidence References

- E03: Seller-reported missing-delivery case.
- E01, E04, E05: Official platform resolution procedures.
- C01–C03: Existing product capability reviews.

Original source URLs and limitations are documented in the corresponding research files.



## Service Journey Conclusions

### Research Summary

The preliminary service journey mapped six stages of missing-delivery resolution, from order placement through investigation, decision-making, and follow-up.

The analysis considered buyer, merchant, carrier, and platform responsibilities using secondary research (E01–E05) and competitor documentation (C01–C03).

### Key Insights

**1. Missing-delivery resolution involves multiple participants.**

Official platform documentation describes interactions between buyers, merchants, platforms, and, where applicable, shipping carriers. Responsibilities differ by ecommerce service.

Evidence: E01, E04, E05.

**2. Delivery information can be inconsistent with reported experiences.**

One buyer account described uncertainty about shipment progress (E02), while one seller account described tracking marked delivered despite a buyer reporting non-delivery (E03).

These individual reports do not establish how frequently such situations occur.

**3. Existing products already support significant parts of the journey.**

Shopify, Gorgias, and AfterShip document capabilities related to order information, tracking, customer support, automation, or shipment exceptions.

Evidence: C01–C03.

The research does not establish that these products are inadequate.

### Provisional Design Focus

Explore the following scenario:

**A small ecommerce merchant receives a report that a package is missing, although carrier tracking indicates delivery.**

This scenario was selected because it is specific enough for a focused UX prototype and raises questions about interpreting evidence and explaining resolution options.

It is a designer-selected scenario, not a validated widespread user problem.

### Design Principles to Explore

- Make evidence sources and timestamps understandable.
- Distinguish confirmed information from customer reports and uncertainty.
- Explain available actions without promising a particular outcome.
- Keep consequential decisions under human control.
- Avoid unnecessary AI automation.

These are preliminary design considerations, not validated requirements.

### Remaining Limitations

This original journey was developed before the primary interviews and remains an illustrative secondary-research artifact, not an observed end-to-end workflow.

Potential friction points and product differentiation remain unvalidated.

### Next Step

Use the provisional scenario to draft a problem statement, identify assumptions, and develop research-informed How Might We questions.

### Source Traceability

See secondary-research.md (E01–E05) and competitor-analysis.md (C01–C03) for original URLs, source details, and limitations.



---

## Research Update: Shipping Exception Journey

**Date:** October 30, 2026
**Status:** Historical journey retained; design focus updated

### Why the Direction Changed

The original service journey explored missing-delivery
disputes using secondary research.

Subsequent interviews with two Shopify sellers revealed
contrasting operational experiences.

P01 reported no significant shipping difficulties.

P02 reported missed pickups, delivery delays, incorrect
shipments, and repeated logistics follow-ups.

These findings suggest exploring a broader shipping
exception workflow rather than focusing exclusively
on delivered-but-missing disputes.

### Updated Primary User

Small ecommerce sellers who personally coordinate
fulfillment and experience recurring shipping exceptions
involving external logistics providers.

This user segment remains provisional.

### Proposed Journey for Milestone 3

The next journey map will explore:

1. Order preparation and shipping arrangement.
2. Carrier pickup or shipment dispatch.
3. Shipping exception occurs or becomes visible.
4. Seller identifies and investigates the issue.
5. Seller coordinates with the logistics provider
   and, when necessary, the customer.
6. Seller follows up and tracks resolution.

These stages are an initial analytical structure,
not a verified end-to-end participant journey.

### Service Participants

**Seller:** Primary user of SellerPilot.

**Logistics provider:** External participant responsible
for pickup, transportation, tracking, and delivery.

**Customer:** May report problems or require updates.

**Ecommerce platform:** Provides order information
and existing fulfillment capabilities.

Only the seller-facing experience is included
in the initial SellerPilot MVP.

### Updated Research Questions

- When and how do sellers first notice shipping problems?
- What information do sellers check during investigation?
- Which actions require contacting logistics providers?
- How do sellers remember unresolved follow-ups?
- What information is needed before contacting customers?
- Which parts of the workflow are already supported
  effectively by existing tools?

### Design Implications

Milestone 3 will explore:

- An as-is seller journey map.
- A service blueprint.
- Shipping exception information architecture.
- Seller task flows and user flows.
- Low-fidelity wireframes.

The original missing-delivery journey remains valuable
background research, but its previous FP02 prioritization
is no longer SellerPilot's current design decision.

### Evidence and Limitations

Primary research:
- primary-research.md
- primary-research-synthesis.md

Current product direction:
- problem-definition.md
- design-opportunities.md

The two interviews do not establish how frequently
these problems occur across ecommerce businesses.

The proposed journey stages require further validation.

### Decision

Proceed with a seller-facing shipping exception
management concept for exploratory UX design.

The earlier missing-delivery scenario remains
documented as part of the research history.
