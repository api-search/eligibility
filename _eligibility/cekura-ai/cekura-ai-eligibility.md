---
api_specs:
- filename: cekura-ai-ai-agents-api-openapi.yml
  format: yaml
  label: Cekura AI Agents API
  slug: cekura-ai-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-ai-agents-api-openapi.yml
- filename: cekura-ai-call-logs-api-openapi.yml
  format: yaml
  label: Cekura Call Logs API
  slug: cekura-ai-call-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-call-logs-api-openapi.yml
- filename: cekura-ai-dashboards-api-openapi.yml
  format: yaml
  label: Cekura Dashboards API
  slug: cekura-ai-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-dashboards-api-openapi.yml
- filename: cekura-ai-evaluators-api-openapi.yml
  format: yaml
  label: Cekura Evaluators API
  slug: cekura-ai-evaluators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-evaluators-api-openapi.yml
- filename: cekura-ai-metrics-api-openapi.yml
  format: yaml
  label: Cekura Metrics API
  slug: cekura-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-metrics-api-openapi.yml
- filename: cekura-ai-observability-api-openapi.yml
  format: yaml
  label: Cekura Observability API
  slug: cekura-ai-observability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-observability-api-openapi.yml
- filename: cekura-ai-results-api-openapi.yml
  format: yaml
  label: Cekura Results API
  slug: cekura-ai-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-results-api-openapi.yml
- filename: cekura-ai-runs-api-openapi.yml
  format: yaml
  label: Cekura Runs API
  slug: cekura-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-runs-api-openapi.yml
- filename: cekura-ai-scenarios-api-openapi.yml
  format: yaml
  label: Cekura Scenarios API
  slug: cekura-ai-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-scenarios-api-openapi.yml
- filename: cekura-ai-schedules-api-openapi.yml
  format: yaml
  label: Cekura Schedules API
  slug: cekura-ai-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-schedules-api-openapi.yml
- filename: cekura-ai-slack-api-openapi.yml
  format: yaml
  label: Cekura Slack API
  slug: cekura-ai-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-slack-api-openapi.yml
- filename: cekura-ai-test-framework-api-openapi.yml
  format: yaml
  label: Cekura Test Framework API
  slug: cekura-ai-test-framework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-test-framework-api-openapi.yml
- filename: cekura-ai-user-api-openapi.yml
  format: yaml
  label: Cekura User API
  slug: cekura-ai-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cekura-ai/openapi/cekura-ai-user-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: you will not use the Services for any illegal or unauthorized purpose
  - summary: Embargoed countries and listed parties (mobile app)
    text: you are not located in a country that is subject to a US government embargo
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
name: Cekura
provenance_date: '2026-11-09'
provider_name: Cekura
provider_slug: cekura-ai
slug: cekura-ai-eligibility
source_date: '2026-11-09'
source_filename: cekura-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.cekura.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cekura\naid: cekura-ai\nurl: https://www.cekura.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: you will not use the Services for any illegal or unauthorized purpose\n- summary: Embargoed countries and listed parties (mobile app)\n  text: you are not located\
  \ in a country that is subject to a US government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/cekura-ai/eligibility/cekura-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cekura's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- QA
- Testing
- Benchmarking
---
