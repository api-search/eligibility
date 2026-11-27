---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms or accessing or using Platform on behalf of an entity, you represent and warrant that you have the authority to bind such entity to these Terms
    type: business
  - text: The System is available only to users who have registered a developer account on our platform and who have passed our required identity and qualification verifications
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI Q&A high-risk decisions
    text: Using the System as the sole basis for high risk decisions directly applicable to medicine, law, finance, etc.
  - summary: AI Q&A intended scenarios only
    text: Any use beyond the foregoing purposes that is not expressly authorized by us in writing shall be deemed unauthorized.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SHEIN
provenance_date: '2026-11-10'
provider_name: SHEIN
provider_slug: shein
slug: shein-eligibility
source_date: '2026-11-10'
source_filename: shein-eligibility.yml
source_heading: Eligibility
source_page: https://open.sheincorp.com/contract
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SHEIN\naid: shein\nurl: https://open.sheincorp.com/contract\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms or accessing or using Platform on behalf of an entity, you represent and\n    warrant that you have the authority to bind such entity to these Terms\n- type: developer\n  text: The System is available only to users who have registered a developer account on our platform and who have\n    passed our required identity and qualification verifications\nrestricted_uses:\n- summary: AI Q&A high-risk decisions\n\
  \  text: Using the System as the sole basis for high risk decisions directly applicable to medicine, law, finance,\n    etc.\n- summary: AI Q&A intended scenarios only\n  text: Any use beyond the foregoing purposes that is not expressly authorized by us in writing shall be deemed\n    unauthorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shein/eligibility/shein-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SHEIN's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Fashion
- Marketplace
- Fulfillment
- Logistics
- Open Platform
- Sellers
---
