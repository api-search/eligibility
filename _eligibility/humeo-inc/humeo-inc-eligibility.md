---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Service.
    type: individual
  - text: you have the authority to enter into these Terms, including on behalf of any business you represent.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Service.
    value: '18'
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
name: Humeo
provenance_date: '2026-11-09'
provider_name: Humeo
provider_slug: humeo-inc
slug: humeo-inc-eligibility
source_date: '2026-11-09'
source_filename: humeo-inc-eligibility.yml
source_heading: Eligibility
source_page: https://humeo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Humeo\naid: humeo-inc\nurl: https://humeo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Service.\n- type: business\n  text: you have the authority to enter into these Terms, including on behalf of any business you represent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction,\
  \ to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/humeo-inc/eligibility/humeo-inc-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Humeo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Creative Intelligence
- Generative Media
- Video
- Content Creation
- Research Lab
---
