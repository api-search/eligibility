---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual may access and/or use the Service on behalf of a company or other entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial solicitation
    text: use the Service for any commercial solicitation purposes
  - summary: Developing competing products
    text: to develop competing products or services
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
name: Mercor
provenance_date: '2026-11-10'
provider_name: Mercor
provider_slug: mercor
slug: mercor-eligibility
source_date: '2026-11-10'
source_filename: mercor-eligibility.yml
source_heading: Eligibility
source_page: https://www.mercor.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mercor\naid: mercor\nurl: https://www.mercor.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity\nrestricted_uses:\n- summary: Commercial solicitation\n  text: use the Service for any commercial solicitation purposes\n- summary: Developing competing products\n  text: to develop competing products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mercor/eligibility/mercor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mercor's own page on 2026-11-10.
synthetic: false
tags:
- Talent Marketplace
- Human Intelligence
- RLHF
- SFT
- AI Evals
- Data Pipeline
- APEX Benchmarks
---
