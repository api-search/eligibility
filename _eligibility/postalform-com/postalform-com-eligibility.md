---
api_specs:
- filename: postalform-com-api-keys-api-openapi.yml
  format: yaml
  label: PostalForm Api Keys API
  slug: postalform-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-api-keys-api-openapi.yml
- filename: postalform-com-credits-api-openapi.yml
  format: yaml
  label: PostalForm Credits API
  slug: postalform-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-credits-api-openapi.yml
- filename: postalform-com-documents-api-openapi.yml
  format: yaml
  label: PostalForm Documents API
  slug: postalform-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-documents-api-openapi.yml
- filename: postalform-com-letters-api-openapi.yml
  format: yaml
  label: PostalForm Letters API
  slug: postalform-com-letters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-letters-api-openapi.yml
- filename: postalform-com-machine-api-openapi.yml
  format: yaml
  label: PostalForm Machine API
  slug: postalform-com-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-machine-api-openapi.yml
- filename: postalform-com-postcards-api-openapi.yml
  format: yaml
  label: PostalForm Postcards API
  slug: postalform-com-postcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-postcards-api-openapi.yml
- filename: postalform-com-return-receipts-api-openapi.yml
  format: yaml
  label: PostalForm Return Receipts API
  slug: postalform-com-return-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-return-receipts-api-openapi.yml
- filename: postalform-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: PostalForm Webhook Endpoints API
  slug: postalform-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-webhook-endpoints-api-openapi.yml
- filename: postalform-com-webhook-events-api-openapi.yml
  format: yaml
  label: PostalForm Webhook Events API
  slug: postalform-com-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-webhook-events-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: PostalForm currently provides service for U.S. delivery only .
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding agreement.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Illegal, harmful, abusive or deceptive content
    text: You may not use the Service for illegal, harmful, abusive, deceptive, or prohibited content or conduct.
  - source: https://postalform.com/acceptable-use
    summary: Regulated or restricted goods
    text: Attempts to use PostalForm to ship, advertise, procure, or facilitate illegal drugs, weapons, hazardous materials, counterfeit goods, or other restricted items.
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
name: PostalForm
provenance_date: '2026-11-10'
provider_name: PostalForm
provider_slug: postalform-com
slug: postalform-com-eligibility
source_date: '2026-11-10'
source_filename: postalform-com-eligibility.yml
source_heading: Eligibility
source_page: https://postalform.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PostalForm\naid: postalform-com\nurl: https://postalform.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://postalform.com/acceptable-use\n  - https://postalform.com/terms\ncountries:\n  served:\n  - US\n  excluded: []\n  text: PostalForm currently provides service for U.S. delivery only .\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding agreement.\nrestricted_uses:\n- summary: Illegal, harmful, abusive or deceptive content\n  text: You may not use the Service for illegal, harmful, abusive, deceptive, or prohibited content or conduct.\n\
  - summary: Regulated or restricted goods\n  text: Attempts to use PostalForm to ship, advertise, procure, or facilitate illegal drugs, weapons, hazardous\n    materials, counterfeit goods, or other restricted items.\n  source: https://postalform.com/acceptable-use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/postalform-com/eligibility/postalform-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from PostalForm's own page on 2026-11-10.
synthetic: false
tags:
- Physical Mail
- Print & Mail
- Postal Mail
- Certified Mail
- Documents
- Agents
- Agentic Commerce
- MCP
- A2A
- x402
- Machine Payments
- Webhook
- Agent-Native
- United States
---
