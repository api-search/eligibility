---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register and become a "member" of the Site, you must be at least 18 years of age to enter into and form a legally binding contract.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age to enter into and form a legally binding contract.
    value: '18'
  restricted_uses:
  - summary: Interactive areas non-commercial only
    text: You agree to use such interactive areas only for non-commercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You grant Slidebean the right to independently verify any information that you post on the Site or provide to Slidebean about yourself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Slidebean
provenance_date: '2026-11-10'
provider_name: Slidebean
provider_slug: slidebean
slug: slidebean-eligibility
source_date: '2026-11-10'
source_filename: slidebean-eligibility.yml
source_heading: Eligibility
source_page: https://slidebean.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Slidebean\naid: slidebean\nurl: https://slidebean.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register and become a \"member\" of the Site, you must be at least 18 years of age to enter into and form\n    a legally binding contract.\nrestricted_uses:\n- summary: Interactive areas non-commercial only\n  text: You agree to use such interactive areas only for non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You grant Slidebean the right to independently verify any information\
  \ that you post on the Site or provide\n    to Slidebean about yourself\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age to enter into and form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/slidebean/eligibility/slidebean-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Slidebean's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Presentation Software
- Pitch Deck
- Financial Modeling
- Startups
- Fundraising
- Software-as-a-Service
- Productivity
---
