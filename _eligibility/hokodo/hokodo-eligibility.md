---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide business-to-business insurance
    type: business
  minimum_age:
    text: null
    value: null
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
name: Hokodo
provenance_date: '2026-11-09'
provider_name: Hokodo
provider_slug: hokodo
slug: hokodo-eligibility
source_date: '2026-11-09'
source_filename: hokodo-eligibility.yml
source_heading: Eligibility
source_page: https://static.hokodo.co/shared/hokodotermsandconditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hokodo\naid: hokodo\nurl: https://static.hokodo.co/shared/hokodotermsandconditions.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We provide business-to-business insurance\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hokodo/eligibility/hokodo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Hokodo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- B2B Payments
- Buy Now Pay Later
- Trade Credit
- Embedded Finance
- Invoice Financing
- Payments API
---
