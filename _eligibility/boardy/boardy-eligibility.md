---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for professional advice
    text: it is not designed for nor should be used as a substitute for professional advice, including mental health or legal services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Boardy reserves the right to request proof of age from any user and to terminate or suspend accounts of users who are found to be under 18 years of age.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Boardy
provenance_date: '2026-11-09'
provider_name: Boardy
provider_slug: boardy
slug: boardy-eligibility
source_date: '2026-11-09'
source_filename: boardy-eligibility.yml
source_heading: Eligibility
source_page: https://www.boardy.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boardy\naid: boardy\nurl: https://www.boardy.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\nrestricted_uses:\n- summary: Not a substitute for professional advice\n  text: it is not designed for nor should be used as a substitute for professional advice, including mental health\n    or legal services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Boardy reserves the right to request proof of age from any user and to terminate\
  \ or suspend accounts of\n    users who are found to be under 18 years of age.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/boardy/eligibility/boardy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Boardy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Networking
- Professional Networking
- Introductions
- AI Agents
- Voice Agents
- Superconnector
---
