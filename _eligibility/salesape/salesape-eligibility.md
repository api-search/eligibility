---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The person or entity identified in the Product Portal or Order Form intending to utilise the Provider's Services (defined below) for its business operations (the “Client”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or infringing material
    text: use the Services to store or transmit any infringing, harmful, abusive, or illegal material, including Viruses
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
name: Salesape
provenance_date: '2026-11-10'
provider_name: Salesape
provider_slug: salesape
slug: salesape-eligibility
source_date: '2026-11-10'
source_filename: salesape-eligibility.yml
source_heading: Eligibility
source_page: https://www.salesape.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salesape\naid: salesape\nurl: https://www.salesape.ai/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The person or entity identified in the Product Portal or Order Form intending to utilise the Provider's\n    Services (defined below) for its business operations (the “Client”)\nrestricted_uses:\n- summary: No illegal or infringing material\n  text: use the Services to store or transmit any infringing, harmful, abusive, or illegal material, including Viruses\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/salesape/eligibility/salesape-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Salesape's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Artificial Intelligence
- Sales
- Lead Qualification
- AI Agents
- CRM
- Conversational AI
---
