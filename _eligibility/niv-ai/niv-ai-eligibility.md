---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years old
    type: individual
  - text: the entity on behalf of which you are using the Website
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the Website for any unlawful purpose or for promotion or facilitation of illegal activities, including gambling
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
name: Niv-AI
provenance_date: '2026-11-10'
provider_name: Niv-AI
provider_slug: niv-ai
slug: niv-ai-eligibility
source_date: '2026-11-10'
source_filename: niv-ai-eligibility.yml
source_heading: Eligibility
source_page: https://niv-ai.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Niv-AI\naid: niv-ai\nurl: https://niv-ai.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years old\n- type: business\n  text: the entity on behalf of which you are using the Website\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the Website for any unlawful purpose or for promotion or facilitation of illegal activities, including\n    gambling\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least\
  \ 18 years old\n"
source_yaml_url: https://artifacts.apis.io/niv-ai/eligibility/niv-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Niv-AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Artificial Intelligence
- Data Center
- Sustainability
---
