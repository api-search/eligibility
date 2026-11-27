---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are located in, or are a resident or national of, any country or territory that is subject to a comprehensive U.S. Government embargo
  entity_types:
  - text: you are at least 16 years old or the age of majority in your jurisdiction, whichever is higher
    type: individual
  minimum_age:
    text: you are at least 16 years old or the age of majority in your jurisdiction, whichever is higher
    value: '16'
  restricted_uses:
  - summary: Sexually explicit or exploitative content
    text: create, upload, record, share or otherwise make available any content that is sexually explicit, exploitative or pornographic
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before you use our Services, you may be required to register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pingo AI
provenance_date: '2026-11-10'
provider_name: Pingo AI
provider_slug: pingo
slug: pingo-eligibility
source_date: '2026-11-10'
source_filename: pingo-eligibility.yml
source_heading: Eligibility
source_page: https://pingo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pingo AI\naid: pingo\nurl: https://pingo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are located in, or are a resident or national of, any country or territory that is subject to a comprehensive\n    U.S. Government embargo\nentity_types:\n- type: individual\n  text: you are at least 16 years old or the age of majority in your jurisdiction, whichever is higher\nrestricted_uses:\n- summary: Sexually explicit or exploitative content\n  text: create, upload, record, share or otherwise make available any content that is sexually explicit, exploitative\n    or pornographic\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before you use our Services, you may be required to register for an account\nminimum_age:\n  value: '16'\n  text: you are at least 16 years old or the age of majority in your jurisdiction, whichever is higher\n"
source_yaml_url: https://artifacts.apis.io/pingo/eligibility/pingo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Pingo AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Language Learning
- Education
- Conversational AI
- Mobile App
- EdTech
---
