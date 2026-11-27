---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services as an individual for personal purposes, you may opt out of arbitration by emailing support@zinc.com within 30 days of first accepting these Terms.
    type: individual
  - text: If you use the Services on behalf of an organization, you agree to these Terms on its behalf and confirm that you have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal, unsafe, or restricted products
    text: You may not use the Services to buy illegal, unsafe, or restricted products;
  - summary: Sanctioned persons or places
    text: or to purchase for or ship to any person, entity, or place subject to sanctions.
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
name: Zinc
provenance_date: '2026-11-10'
provider_name: Zinc
provider_slug: zinc-com
slug: zinc-com-eligibility
source_date: '2026-11-10'
source_filename: zinc-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.zinc.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zinc\naid: zinc-com\nurl: https://www.zinc.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use the Services as an individual for personal purposes, you may opt out of arbitration by emailing\n    support@zinc.com within 30 days of first accepting these Terms.\n- type: business\n  text: If you use the Services on behalf of an organization, you agree to these Terms on its behalf and confirm\n    that you have authority to do so.\nrestricted_uses:\n- summary: Illegal, unsafe, or restricted products\n  text: You\
  \ may not use the Services to buy illegal, unsafe, or restricted products;\n- summary: Sanctioned persons or places\n  text: or to purchase for or ship to any person, entity, or place subject to sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/zinc-com/eligibility/zinc-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Zinc's own page on 2026-11-10.
synthetic: false
tags:
- E‑commerce API
- Product Search
- Order Automation
- Retail Integration
- Procurement
---
