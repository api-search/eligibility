---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are an Adult
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose nor may you, in the use of the Service, violate any laws in your jurisdiction
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
name: Bravo Sierra
provenance_date: '2026-11-09'
provider_name: Bravo Sierra
provider_slug: bravo-sierra
slug: bravo-sierra-eligibility
source_date: '2026-11-09'
source_filename: bravo-sierra-eligibility.yml
source_heading: Eligibility
source_page: https://www.bravosierra.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bravo Sierra\naid: bravo-sierra\nurl: https://www.bravosierra.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are an Adult\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose nor may you, in the use of the Service,\n    violate any laws in your jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bravo-sierra/eligibility/bravo-sierra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Bravo Sierra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Care
- Consumer Packaged Goods
- E-Commerce
- Direct to Consumer
- Beauty and Grooming
- Military and Veterans
- Made in USA
- Shopify
---
