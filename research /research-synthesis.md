# SellerPilot: Research Synthesis

## Purpose

Identify preliminary themes, contradictions, and research gaps from secondary research on missing-delivery disputes in ecommerce.

## Evidence Reviewed

- E01: Etsy's official missing-delivery resolution process.
- E02: A buyer-reported delayed-delivery experience.
- E03: A seller-reported missing-delivery dispute.

Full source citations and limitations are recorded in `secondary-research.md`.

## Method

Compare evidence across buyer, seller, and platform perspectives. Group related observations into themes, distinguish supported observations from interpretations, and identify questions requiring further investigation.

## Preliminary Themes

Themes will be documented below with supporting evidence IDs, contradictory evidence where available, and confidence limitations.


## Evidence-to-Theme Matrix

| Evidence ID | Perspective | Observation | Preliminary Theme |
|---|---|---|---|
| E01 | Platform | Etsy documents seller contact, case eligibility, and escalation steps. | Multi-stage dispute resolution |
| E02 | Buyer | A buyer reported uncertainty about shipment status and escalation timing. | Delivery-status and next-step uncertainty |
| E03 | Seller | A seller reported tracking marked as delivered while the buyer said the package was missing. | Conflicting delivery evidence |

**Cross-source interpretation:** E02 and E03 suggest that understanding delivery information may be worth investigating from both buyer and seller perspectives. E01 establishes that resolution can involve multiple procedural steps.

**Confidence and limitations:** These are preliminary themes based on one platform's official documentation and two self-reported accounts. They do not establish prevalence, causation, or the usability of Etsy's current interface. Source URLs and detailed limitations are recorded under E01-E03 in `secondary-research.md`.

**Next research question:** How do other ecommerce platforms communicate shipment evidence, escalation eligibility, and resolution responsibilities?

- E04: eBay's official missing-delivery resolution process.
- E05: Shopify's merchant-led missing-delivery resolution process.


## Cross-Platform Synthesis

### Platform Comparison

| Platform | Documented Resolution Model | Evidence Reference | Research Question |
|---|---|---|---|
| Etsy | Seller contact followed by eligible case escalation through Etsy. | E01 | Are escalation steps and eligibility requirements clear to users? |
| eBay | Seller response, tracking evidence, and potential eBay intervention. | E04 | Do buyers and sellers understand the evidence required for resolution? |
| Shopify | Independent merchants handle customer issues, supported by order, tracking, refund, and shipping-claim tools. | E05 | How do merchants coordinate information and decisions across services? |

### Preliminary Cross-Platform Findings

**Finding 1: Resolution responsibility differs across platforms.**
Etsy and eBay document platform-managed escalation processes, while Shopify generally places customer-service and refund decisions with independent merchants. (Evidence: E01, E04, E05)

**Finding 2: Delivery information and evidence are relevant across service models.**
Official platform workflows reference shipment or tracking information. Buyer and seller accounts also raise questions about interpreting delivery status. (Evidence: E01-E05)

**Finding 3: The strongest product opportunity is not yet established.**
The available evidence supports investigating buyer guidance, seller decision-making, and information coordination. It does not establish which user group has the greatest unmet need.

### Contradictions and Limitations

- Official policies describe intended workflows, while public discussions describe individual reported experiences.
- Different platforms have different responsibilities and protection policies; their processes are not directly interchangeable.
- At the time of this secondary research synthesis, primary interviews had not yet been conducted. The secondary evidence alone does not establish the frequency of any reported difficulty. Subsequent interviews are documented separately.
- We cannot yet conclude that existing tools are inadequate or that AI assistance is necessary.

### Questions for Competitor Analysis

1. What tools already combine order, tracking, and customer communication information?
2. How do existing products support missing-delivery investigations?
3. Which decisions remain with the merchant or platform?
4. Do existing tools provide explanations, safeguards, or human approval for automated actions?
5. What potential gaps remain after accounting for existing capabilities?

**Source traceability:** See E01-E05 in `secondary-research.md` for original URLs, source details, observations, and limitations.


---

## Research Update: Primary Research Integration

**Date:** October 30, 2026
**Status:** Updated design direction following exploratory interviews

### Primary Research Conducted

Two small ecommerce business owners participated in
asynchronous qualitative interviews.

**P01: Fashion business owner**
- Uses Shopify for fulfillment.
- Reported no significant shipping difficulties.
- Identified lead generation as the biggest challenge.

**P02: Pooja samagri business owner**
- Uses Shopify, logistics software, and Excel.
- Reported missed pickups, delivery delays,
  incorrect shipments, and logistics follow-ups.
- Expressed a need for clearer visibility into
  shipping problems.

### Relationship to Secondary Research

The original secondary research explored
delivered-but-missing package disputes.

Primary research revealed that shipping-related
challenges may extend beyond this scenario.

P02's experience suggests an opportunity to explore
shipping exception visibility and coordination.

P01's contrasting experience indicates that these
problems should not be assumed to affect all
small ecommerce sellers.

### Updated Design Direction

SellerPilot will explore a seller-facing shipping
exception management workspace.

The provisional focus includes:

1. Identifying shipments requiring attention.
2. Reviewing shipment and tracking information.
3. Understanding potential next steps.
4. Supporting seller-controlled communication.
5. Tracking unresolved shipping issues.

The original delivered-but-missing scenario remains
part of the secondary research history but is no
longer the sole focus of the proposed MVP.

### Research Limitations

- Only two exploratory interviews were conducted.
- Both participants use Shopify.
- Order volumes and exception frequencies are unknown.
- Existing logistics products have not been tested
  directly against the reported challenges.
- AI assistance has not been validated as necessary.
- Market demand and product differentiation remain
  unvalidated.

### Updated Research References

- primary-research.md
- primary-research-synthesis.md
- problem-definition.md
- design-opportunities.md

### Decision

Proceed to Milestone 3 using shipping exception
visibility, investigation, and coordination as
the provisional design focus.

This decision reflects exploratory research and
project learning objectives, not validated market demand.
