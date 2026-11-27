---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms of Use only apply to visitors to our Site or consumers who reside in the United States. If you are a consumer resident outside of the U.S., these Terms of Use do not apply to you .
  entity_types:
  - text: YOU ARE OF LEGAL AGE UNDER APPLICABLE LAW TO FORM A BINDING CONTRACT WITH FIGS
    type: individual
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THESE TERMS OF USE PERSONALLY OR ON BEHALF OF THE COMPANY YOU HAVE NAMED AS THE USER OF THE SERVICES
    type: business
  minimum_age:
    text: We assume that because Orders require a valid credit card, only persons age 18 or over are placing Orders
    value: '18'
  restricted_uses:
  - summary: No resale of products
    text: any resale of Products for personal and/or business profit is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require additional verifications or information before accepting any Order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FIGS
provenance_date: '2026-11-09'
provider_name: FIGS
provider_slug: figs
slug: figs-eligibility
source_date: '2026-11-09'
source_filename: figs-eligibility.yml
source_heading: Eligibility
source_page: https://www.wearfigs.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FIGS\naid: figs\nurl: https://www.wearfigs.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms of Use only apply to visitors to our Site or consumers who reside in the United States. If you\n    are a consumer resident outside of the U.S., these Terms of Use do not apply to you .\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE UNDER APPLICABLE LAW TO FORM A BINDING CONTRACT WITH FIGS\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THESE TERMS OF USE PERSONALLY OR ON BEHALF OF THE COMPANY YOU HAVE\n\
  \    NAMED AS THE USER OF THE SERVICES\nrestricted_uses:\n- summary: No resale of products\n  text: any resale of Products for personal and/or business profit is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require additional verifications or information before accepting any Order.\nminimum_age:\n  value: '18'\n  text: We assume that because Orders require a valid credit card, only persons age 18 or over are placing Orders\n"
source_yaml_url: https://artifacts.apis.io/figs/eligibility/figs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from FIGS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Apparel
- Medical
- E-Commerce
- Direct to Consumer
- Retail
- Consumer Goods
---
