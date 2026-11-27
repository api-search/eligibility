---
api_specs:
- filename: gray-swan-activity-api-openapi.yml
  format: yaml
  label: Gray Swan Activity API
  slug: gray-swan-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gray-swan/openapi/gray-swan-activity-api-openapi.yml
- filename: gray-swan-cygnal-api-openapi.yml
  format: yaml
  label: Gray Swan Cygnal API
  slug: gray-swan-cygnal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gray-swan/openapi/gray-swan-cygnal-api-openapi.yml
- filename: gray-swan-policies-api-openapi.yml
  format: yaml
  label: Gray Swan Policies API
  slug: gray-swan-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gray-swan/openapi/gray-swan-policies-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export Regulation: You shall not export ... to any jurisdiction or country to which export ... is prohibited by law, regulation, or rule.'
  minimum_age:
    text: null
    value: null
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
name: Gray Swan
provenance_date: '2026-11-09'
provider_name: Gray Swan
provider_slug: gray-swan
slug: gray-swan-eligibility
source_date: '2026-11-09'
source_filename: gray-swan-eligibility.yml
source_heading: Eligibility
source_page: https://www.grayswan.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gray Swan\naid: gray-swan\nurl: https://www.grayswan.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export Regulation: You shall not export ... to any jurisdiction or country to which export ... is prohibited\n    by law, regulation, or rule.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gray-swan/eligibility/gray-swan-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Gray Swan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Security
- LLM Security
- Guardrails
- Red Teaming
- AI Governance
- Prompt Injection
- Model Safety
- API Security
---
