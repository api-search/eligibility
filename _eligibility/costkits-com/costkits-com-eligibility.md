---
api_specs:
- filename: costkits-com-bill-analysis-api-openapi.yml
  format: yaml
  label: CostKits Bill Analysis API
  slug: costkits-com-bill-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-bill-analysis-api-openapi.yml
- filename: costkits-com-cost-estimation-api-openapi.yml
  format: yaml
  label: CostKits Cost Estimation API
  slug: costkits-com-cost-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-cost-estimation-api-openapi.yml
- filename: costkits-com-coverage-rules-api-openapi.yml
  format: yaml
  label: CostKits Coverage Rules API
  slug: costkits-com-coverage-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-coverage-rules-api-openapi.yml
- filename: costkits-com-demo-api-openapi.yml
  format: yaml
  label: CostKits Demo API
  slug: costkits-com-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-demo-api-openapi.yml
- filename: costkits-com-procedure-ontology-api-openapi.yml
  format: yaml
  label: CostKits Procedure Ontology API
  slug: costkits-com-procedure-ontology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-procedure-ontology-api-openapi.yml
- filename: costkits-com-provider-graph-api-openapi.yml
  format: yaml
  label: CostKits Provider Graph API
  slug: costkits-com-provider-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-provider-graph-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use Cost Kits for personal, non-commercial purposes to analyze your own medical bills and healthcare costs.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You may use Cost Kits for personal, non-commercial purposes
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
name: CostKits
provenance_date: '2026-11-09'
provider_name: CostKits
provider_slug: costkits-com
slug: costkits-com-eligibility
source_date: '2026-11-09'
source_filename: costkits-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.costkits.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CostKits\naid: costkits-com\nurl: https://www.costkits.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use Cost Kits for personal, non-commercial purposes to analyze your own medical bills and healthcare\n    costs.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You may use Cost Kits for personal, non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/costkits-com/eligibility/costkits-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CostKits's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Billing
- Healthcare Costs
- Price Transparency
- Caregivers
- Insurance
- MCP
---
