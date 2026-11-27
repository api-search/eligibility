---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Site or the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site or the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: 'When you use the Site or Services, you may not: violate any law or regulation;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may suspend or terminate your account and your ability to use the Services if you engage in, encourage, or advocate for illegal conduct or if you fail to comply with these Terms or any Additional Terms (defined below).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evertas
provenance_date: '2026-11-09'
provider_name: Evertas
provider_slug: evertas
slug: evertas-eligibility
source_date: '2026-11-09'
source_filename: evertas-eligibility.yml
source_heading: Eligibility
source_page: https://evertas.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evertas\naid: evertas\nurl: https://evertas.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site or the Services.\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: 'When you use the Site or Services, you may not: violate any law or regulation;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may suspend or terminate your account and your ability to use the Services if you engage in, encourage,\n    or advocate\
  \ for illegal conduct or if you fail to comply with these Terms or any Additional Terms (defined below).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site or the Services.\n"
source_yaml_url: https://artifacts.apis.io/evertas/eligibility/evertas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Evertas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Cryptocurrency
- Digital Assets
- Risk Management
- Underwriting
- Financial Services
- Blockchain
---
