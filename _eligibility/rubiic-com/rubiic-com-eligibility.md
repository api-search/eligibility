---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: You may use the Service on behalf of a company you represent, in which case “you” includes that company and you confirm you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Acceptable use policy
    text: The Acceptable Use Policy lists what you may not make with the Service
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
name: rubiic-com
provenance_date: '2026-11-10'
provider_name: rubiic-com
provider_slug: rubiic-com
slug: rubiic-com-eligibility
source_date: '2026-11-10'
source_filename: rubiic-com-eligibility.yml
source_heading: Eligibility
source_page: https://rubiic.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rubiic-com\naid: rubiic-com\nurl: https://rubiic.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: You may use the Service on behalf of a company you represent, in which case “you” includes that company\n    and you confirm you have authority to bind it.\nrestricted_uses:\n- summary: Acceptable use policy\n  text: The Acceptable Use Policy lists what you may not make with the Service\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/rubiic-com/eligibility/rubiic-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from rubiic-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Creative
- Video Generation
- Graphics
- Automation
- MCP
---
