---
api_specs:
- filename: mintlify-agent-api-openapi.yml
  format: yaml
  label: Mintlify Agent API
  slug: mintlify-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-agent-api-openapi.yml
- filename: mintlify-analytics-api-openapi.yml
  format: yaml
  label: Mintlify Analytics API
  slug: mintlify-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-analytics-api-openapi.yml
- filename: mintlify-assistant-api-openapi.yml
  format: yaml
  label: Mintlify Assistant API
  slug: mintlify-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-assistant-api-openapi.yml
- filename: mintlify-update-api-openapi.yml
  format: yaml
  label: Mintlify Update API
  slug: mintlify-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-update-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Mintlify Pro plan (the "Pro Plan") is intended for individuals and small teams.
    type: individual
  - text: Customer may access and use the Pro Plan only if Customer's organization has one hundred (100) or fewer total personnel, including employees, contractors, and other workers
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Pro Plan size limit
    text: Customer may access and use the Pro Plan only if Customer's organization has one hundred (100) or fewer total personnel
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
name: Mintlify
provenance_date: '2026-11-10'
provider_name: Mintlify
provider_slug: mintlify
slug: mintlify-eligibility
source_date: '2026-11-10'
source_filename: mintlify-eligibility.yml
source_heading: Eligibility
source_page: https://www.mintlify.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mintlify\naid: mintlify\nurl: https://www.mintlify.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Mintlify Pro plan (the \"Pro Plan\") is intended for individuals and small teams.\n- type: business\n  text: Customer may access and use the Pro Plan only if Customer's organization has one hundred (100) or fewer\n    total personnel, including employees, contractors, and other workers\nrestricted_uses:\n- summary: Pro Plan size limit\n  text: Customer may access and use the Pro Plan only if Customer's organization\
  \ has one hundred (100) or fewer\n    total personnel\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mintlify/eligibility/mintlify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mintlify's own page on 2026-11-10.
synthetic: false
tags:
- Documentation
- API Documentation
- Developer Portal
- MCP
- AI Assistant
- Docs as Code
---
