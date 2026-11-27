---
api_specs:
- filename: turquoise-health-consumer-pricing-api-openapi.yml
  format: yaml
  label: Turquoise Health Consumer Pricing API
  slug: turquoise-health-consumer-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turquoise-health/openapi/turquoise-health-consumer-pricing-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: TO CERTAIN HEALTHCARE PROVIDERS AND PAYERS THAT HAVE MADE AVAILABLE TO TURQUOISE CERTIFIED ELECTIVE PROCEDURE DATA
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY
    value: legal age
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
name: Turquoise Health
provenance_date: '2026-11-10'
provider_name: Turquoise Health
provider_slug: turquoise-health
slug: turquoise-health-eligibility
source_date: '2026-11-10'
source_filename: turquoise-health-eligibility.yml
source_heading: Eligibility
source_page: https://turquoise.health/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Turquoise Health\naid: turquoise-health\nurl: https://turquoise.health/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: TO CERTAIN HEALTHCARE PROVIDERS AND PAYERS THAT HAVE MADE AVAILABLE TO TURQUOISE CERTIFIED ELECTIVE PROCEDURE\n    DATA\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY\n"
source_yaml_url: https://artifacts.apis.io/turquoise-health/eligibility/turquoise-health-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Turquoise Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Price Transparency
- Hospital Rates
- Payer Rates
- Machine-Readable Files
- FHIR
- Health Insurance
- Negotiated Rates
- Out-of-Pocket Costs
- MRF
- Consumer Pricing
- MCP
- Eligibility
- Standard Service Packages
- HIPAA
---
