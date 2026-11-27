---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any natural person or legal entity that creates an account or uses the Service.
    type: individual
  - text: Businesses acting on behalf of a legal entity confirm they have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful content
    text: You must not use the Service to process, transmit, or store unlawful content, personal data without appropriate legal basis, or content that infringes third-party intellectual property rights.
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
name: mcpgatepro-com
provenance_date: '2026-11-10'
provider_name: mcpgatepro-com
provider_slug: mcpgatepro-com
slug: mcpgatepro-com-eligibility
source_date: '2026-11-10'
source_filename: mcpgatepro-com-eligibility.yml
source_heading: Eligibility
source_page: https://mcpgatepro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mcpgatepro-com\naid: mcpgatepro-com\nurl: https://mcpgatepro.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any natural person or legal entity that creates an account or uses the Service.\n- type: business\n  text: Businesses acting on behalf of a legal entity confirm they have authority to bind that entity.\nrestricted_uses:\n- summary: Unlawful content\n  text: You must not use the Service to process, transmit, or store unlawful content, personal data without appropriate\n    legal basis, or content that infringes third-party\
  \ intellectual property rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/mcpgatepro-com/eligibility/mcpgatepro-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from mcpgatepro-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cloud
- Cost Management
- Database
- Monitoring
---
