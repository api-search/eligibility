---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Lifetime Subscriptions are only available for shipment to a United States address.
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Elysium Health and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: No resale of products
    text: The products available on the Site, and any samples thereof we may provide to you, are for personal use only.
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
name: Elysium Health
provenance_date: '2026-11-09'
provider_name: Elysium Health
provider_slug: elysium
slug: elysium-eligibility
source_date: '2026-11-09'
source_filename: elysium-eligibility.yml
source_heading: Eligibility
source_page: https://www.elysiumhealth.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elysium Health\naid: elysium\nurl: https://www.elysiumhealth.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Lifetime Subscriptions are only available for shipment to a United States address.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Elysium Health and are not barred from using the Services under applicable law.\nrestricted_uses:\n- summary: No resale of products\n  text: The products available on the Site, and any samples thereof we\
  \ may provide to you, are for personal use\n    only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/elysium/eligibility/elysium-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Elysium Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Longevity
- Supplements
- Consumer Health
- Diagnostics
- Agentic Commerce
- Universal Commerce Protocol
- Shopify
- E-Commerce
- MCP
---
