---
api_specs:
- filename: relaystation-ai-api-openapi.json
  format: json
  label: Relaystation Api API
  slug: relaystation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relaystation-ai/openapi/_original/relaystation-ai-api-openapi.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Identity data without lawful basis
    text: Submit another person's government ID, biometric data, or other sensitive personal information for identity verification or screening without a lawful basis and, where required, that person's consent
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
name: relaystation-ai
provenance_date: '2026-11-10'
provider_name: relaystation-ai
provider_slug: relaystation-ai
slug: relaystation-ai-eligibility
source_date: '2026-11-10'
source_filename: relaystation-ai-eligibility.yml
source_heading: Eligibility
source_page: https://relaystation.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: relaystation-ai\naid: relaystation-ai\nurl: https://relaystation.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Identity data without lawful basis\n  text: Submit another person's government ID, biometric data, or other sensitive personal information for identity\n    verification or screening without a lawful basis and, where required, that person's consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/relaystation-ai/eligibility/relaystation-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from relaystation-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data-Relay
- Real-Time
- Cloud
---
