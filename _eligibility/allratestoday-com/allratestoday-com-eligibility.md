---
api_specs:
- filename: allratestoday-com-authentication-api-openapi.yml
  format: yaml
  label: allratestoday-com Authentication API
  slug: allratestoday-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-authentication-api-openapi.yml
- filename: allratestoday-com-central-bank-rates-api-openapi.yml
  format: yaml
  label: allratestoday-com Central Bank Rates API
  slug: allratestoday-com-central-bank-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-central-bank-rates-api-openapi.yml
- filename: allratestoday-com-compatibility-api-openapi.yml
  format: yaml
  label: allratestoday-com Compatibility API
  slug: allratestoday-com-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-compatibility-api-openapi.yml
- filename: allratestoday-com-market-rates-api-openapi.yml
  format: yaml
  label: allratestoday-com Market Rates API
  slug: allratestoday-com-market-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-market-rates-api-openapi.yml
- filename: allratestoday-com-open-endpoints-api-openapi.yml
  format: yaml
  label: allratestoday-com Open Endpoints API
  slug: allratestoday-com-open-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-open-endpoints-api-openapi.yml
- filename: allratestoday-com-reference-rate-api-openapi.yml
  format: yaml
  label: allratestoday-com Reference Rate API
  slug: allratestoday-com-reference-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-reference-rate-api-openapi.yml
claim_count: 2
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
  - summary: Lawful use only
    text: Use the API only for lawful purposes
  - summary: Free tier not for commercial use
    text: Use the free tier or the keyless official-rate endpoints in a commercial product, a paid service, or a public display
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
name: allratestoday-com
provenance_date: '2026-11-09'
provider_name: allratestoday-com
provider_slug: allratestoday-com
slug: allratestoday-com-eligibility
source_date: '2026-11-09'
source_filename: allratestoday-com-eligibility.yml
source_heading: Eligibility
source_page: https://allratestoday.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: allratestoday-com\naid: allratestoday-com\nurl: https://allratestoday.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: Use the API only for lawful purposes\n- summary: Free tier not for commercial use\n  text: Use the free tier or the keyless official-rate endpoints in a commercial product, a paid service, or a public\n    display\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/allratestoday-com/eligibility/allratestoday-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from allratestoday-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Exchange Rates
- Data
---
