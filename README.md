# Cardinal Health (cardinal-health)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cardinal Health is a Fortune 15 global integrated healthcare services and products company that provides pharmaceutical distribution, medical-surgical product distribution, and customized solutions for hospitals, health systems, pharmacies, ambulatory surgery centers, clinical laboratories, and physician offices. Cardinal Health does not publish a public developer portal, but it exchanges high volumes of B2B trading data with customers and suppliers via standard X12 EDI transactions (850, 810, 855, 856, 846, 832, 867) over AS2, SFTP, and private API channels. Third-party EDI platforms such as Orderful, Crossfire, SPS Commerce, Zenbridge, DataTrans, Alluvia, ConnectPointz, and Spark Shipping offer managed connectors into Cardinal Health for order-to-cash, inventory, and supply-chain automation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cardinal-health/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consumer
- **Access:** Partner

## Tags

- B2B
- Distribution
- EDI
- Healthcare
- Medical-Surgical
- Order-to-Cash
- Pharmaceutical
- Supply Chain
- Trading Partner

## Overview

Cardinal Health operates two primary segments - Pharmaceutical & Specialty Solutions and Global Medical Products & Distribution - serving roughly 90% of U.S. hospitals and tens of thousands of outpatient, retail, and laboratory customers. Because the business runs on very large transaction volumes with healthcare providers, manufacturers, and GPOs, Cardinal Health integrates through the X12 EDI standard rather than a public REST API. Trading partners exchange purchase orders (EDI 850), acknowledgments (855), advance ship notices (856), invoices (810), inventory inquiries (846), product catalogs (832), and product activity data (867) over AS2, SFTP, and API-fronted EDI. Onboarding is coordinated with Cardinal Health's trading partner team, and most managed integrations go live within six to ten weeks.

## APIs

### Cardinal Health EDI Trading Partner Integration
Cardinal Health operates an EDI trading partner program for customers and suppliers covering pharmaceutical distribution, medical products, and specialty pharmacy. Integrations use X12 EDI transactions including 850 Purchase Order, 810 Invoice, 855 PO Acknowledgment, 856 Advance Ship Notice, 846 Inventory Inquiry, 832 Price/Sales Catalog, and 867 Product Activity Data. Connectivity is offered through AS2, SFTP, and API-fronted EDI through managed integrators. Onboarding is coordinated with Cardinal Health trading partner teams and typically spans six to ten weeks including mapping and conformance testing.

**Human URL:** [https://www.cardinalhealth.com/en/services.html](https://www.cardinalhealth.com/en/services.html)

#### Features

- Purchase orders (EDI 850) and acknowledgments (EDI 855)
- Invoicing (EDI 810) and advance ship notices (EDI 856)
- Inventory inquiry (EDI 846) and product activity (EDI 867)
- Price and sales catalog exchange (EDI 832)
- AS2, SFTP, and API-fronted EDI connectivity
- Managed partner onboarding and conformance testing
- Support for medical-surgical and pharmaceutical segments

#### Use Cases

- Hospital and health system procurement automation
- Retail and mail-order pharmacy replenishment
- Ambulatory surgery center and physician office ordering
- Manufacturer/distributor chargeback and rebate processing
- GPO contract pricing and compliance reporting
- Drug traceability and DSCSA-related data exchange

## Common Properties

- [Website](https://www.cardinalhealth.com/)
- [Products and Services](https://www.cardinalhealth.com/en/services.html)
- [About](https://www.cardinalhealth.com/en/about-us.html)
- [Investor Relations](https://ir.cardinalhealth.com/)
- [Careers](https://www.cardinalhealth.com/en/about-us/careers.html)
- [Contact](https://www.cardinalhealth.com/en/contact-us.html)
- [Terms and Conditions](https://www.cardinalhealth.com/en/notices/terms-and-conditions.html)
- [Privacy Policy](https://www.cardinalhealth.com/en/notices/privacy-policy.html)
- [LinkedIn](https://www.linkedin.com/company/cardinal-health)
- [X](https://x.com/cardinalhealth)

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
