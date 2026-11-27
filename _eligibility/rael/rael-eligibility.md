---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: we only ship products to directly to consumers in the United States...for now.
  entity_types:
  - text: Our Products and Services are not offered to persons under the age of 16.
    type: individual
  minimum_age:
    text: Our Products and Services are not offered to persons under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Personal non-commercial use
    text: Our Products and Services are for your personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Services to any person or entity and change our eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rael
provenance_date: '2026-11-10'
provider_name: Rael
provider_slug: rael
slug: rael-eligibility
source_date: '2026-11-10'
source_filename: rael-eligibility.yml
source_heading: Eligibility
source_page: https://www.getrael.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rael\naid: rael\nurl: https://www.getrael.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: we only ship products to directly to consumers in the United States...for now.\nentity_types:\n- type: individual\n  text: Our Products and Services are not offered to persons under the age of 16.\nrestricted_uses:\n- summary: Personal non-commercial use\n  text: Our Products and Services are for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion, refuse to offer the\
  \ Services to any person or entity and change our eligibility\n    criteria at any time.\nminimum_age:\n  value: '16'\n  text: Our Products and Services are not offered to persons under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/rael/eligibility/rael-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rael's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Consumer Goods
- Health and Wellness
- Personal Care
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Shopify
---
