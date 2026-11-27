---
api_specs:
- filename: eurocomply-app-mcp-tools.json
  format: json
  label: EuroComply MCP API
  slug: eurocomply-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eurocomply-app/openapi/eurocomply-app-mcp-tools.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is directed exclusively at businesses, professionals, and other legal entities acting in the course of a trade, business, or profession.
    type: business
  - text: If you are an individual acting in a personal (non-business) capacity, you must not use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or misleading use
    text: Use the Service for unlawful purposes or in violation of any applicable law or regulation
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
name: EuroComply
provenance_date: '2026-11-09'
provider_name: EuroComply
provider_slug: eurocomply-app
slug: eurocomply-app-eligibility
source_date: '2026-11-09'
source_filename: eurocomply-app-eligibility.yml
source_heading: Eligibility
source_page: https://eurocomply.app/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EuroComply\naid: eurocomply-app\nurl: https://eurocomply.app/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is directed exclusively at businesses, professionals, and other legal entities acting in the\n    course of a trade, business, or profession.\n- type: individual\n  text: If you are an individual acting in a personal (non-business) capacity, you must not use the Service.\nrestricted_uses:\n- summary: Unlawful or misleading use\n  text: Use the Service for unlawful purposes or in violation of any\
  \ applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/eurocomply-app/eligibility/eurocomply-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EuroComply's own page on 2026-11-09.
synthetic: false
tags:
- AI Act
- GDPR
- NIS2
- DORA
- RegTech
---
