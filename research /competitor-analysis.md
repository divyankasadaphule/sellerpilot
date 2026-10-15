# SellerPilot: Competitor & Existing-Tool Analysis

## Purpose

Examine existing ecommerce tools before proposing SellerPilot features. Identify documented capabilities, potential limitations, and questions requiring further validation.

## C01: Shopify Native Tools

**Organization:** Shopify
**Source type:** Official product documentation
**Date accessed:** October 14, 2026
**Publication/last-updated dates:** Not consistently displayed on the reviewed pages

### Sources

1. Shopify. *Viewing and managing order details*. https://help.shopify.com/en/manual/fulfillment/managing-orders/managing-order-details
2. Shopify. *Order tracking at Shopify*. https://help.shopify.com/en/manual/fulfillment/setup/order-status-page/order-tracking
3. Shopify. *Shopify Inbox*. https://help.shopify.com/en/manual/inbox
4. Shopify. *Refunding orders*. https://help.shopify.com/en/manual/orders/refund-cancel-order

### Verified capabilities

- [1] Merchants can review order information, timelines, notes, and customer details, and contact customers.
- [2] Shopify supports shipment tracking through order-status pages, notification emails, and the Shop app.
- [3] Shopify Inbox supports customer conversations and offers an optional AI-powered Inbox agent for answering customer questions.
- [4] Merchants can issue full or partial refunds from Shopify Admin.

### UX interpretation (not validated)

Shopify already provides several capabilities relevant to missing-delivery resolution. Before designing SellerPilot, we need to investigate whether specific investigation or decision-making tasks remain difficult despite these tools.

### Research gaps

- Can merchants conveniently review all relevant missing-delivery evidence in one workflow?
- How does the Inbox agent handle ambiguous delivery information?
- What support exists for deciding between refunding, replacing, waiting, or submitting a carrier claim?
- Are these capabilities sufficient for small merchants?

### Limitations

Official documentation confirms stated product capabilities but does not establish usability, user satisfaction, or unmet needs. No hands-on product evaluation or merchant interviews have been conducted.

### Status

Capability review completed. Usability and workflow gaps remain unverified.


## C02: Gorgias Ecommerce Helpdesk

**Organization:** Gorgias
**Source type:** Official product documentation
**Date accessed:** October 14, 2026
**Publication/last-updated dates:** See individual source pages; dates vary.

### Sources

1. Gorgias. *Connect a store to Gorgias: Shopify*. https://docs.gorgias.com/en-US/connect-shopify-to-gorgias-81814
2. Gorgias. *Shopify Actions*. https://docs.gorgias.com/en-US/shopify-actions-461552
3. Gorgias. *AI Agent Actions: make changes to Shopify orders*. https://docs.gorgias.com/en-US/ai-agent-actions-make-changes-to-shopify-orders-757792
4. Gorgias. *Create an action for AI Agent*. https://docs.gorgias.com/en-US/create-an-action-for-ai-agent-567325

### Verified capabilities

- [1] A Shopify integration brings customer order history, shipping details, and purchase information into the helpdesk alongside support tickets.
- [1, 2] Agents can perform supported Shopify order actions, including refunds and cancellations, within Gorgias.
- [3] The AI Agent can perform configured actions such as cancelling orders or changing shipping addresses.
- [4] AI actions can use conditions to restrict when they execute.
- [4] Customer-confirmation checkpoints can be configured, and certain irreversible actions trigger confirmation automatically.

### UX interpretation (not validated)

Gorgias already addresses several proposed SellerPilot capabilities, including unified order context, support workflows, AI actions, and safeguards. A differentiated design opportunity cannot be established simply by combining these features.

### Research gaps

- How does Gorgias support investigations when tracking says delivered but a buyer reports non-delivery?
- How clearly does it explain conflicting evidence or uncertainty to support agents?
- Does it provide a structured comparison of refund, replacement, carrier claim, and escalation options?
- How do small merchants experience the workflow in practice?

### Potential design direction (hypothesis only)

Investigate whether a narrowly focused missing-delivery investigation workflow could offer value beyond existing helpdesk capabilities. This is not a verified product gap.

### Limitations

This is a documentation-based capability review, not hands-on usability testing. Feature availability may depend on plan, integrations, configuration, and permissions. The absence of a feature from reviewed documentation does not prove the product lacks that feature.

### Status

Official capability review completed. Unmet needs and differentiation remain unverified.


## Competitor Capability Matrix

| Capability | Shopify (C01) | Gorgias (C02) | AfterShip (C03) |
|---|---|---|---|
| Customer and order details | Documented | Shopify integration | Shopify integration for supported actions |
| Shipment tracking | Documented | Shipment details in helpdesk | Core tracking capability |
| Customer communication | Shopify Inbox | Support tickets and messaging | Tracking notifications |
| Refund management | Shopify Admin | Supported Shopify actions | Supported exception-handling actions for eligible orders |
| AI assistance | Inbox AI agent | AI Agent | AfterShip Agent |
| Shipment exception detection | Not established by reviewed sources | Not established by reviewed sources | Documented |
| Exception grouping and recommended actions | Not established by reviewed sources | Not established by reviewed sources | Documented |
| Configurable AI actions and safeguards | Not established by reviewed sources | Documented | Further investigation needed |
| Conflicting delivered-status evidence analysis | Not established by reviewed sources | Not established by reviewed sources | Not established by reviewed sources |
| Guided comparison of resolution options | Not established by reviewed sources | Not established by reviewed sources | Not established by reviewed sources |

### Cross-Competitor Interpretation

**Observation 1: Existing tools cover much of the proposed workflow.**

Shopify provides foundational order and customer-support capabilities. Gorgias adds integrated helpdesk workflows and AI actions. AfterShip provides shipment exception management and supported resolution actions. (Evidence: C01, C02, C03)

**Observation 2: Missing-delivery support is not an untouched product space.**

AfterShip already documents exception detection, grouping, recommended actions, and certain refund or reship workflows. SellerPilot cannot claim these capabilities are unique. (Evidence: C03)

**Observation 3: Differentiation remains an open research question.**

The reviewed sources do not establish whether merchants need additional help interpreting contradictory tracking evidence or comparing resolution options.

### Potential Design Hypothesis

Small ecommerce merchants might benefit from a focused workflow that explains conflicting delivery information and helps them evaluate possible next steps before taking action.

**Status:** Unvalidated hypothesis, not a confirmed user need.

### Evidence and Limitations

- C01: Shopify official documentation and URLs recorded above.
- C02: Gorgias official documentation and URLs recorded above.
- C03: AfterShip official documentation and URLs recorded above.
- "Not established by reviewed sources" does not mean the capability is absent.
- This comparison is based on product documentation, not hands-on usability testing or merchant interviews.
- Features may depend on subscription plan, integrations, configuration, and permissions.



## C03: AfterShip Tracking

**Organization:** AfterShip
**Source type:** Official product documentation
**Date accessed:** October 14, 2026
**Document author:** Harneet Kaur

### Sources

1. AfterShip. *Everything You Need to Know About Exception Shipments*. Published July 1, 2026. https://support.aftership.com/en/tracking/articles/15441374-everything-you-need-to-know-about-exception-shipments
2. AfterShip. *Set Up Exception Handling Settings*. Updated October 2026 (relative date shown by source; exact date not established). https://support.aftership.com/en/tracking/articles/17126856-set-up-exception-handling-settings
3. AfterShip. *Notification Delivery*. Updated October 2026 (exact date not established). https://support.aftership.com/en/tracking/articles/15441685-notification-delivery
4. AfterShip. *How to Check Shipping Exceptions Report*. Published July 1, 2026. https://support.aftership.com/en/tracking/articles/15441612-how-to-check-shipping-exceptions-report

### Verified capabilities

- [1] Merchants can identify and filter shipments marked with an Exception status, apply tags, and configure internal or customer notifications.
- [2] AfterShip offers an Exceptions dashboard with carrier-reported, custom, and manually flagged exception types.
- [2] AfterShip Agent can group matching shipments into tasks and provide recommended actions.
- [2] Eligible Shopify-connected merchants can use reship and refund actions in exception handling.
- [3] Tracking-based notifications cover shipment events such as in transit, delivered, failed attempt, and exception.
- [4] Certain paid plans include exception analytics covering issues such as delays, damage, returns to sender, and loss.

### UX interpretation (not validated)

AfterShip already provides substantial missing-delivery and shipment-exception management capabilities. SellerPilot cannot claim that detecting exceptions, grouping cases, or supporting refund and reship actions is a unique product opportunity.

### Research gaps

- How does AfterShip handle a buyer's missing-package report when carrier tracking says Delivered?
- How does it explain conflicting evidence and uncertainty to merchants?
- How do smaller merchants evaluate the complexity and cost of these tools?
- Which decisions require merchant approval, and how clearly are they explained?

### Potential design direction (hypothesis only)

Investigate whether a more focused experience for interpreting conflicting delivery evidence and explaining resolution options would be valuable to small merchants. No unmet need has yet been verified.

### Limitations

This is a documentation review, not hands-on testing. Capabilities vary by plan, platform, configuration, and permissions. Absence from reviewed documentation does not prove a feature is unavailable.

### Status

Official capability review completed. Differentiation and usability gaps remain unverified.




## Competitor Research Conclusions

### 1. Research Summary

This secondary research reviewed three existing ecommerce solutions:

- C01: Shopify Native Tools
- C02: Gorgias Ecommerce Helpdesk
- C03: AfterShip Tracking

The purpose was to understand existing capabilities before defining SellerPilot's product direction.

### 2. Key Findings

**Finding 1: Core ecommerce support capabilities already exist.**

Shopify supports order management, customer communication, shipment information, and refunds. Gorgias adds integrated support workflows and configurable AI actions. AfterShip provides shipment tracking and exception management.

Evidence: C01, C02, C03.

**Finding 2: AI automation alone is not a meaningful differentiator.**

Gorgias and AfterShip already document AI-assisted workflows. Adding AI to SellerPilot would require a specific user benefit, appropriate safeguards, and a clear explanation of why automation is necessary.

Evidence: C02, C03.

**Finding 3: Conflicting delivery information is worth investigating further.**

A seller-reported case in E03 describes a shipment marked delivered while the buyer reported it missing. The competitor documentation reviewed so far does not establish whether existing products adequately support this specific situation.

Evidence: E03, C01, C02, C03.

This does not prove that a product gap exists.

### 3. Potential Product Direction

Investigate a focused missing-delivery decision-support experience for small ecommerce merchants.

Possible areas of investigation include:

- Understanding contradictory shipment information.
- Organizing evidence from customers and carriers.
- Explaining available resolution options.
- Supporting merchant review before consequential actions.

These are research hypotheses, not confirmed requirements or committed features.

### 4. What We Will Not Assume

- That existing tools are inadequate.
- That missing-delivery disputes are a frequent problem for all small merchants.
- That merchants need another dashboard.
- That AI is necessary.
- That seller needs are more important than buyer needs.

### 5. Remaining Research Questions

1. Who experiences the greatest difficulty during missing-delivery resolution: buyers, sellers, or support agents?
2. Which specific decisions create uncertainty?
3. How do existing tools handle conflicting tracking information?
4. What information is needed before a refund, replacement, or claim decision?
5. Can a simpler workflow solve the problem without AI?

### 6. Research Limitations

This analysis is based on official product documentation and a small number of self-reported public experiences.

We have not conducted primary interviews, observed merchant workflows, or completed hands-on competitor usability testing.

The research identifies promising questions for further investigation but does not validate product-market need.

### 7. Next Research Activity

Develop a preliminary missing-delivery service journey that maps buyer, merchant, platform, and carrier interactions.

Use E01–E05 and C01–C03 to distinguish documented steps from inferred friction points.

### Source Traceability

Original source URLs, publication details where available, evidence observations, and limitations are recorded in:

- secondary-research.md (E01–E05)
- competitor-analysis.md (C01–C03)

