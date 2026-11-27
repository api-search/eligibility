---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” and “your” mean the customer or prospective customer using our services.
    type: individual
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
name: Trussle
provenance_date: '2026-11-10'
provider_name: Trussle
provider_slug: trussle-com
slug: trussle-com-eligibility
source_date: '2026-11-10'
source_filename: trussle-com-eligibility.yml
source_heading: Eligibility
source_page: https://better.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trussle\naid: trussle-com\nurl: https://better.co.uk/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” and “your” mean the customer or prospective customer using our services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trussle-com/eligibility/trussle-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Trussle's own page on 2026-11-10.
synthetic: false
tags:
- Mortgage
- Fintech
- United Kingdom
- Brokerage
- Digital
---
