---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and capable in your country of residence of entering into a legally binding agreement to become a Member.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age and capable in your country of residence of entering into a legally binding agreement to become a Member.
    value: '18'
  restricted_uses:
  - summary: Gift card recipients must be 18+
    text: The gift card recipient must be 18 or over.
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
name: Secret Escapes
provenance_date: '2026-11-10'
provider_name: Secret Escapes
provider_slug: secret-escapes
slug: secret-escapes-eligibility
source_date: '2026-11-10'
source_filename: secret-escapes-eligibility.yml
source_heading: Eligibility
source_page: https://www.secretescapes.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Secret Escapes\naid: secret-escapes\nurl: https://www.secretescapes.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and capable in your country of residence of entering into a legally\n    binding agreement to become a Member.\nrestricted_uses:\n- summary: Gift card recipients must be 18+\n  text: The gift card recipient must be 18 or over.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years of age and capable in your country of residence of entering into a legally\n    binding agreement to become a Member.\n"
source_yaml_url: https://artifacts.apis.io/secret-escapes/eligibility/secret-escapes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Secret Escapes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hospitality
- E-Commerce
- Membership
- Flash Sales
---
