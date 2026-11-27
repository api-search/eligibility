---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a binding contract.
    type: individual
  - text: If you use the Service for an organization, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
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
name: The Trade Lab
provenance_date: '2026-11-10'
provider_name: The Trade Lab
provider_slug: the-trade-lab
slug: the-trade-lab-eligibility
source_date: '2026-11-10'
source_filename: the-trade-lab-eligibility.yml
source_heading: Eligibility
source_page: https://thetradelab.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Trade Lab\naid: the-trade-lab\nurl: https://thetradelab.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract.\n- type: business\n  text: If you use the Service for an organization, you represent that you have authority to bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/the-trade-lab/eligibility/the-trade-lab-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from The Trade Lab's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Trade Compliance
- International Trade
- Software-as-a-Service
---
