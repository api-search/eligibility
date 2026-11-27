---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You shall ensure that copies of all required documents, including but not limited to company incorporation certificate, partnership agreement, copy of PAN
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: shall be duly uploaded on the Shiplyst Website for the purpose of verification by Shiplyst.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shiplyst
provenance_date: '2026-11-10'
provider_name: Shiplyst
provider_slug: shiplyst
slug: shiplyst-eligibility
source_date: '2026-11-10'
source_filename: shiplyst-eligibility.yml
source_heading: Eligibility
source_page: https://www.shiplyst.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shiplyst\naid: shiplyst\nurl: https://www.shiplyst.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You shall ensure that copies of all required documents, including but not limited to company incorporation\n    certificate, partnership agreement, copy of PAN\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: shall be duly uploaded on the Shiplyst Website for the purpose of verification by Shiplyst.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shiplyst/eligibility/shiplyst-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Shiplyst's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Ocean Freight
- Supply Chain
- Freight Forwarding
- Container Shipping
- Cargo Tracking
- Marketplace
---
