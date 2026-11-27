---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We help individuals and businesses obtain commercial and personal lines coverage through admitted and non-admitted carriers.
    type: individual
  - text: We help individuals and businesses obtain commercial and personal lines coverage through admitted and non-admitted carriers.
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
name: Menlo Insurance Services
provenance_date: '2026-11-10'
provider_name: Menlo Insurance Services
provider_slug: menloinsurance
slug: menloinsurance-eligibility
source_date: '2026-11-10'
source_filename: menloinsurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.menloinsurance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Menlo Insurance Services\naid: menloinsurance\nurl: https://www.menloinsurance.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We help individuals and businesses obtain commercial and personal lines coverage through admitted and non-admitted\n    carriers.\n- type: business\n  text: We help individuals and businesses obtain commercial and personal lines coverage through admitted and non-admitted\n    carriers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/menloinsurance/eligibility/menloinsurance-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Menlo Insurance Services's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Brokerage
- Commercial
- Personal
- Quotes
---
