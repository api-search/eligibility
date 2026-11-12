---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization or entity, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment or unlawful use
    text: use the Services to stalk, threaten, harass or harm another individual
  - summary: Export-controlled users
    text: you are not a prohibited end user under any applicable export control or trade compliance laws
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
name: ConnectMachine
provenance_date: '2026-11-09'
provider_name: ConnectMachine
provider_slug: connectmachine-ai
slug: connectmachine-ai-eligibility
source_date: '2026-11-09'
source_filename: connectmachine-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.connectmachine.ai/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConnectMachine\naid: connectmachine-ai\nurl: https://www.connectmachine.ai/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization or entity, you represent and warrant that you\n    have the authority to bind that organization to these Terms.\nrestricted_uses:\n- summary: Harassment or unlawful use\n  text: use the Services to stalk, threaten, harass or harm another individual\n- summary: Export-controlled users\n  text: you are not a prohibited end user under\
  \ any applicable export control or trade compliance laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/connectmachine-ai/eligibility/connectmachine-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ConnectMachine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Business Cards
- Contact Management
- Business Card Scanner
- Networking
- Artificial Intelligence
- MCP
- CRM
---
