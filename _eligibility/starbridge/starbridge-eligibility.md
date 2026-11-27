---
api_specs:
- filename: starbridge-bridges-api-openapi.yml
  format: yaml
  label: Starbridge Bridges API
  slug: starbridge-bridges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-bridges-api-openapi.yml
- filename: starbridge-buyer-api-openapi.yml
  format: yaml
  label: Starbridge Buyer API
  slug: starbridge-buyer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-buyer-api-openapi.yml
- filename: starbridge-columns-api-openapi.yml
  format: yaml
  label: Starbridge Columns API
  slug: starbridge-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-columns-api-openapi.yml
- filename: starbridge-external-mcp-api-openapi.yml
  format: yaml
  label: Starbridge External MCP API
  slug: starbridge-external-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-external-mcp-api-openapi.yml
- filename: starbridge-signal-api-openapi.yml
  format: yaml
  label: Starbridge Signal API
  slug: starbridge-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-signal-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services will only be accessed by an employee within Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Email outreach limits
    text: Customer shall use any email-sending functionality of the Services only in compliance with the CAN-SPAM Act
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
name: Starbridge
provenance_date: '2026-11-10'
provider_name: Starbridge
provider_slug: starbridge
slug: starbridge-eligibility
source_date: '2026-11-10'
source_filename: starbridge-eligibility.yml
source_heading: Eligibility
source_page: https://starbridge.ai/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Starbridge\naid: starbridge\nurl: https://starbridge.ai/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services will only be accessed by an employee within Customer\nrestricted_uses:\n- summary: Email outreach limits\n  text: Customer shall use any email-sending functionality of the Services only in compliance with the CAN-SPAM\n    Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/starbridge/eligibility/starbridge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Starbridge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales Intelligence
- Go-To-Market
- Public Sector
- Education
- Government
- Procurement
- Buyer Intelligence
- MCP
- A2A
---
