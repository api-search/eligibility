---
api_specs:
- filename: omniyond-com-mcp-api-openapi.yml
  format: yaml
  label: omniyond-com MCP API
  slug: omniyond-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-mcp-api-openapi.yml
- filename: omniyond-com-scheduler-api-openapi.yml
  format: yaml
  label: omniyond-com Scheduler API
  slug: omniyond-com-scheduler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-scheduler-api-openapi.yml
- filename: omniyond-com-utility-api-openapi.yml
  format: yaml
  label: omniyond-com Utility API
  slug: omniyond-com-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-utility-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use Omniyond.
    value: '18'
  restricted_uses:
  - summary: Illegal, harmful or fraudulent purposes
    text: Use the service for illegal, harmful, or fraudulent purposes
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
name: omniyond-com
provenance_date: '2026-11-10'
provider_name: omniyond-com
provider_slug: omniyond-com
slug: omniyond-com-eligibility
source_date: '2026-11-10'
source_filename: omniyond-com-eligibility.yml
source_heading: Eligibility
source_page: https://omniyond.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: omniyond-com\naid: omniyond-com\nurl: https://omniyond.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal, harmful or fraudulent purposes\n  text: Use the service for illegal, harmful, or fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Omniyond.\n"
source_yaml_url: https://artifacts.apis.io/omniyond-com/eligibility/omniyond-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from omniyond-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Pay-per-use
- Scheduling
- Automation
---
