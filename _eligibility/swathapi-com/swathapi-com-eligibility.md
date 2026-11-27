---
api_specs:
- filename: swathapi-com-billing-api-openapi.yml
  format: yaml
  label: swathapi-com Billing API
  slug: swathapi-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-billing-api-openapi.yml
- filename: swathapi-com-monitors-api-openapi.yml
  format: yaml
  label: swathapi-com Monitors API
  slug: swathapi-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-monitors-api-openapi.yml
- filename: swathapi-com-property-api-openapi.yml
  format: yaml
  label: swathapi-com Property API
  slug: swathapi-com-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-property-api-openapi.yml
- filename: swathapi-com-signup-api-openapi.yml
  format: yaml
  label: swathapi-com Signup API
  slug: swathapi-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-signup-api-openapi.yml
- filename: swathapi-com-storms-api-openapi.yml
  format: yaml
  label: swathapi-com Storms API
  slug: swathapi-com-storms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-storms-api-openapi.yml
- filename: swathapi-com-swaths-api-openapi.yml
  format: yaml
  label: swathapi-com Swaths API
  slug: swathapi-com-swaths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-swaths-api-openapi.yml
- filename: swathapi-com-usage-api-openapi.yml
  format: yaml
  label: swathapi-com Usage API
  slug: swathapi-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-usage-api-openapi.yml
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
  - summary: No sole basis for insurance, credit or eligibility decisions
    text: Do not use the Service as the sole basis for denying, approving, or valuing an insurance claim, extending credit, or making an eligibility decision about any person.
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
name: swathapi-com
provenance_date: '2026-11-10'
provider_name: swathapi-com
provider_slug: swathapi-com
slug: swathapi-com-eligibility
source_date: '2026-11-10'
source_filename: swathapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://swathapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: swathapi-com\naid: swathapi-com\nurl: https://swathapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sole basis for insurance, credit or eligibility decisions\n  text: Do not use the Service as the sole basis for denying, approving, or valuing an insurance claim, extending\n    credit, or making an eligibility decision about any person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/swathapi-com/eligibility/swathapi-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from swathapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Weather
- Storm
- Artificial Intelligence
- NOAA
---
