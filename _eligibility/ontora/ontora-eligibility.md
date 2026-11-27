---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  - text: If you are using the Service on behalf of a company or other entity, you represent that you have authority to bind that entity, and “you” refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract.
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
name: Ontora
provenance_date: '2026-11-10'
provider_name: Ontora
provider_slug: ontora
slug: ontora-eligibility
source_date: '2026-11-10'
source_filename: ontora-eligibility.yml
source_heading: Eligibility
source_page: https://ontora.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ontora\naid: ontora\nurl: https://ontora.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\n- type: business\n  text: If you are using the Service on behalf of a company or other entity, you represent that you have authority\n    to bind that entity, and “you” refers to that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/ontora/eligibility/ontora-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ontora's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Operational Intelligence
- Process Discovery
- Enterprise
- Automation
- Y Combinator
---
