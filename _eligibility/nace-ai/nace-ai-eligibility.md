---
api_specs:
- filename: nace-ai-health-api-openapi.yml
  format: yaml
  label: Nace Ai Health API
  slug: nace-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nace-ai/openapi/nace-ai-health-api-openapi.yml
- filename: nace-ai-public-api-api-openapi.yml
  format: yaml
  label: Nace Ai Public API
  slug: nace-ai-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nace-ai/openapi/nace-ai-public-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other entity (a "Customer Organization"), then "you" includes you and that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old, and of legal age to form a binding contract where you live, to use the Services.
    value: '18'
  restricted_uses:
  - summary: Fully automated significant decisions
    text: use the Services to make fully automated decisions that produce legal or similarly significant effects on individuals
  - summary: Fraud and financial crime
    text: use the Services for fraud, to facilitate money laundering or other financial crime, to deceive auditors or regulators, or to create false or misleading financial records
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
name: Nace Ai
provenance_date: '2026-11-10'
provider_name: Nace Ai
provider_slug: nace-ai
slug: nace-ai-eligibility
source_date: '2026-11-10'
source_filename: nace-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.nace.ai/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nace Ai\naid: nace-ai\nurl: https://www.nace.ai/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity (a \"Customer Organization\"), then \"you\" includes\n    you and that entity\nrestricted_uses:\n- summary: Fully automated significant decisions\n  text: use the Services to make fully automated decisions that produce legal or similarly significant effects on\n    individuals\n- summary: Fraud and financial crime\n  text: use the Services for fraud, to\
  \ facilitate money laundering or other financial crime, to deceive auditors\n    or regulators, or to create false or misleading financial records\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and of legal age to form a binding contract where you live, to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/nace-ai/eligibility/nace-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nace Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Intelligence
- Document Processing
- Data Extraction
- OCR
- Machine Learning
- Enterprise Automation
- MCP
---
