---
api_specs:
- filename: coveragecat-com-agent-api-openapi.yml
  format: yaml
  label: Coverage Cat Agent API
  slug: coveragecat-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-agent-api-openapi.yml
- filename: coveragecat-com-consumer-api-openapi.yml
  format: yaml
  label: Coverage Cat Consumer API
  slug: coveragecat-com-consumer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-consumer-api-openapi.yml
- filename: coveragecat-com-intake-api-openapi.yml
  format: yaml
  label: Coverage Cat Intake API
  slug: coveragecat-com-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-intake-api-openapi.yml
- filename: coveragecat-com-tools-api-openapi.yml
  format: yaml
  label: Coverage Cat Tools API
  slug: coveragecat-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-tools-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
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
name: Coverage Cat
provenance_date: '2026-11-09'
provider_name: Coverage Cat
provider_slug: coveragecat-com
slug: coveragecat-com-eligibility
source_date: '2026-11-09'
source_filename: coveragecat-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.coveragecat.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coverage Cat\naid: coveragecat-com\nurl: https://www.coveragecat.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/coveragecat-com/eligibility/coveragecat-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Coverage Cat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurance Broker
- Homeowners Insurance
- Umbrella Insurance
- Auto Insurance
- AI Agents
- MCP
---
