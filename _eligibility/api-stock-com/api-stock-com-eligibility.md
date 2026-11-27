---
api_specs:
- filename: api-stock-com-account-management-api-openapi.yml
  format: yaml
  label: API Stock Account Management API
  slug: api-stock-com-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-account-management-api-openapi.yml
- filename: api-stock-com-agent-api-openapi.yml
  format: yaml
  label: API Stock Agent API
  slug: api-stock-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-agent-api-openapi.yml
- filename: api-stock-com-catalog-api-openapi.yml
  format: yaml
  label: API Stock Catalog API
  slug: api-stock-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-catalog-api-openapi.yml
- filename: api-stock-com-costs-api-openapi.yml
  format: yaml
  label: API Stock Costs API
  slug: api-stock-com-costs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-costs-api-openapi.yml
- filename: api-stock-com-generations-api-openapi.yml
  format: yaml
  label: API Stock Generations API
  slug: api-stock-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-generations-api-openapi.yml
- filename: api-stock-com-llm-api-openapi.yml
  format: yaml
  label: API Stock LLM API
  slug: api-stock-com-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-llm-api-openapi.yml
- filename: api-stock-com-task-management-api-openapi.yml
  format: yaml
  label: API Stock Task Management API
  slug: api-stock-com-task-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-task-management-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, and legally able to enter into a contract.
    type: individual
  - text: If you are entering into these Terms on behalf of a company, you confirm that you are authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Sexual content involving minors
    text: generate sexual content involving minors, or any content that sexualises a minor, in any form
  - summary: Non-consensual intimate imagery
    text: create non-consensual intimate imagery, or a likeness, voice or persona of a real person for deception, harassment, defamation or fraud
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
name: API Stock
provenance_date: '2026-11-09'
provider_name: API Stock
provider_slug: api-stock-com
slug: api-stock-com-eligibility
source_date: '2026-11-09'
source_filename: api-stock-com-eligibility.yml
source_heading: Eligibility
source_page: https://api-stock.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: API Stock\naid: api-stock-com\nurl: https://api-stock.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, and legally able to enter\n    into a contract.\n- type: business\n  text: If you are entering into these Terms on behalf of a company, you confirm that you are authorised to bind\n    it.\nrestricted_uses:\n- summary: Sexual content involving minors\n  text: generate sexual content involving minors, or any content that sexualises a minor, in\
  \ any form\n- summary: Non-consensual intimate imagery\n  text: create non-consensual intimate imagery, or a likeness, voice or persona of a real person for deception,\n    harassment, defamation or fraud\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/api-stock-com/eligibility/api-stock-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from API Stock's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- LLM
- Platform
---
