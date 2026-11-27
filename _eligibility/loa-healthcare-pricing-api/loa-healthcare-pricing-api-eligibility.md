---
api_specs:
- filename: loa-healthcare-pricing-api-entities-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entities API
  slug: loa-healthcare-pricing-api-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entities-api-openapi.yml
- filename: loa-healthcare-pricing-api-entity-analytics-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entity Analytics API
  slug: loa-healthcare-pricing-api-entity-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entity-analytics-api-openapi.yml
- filename: loa-healthcare-pricing-api-entity-updates-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entity Updates API
  slug: loa-healthcare-pricing-api-entity-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entity-updates-api-openapi.yml
- filename: loa-healthcare-pricing-api-prices-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Prices API
  slug: loa-healthcare-pricing-api-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-prices-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Healthcare data and services cover the United States. Other Services are offered only in the United States.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live) and legally able to enter a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: No patient-identifying data in MCP tools
    text: Use these tools for procedure and location searches, not for sending medical records, insurance member IDs, or other patient-identifying details.
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
name: Loa Healthcare Pricing API
provenance_date: '2026-11-09'
provider_name: Loa Healthcare Pricing API
provider_slug: loa-healthcare-pricing-api
slug: loa-healthcare-pricing-api-eligibility
source_date: '2026-11-09'
source_filename: loa-healthcare-pricing-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.loacare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loa Healthcare Pricing API\naid: loa-healthcare-pricing-api\nurl: https://www.loacare.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Healthcare data and services cover the United States. Other Services are offered only in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live) and legally able to enter a contract.\nrestricted_uses:\n- summary: No patient-identifying data in MCP tools\n  text: Use these tools for procedure and location searches, not for sending medical records, insurance\
  \ member IDs,\n    or other patient-identifying details.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/loa-healthcare-pricing-api/eligibility/loa-healthcare-pricing-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Loa Healthcare Pricing API's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Price Transparency
- medical pricing
- Hospitals
- Providers
- Provider Directory
- hospital prices
- CPT
- HCPCS
- MCP
- Agent-Native
- OpenAPI
- Llms.txt
---
