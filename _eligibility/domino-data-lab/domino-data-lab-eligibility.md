---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: You must be 13 years or older to use this Service.
    value: '13'
  restricted_uses:
  - summary: Direct competitors
    text: You may not use this Service if you are a direct competitor, except with Domino’s prior written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Domino Data Lab
provenance_date: '2026-11-09'
provider_name: Domino Data Lab
provider_slug: domino-data-lab
slug: domino-data-lab-eligibility
source_date: '2026-11-09'
source_filename: domino-data-lab-eligibility.yml
source_heading: Eligibility
source_page: https://domino.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Domino Data Lab\naid: domino-data-lab\nurl: https://domino.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Direct competitors\n  text: You may not use this Service if you are a direct competitor, except with Domino’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process.\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/domino-data-lab/eligibility/domino-data-lab-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Domino Data Lab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MLOps
- Data Science
- Machine Learning
- AI Platform
- Model Monitoring
- Enterprise AI
---
