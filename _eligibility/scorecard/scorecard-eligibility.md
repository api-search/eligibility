---
api_specs:
- filename: scorecard-metrics-api-openapi.yml
  format: yaml
  label: Scorecard Metrics API
  slug: scorecard-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-metrics-api-openapi.yml
- filename: scorecard-projects-api-openapi.yml
  format: yaml
  label: Scorecard Projects API
  slug: scorecard-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-projects-api-openapi.yml
- filename: scorecard-records-api-openapi.yml
  format: yaml
  label: Scorecard Records API
  slug: scorecard-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-records-api-openapi.yml
- filename: scorecard-runs-api-openapi.yml
  format: yaml
  label: Scorecard Runs API
  slug: scorecard-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-runs-api-openapi.yml
- filename: scorecard-systems-api-openapi.yml
  format: yaml
  label: Scorecard Systems API
  slug: scorecard-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-systems-api-openapi.yml
- filename: scorecard-test-cases-api-openapi.yml
  format: yaml
  label: Scorecard Test Cases API
  slug: scorecard-test-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-test-cases-api-openapi.yml
- filename: scorecard-test-sets-api-openapi.yml
  format: yaml
  label: Scorecard Test Sets API
  slug: scorecard-test-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scorecard/openapi/scorecard-test-sets-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harmful or violating use
    text: Use the Services in violation of this Agreement or in a manner that could cause harm.
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
name: Scorecard
provenance_date: '2026-11-10'
provider_name: Scorecard
provider_slug: scorecard
slug: scorecard-eligibility
source_date: '2026-11-10'
source_filename: scorecard-eligibility.yml
source_heading: Eligibility
source_page: https://www.scorecard.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scorecard\naid: scorecard\nurl: https://www.scorecard.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful or violating use\n  text: Use the Services in violation of this Agreement or in a manner that could cause harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scorecard/eligibility/scorecard-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Scorecard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Evaluation
- Testing
- LLM
- Observability
- Simulation
- Developer Tools
- MCP
---
