---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to the terms and conditions of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use only in compliance with law
    text: You represent, covenant, and warrant that you will use the Service only in compliance with all applicable laws and regulations.
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
name: Retail Zipline
provenance_date: '2026-11-10'
provider_name: Retail Zipline
provider_slug: retail-zipline
slug: retail-zipline-eligibility
source_date: '2026-11-10'
source_filename: retail-zipline-eligibility.yml
source_heading: Eligibility
source_page: https://getzipline.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Retail Zipline\naid: retail-zipline\nurl: https://getzipline.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity to the terms and conditions of this Agreement.\nrestricted_uses:\n- summary: Use only in compliance with law\n  text: You represent, covenant, and warrant that you will use the Service only in compliance with all applicable\n    laws and regulations.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/retail-zipline/eligibility/retail-zipline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Retail Zipline's own page on 2026-11-10.
synthetic: false
tags:
- Retail
- Retail Operations
- Task Management
- Employee Communications
- Store Operations
- Workforce
- Knowledge Base
- Software-as-a-Service
- MCP
- Company
---
