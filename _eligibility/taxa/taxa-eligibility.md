---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years of age and have the legal capacity to enter into a binding contract to use the Site or register for a waitlist.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the Site for any unlawful or fraudulent purpose
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
name: Taxa
provenance_date: '2026-11-10'
provider_name: Taxa
provider_slug: taxa
slug: taxa-eligibility
source_date: '2026-11-10'
source_filename: taxa-eligibility.yml
source_heading: Eligibility
source_page: https://www.taxatech.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Taxa\naid: taxa\nurl: https://www.taxatech.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age and have the legal capacity to enter into a binding contract\n    to use the Site or register for a waitlist.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Site for any unlawful or fraudulent purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years\
  \ of age\n"
source_yaml_url: https://artifacts.apis.io/taxa/eligibility/taxa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Taxa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier
- Biotechnology
- Synthetic Biology
- Microbiome
- Skincare
- Consumer Health
- Probiotics
- Deodorant
---
