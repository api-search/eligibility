---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be over the age of eighteen (18) years and able to understand and agree to the terms, conditions, obligations, representations, and warranties set forth in these Terms.
    type: individual
  minimum_age:
    text: You must be over the age of eighteen (18) years
    value: '18'
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
name: Delhivery
provenance_date: '2026-11-09'
provider_name: Delhivery
provider_slug: delhivery
slug: delhivery-eligibility
source_date: '2026-11-09'
source_filename: delhivery-eligibility.yml
source_heading: Eligibility
source_page: https://www.delhivery.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delhivery\naid: delhivery\nurl: https://www.delhivery.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be over the age of eighteen (18) years and able to understand and agree to the terms, conditions,\n    obligations, representations, and warranties set forth in these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over the age of eighteen (18) years\n"
source_yaml_url: https://artifacts.apis.io/delhivery/eligibility/delhivery-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Delhivery's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Supply Chain
- Freight
- E-Commerce
- Tracking
- Fulfillment
- India
---
