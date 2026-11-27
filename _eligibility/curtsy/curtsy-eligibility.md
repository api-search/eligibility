---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally capable of entering into a binding contract and must provide accurate, current, and complete information.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited items
    text: 'You may not use the Services to list, sell, buy, promote, or facilitate: counterfeit goods; stolen goods;'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Curtsy may conduct onboarding review, identity verification, sanctions screening, fraud review, listing review, transaction monitoring, payout risk review, reserve analysis, and ongoing seller monitoring.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Curtsy
provenance_date: '2026-11-09'
provider_name: Curtsy
provider_slug: curtsy
slug: curtsy-eligibility
source_date: '2026-11-09'
source_filename: curtsy-eligibility.yml
source_heading: Eligibility
source_page: https://curtsyapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curtsy\naid: curtsy\nurl: https://curtsyapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally capable of entering into a binding contract and must provide accurate, current, and\n    complete information.\nrestricted_uses:\n- summary: Prohibited items\n  text: 'You may not use the Services to list, sell, buy, promote, or facilitate: counterfeit goods; stolen goods;'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Curtsy may conduct onboarding review, identity verification, sanctions\
  \ screening, fraud review, listing\n    review, transaction monitoring, payout risk review, reserve analysis, and ongoing seller monitoring.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/curtsy/eligibility/curtsy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Curtsy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Resale
- Marketplace
- Fashion
- E-Commerce
- Secondhand
- Consumer
- Mobile
---
