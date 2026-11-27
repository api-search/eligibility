---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Leta Application can only be obtained by individuals above 18 years of age.
    type: individual
  minimum_age:
    text: The Leta Application can only be obtained by individuals above 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Unless otherwise agreed by Leta in a separate written agreement with you, the Services are made available solely for your personal, non-commercial use.
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
name: Leta
provenance_date: '2026-11-09'
provider_name: Leta
provider_slug: leta
slug: leta-eligibility
source_date: '2026-11-09'
source_filename: leta-eligibility.yml
source_heading: Eligibility
source_page: https://leta.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leta\naid: leta\nurl: https://leta.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Leta Application can only be obtained by individuals above 18 years of age.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Unless otherwise agreed by Leta in a separate written agreement with you, the Services are made available\n    solely for your personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ The Leta Application can only be obtained by individuals above 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/leta/eligibility/leta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Leta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Last Mile Delivery
- Supply Chain
- Route Optimization
- Fleet Management
- Transportation
- Artificial Intelligence
- Africa
- Software-as-a-Service
---
