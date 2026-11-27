---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 (eighteen) years of age to use this Website or any Services contained herein.
    type: individual
  minimum_age:
    text: You must be at least 18 (eighteen) years of age to use this Website or any Services contained herein.
    value: '18'
  restricted_uses:
  - summary: Acceptable use prohibitions
    text: 'You further agree not to use the Website or Services: I) To harass, abuse, or threaten others or otherwise violate any person''s legal rights'
  - summary: No unlawful gambling or pyramid schemes
    text: To engage in or create any unlawful gambling, sweepstakes, or pyramid scheme
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
name: Landis
provenance_date: '2026-11-09'
provider_name: Landis
provider_slug: landis
slug: landis-eligibility
source_date: '2026-11-09'
source_filename: landis-eligibility.yml
source_heading: Eligibility
source_page: https://www.landis.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landis\naid: landis\nurl: https://www.landis.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 (eighteen) years of age to use this Website or any Services contained herein.\nrestricted_uses:\n- summary: Acceptable use prohibitions\n  text: 'You further agree not to use the Website or Services: I) To harass, abuse, or threaten others or otherwise\n    violate any person''s legal rights'\n- summary: No unlawful gambling or pyramid schemes\n  text: To engage in or create any unlawful gambling, sweepstakes,\
  \ or pyramid scheme\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (eighteen) years of age to use this Website or any Services contained herein.\n"
source_yaml_url: https://artifacts.apis.io/landis/eligibility/landis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Landis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Real Estate
- PropTech
- Fintech
- Mortgage
- Rent-to-Own
- Homeownership
- Housing
---
