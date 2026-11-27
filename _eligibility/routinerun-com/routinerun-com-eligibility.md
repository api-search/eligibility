---
api_specs:
- filename: routinerun-com-events-api-openapi.yml
  format: yaml
  label: routinerun-com Events API
  slug: routinerun-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-events-api-openapi.yml
- filename: routinerun-com-runs-api-openapi.yml
  format: yaml
  label: routinerun-com Runs API
  slug: routinerun-com-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-runs-api-openapi.yml
- filename: routinerun-com-commands-api-openapi.yml
  format: yaml
  label: routinerun-com Commands API
  slug: routinerun-com-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-commands-api-openapi.yml
- filename: routinerun-com-history-api-openapi.yml
  format: yaml
  label: routinerun-com History API
  slug: routinerun-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-history-api-openapi.yml
- filename: routinerun-com-pagerduty-api-openapi.yml
  format: yaml
  label: routinerun-com Pagerduty API
  slug: routinerun-com-pagerduty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-pagerduty-api-openapi.yml
- filename: routinerun-com-routines-api-openapi.yml
  format: yaml
  label: routinerun-com Routines API
  slug: routinerun-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-routines-api-openapi.yml
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
  - summary: Not a medical or safety product
    text: Routine Run is not a medical product and does not treat or help any condition. It is not a safety system.
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
name: routinerun-com
provenance_date: '2026-11-10'
provider_name: routinerun-com
provider_slug: routinerun-com
slug: routinerun-com-eligibility
source_date: '2026-11-10'
source_filename: routinerun-com-eligibility.yml
source_heading: Eligibility
source_page: https://routinerun.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: routinerun-com\naid: routinerun-com\nurl: https://routinerun.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not a medical or safety product\n  text: Routine Run is not a medical product and does not treat or help any condition. It is not a safety system.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/routinerun-com/eligibility/routinerun-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from routinerun-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Productivity
- Task Management
- No-Code
---
