---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: apply to all consumer purchases by You of any model of electric bike (“ebike(s)”) and/or related accessories or other products offered by RLM branded with the “Rad Power Bikes” mark (collectively with ebikes, the “Products”) in the United States only.
  entity_types:
  - text: apply to all consumer purchases by You
    type: individual
  minimum_age:
    text: You represent and warrant that You are at least 16 years of age or the age of legal majority in Your jurisdiction (the “Minimum Age”), whichever is higher.
    value: '16'
  restricted_uses:
  - summary: Electric component modification
    text: RLM prohibits any such modification under any circumstances.
  - summary: Operation by minors
    text: RLM’s EBIKES ARE NOT TO BE OPERATED BY ANYONE UNDER THE AGE OF 16.
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
name: Rad Power Bikes
provenance_date: '2026-11-10'
provider_name: Rad Power Bikes
provider_slug: rad-power-bikes
slug: rad-power-bikes-eligibility
source_date: '2026-11-10'
source_filename: rad-power-bikes-eligibility.yml
source_heading: Eligibility
source_page: https://www.radpowerbikes.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rad Power Bikes\naid: rad-power-bikes\nurl: https://www.radpowerbikes.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: apply to all consumer purchases by You of any model of electric bike (“ebike(s)”) and/or related accessories\n    or other products offered by RLM branded with the “Rad Power Bikes” mark (collectively with ebikes, the “Products”)\n    in the United States only.\nentity_types:\n- type: individual\n  text: apply to all consumer purchases by You\nrestricted_uses:\n- summary: Electric component modification\n  text: RLM prohibits any\
  \ such modification under any circumstances.\n- summary: Operation by minors\n  text: RLM’s EBIKES ARE NOT TO BE OPERATED BY ANYONE UNDER THE AGE OF 16.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent and warrant that You are at least 16 years of age or the age of legal majority in Your jurisdiction\n    (the “Minimum Age”), whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/rad-power-bikes/eligibility/rad-power-bikes-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rad Power Bikes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electric Bikes
- Micromobility
- E-Commerce
- Retail
- Consumer Products
- Agentic Commerce
- Shopify
- MCP
- Universal Commerce Protocol
---
