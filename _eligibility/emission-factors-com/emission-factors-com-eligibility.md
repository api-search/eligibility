---
api_specs:
- filename: emission-factors-com-bulk-api-openapi.yml
  format: yaml
  label: emission-factors-com Bulk API
  slug: emission-factors-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-bulk-api-openapi.yml
- filename: emission-factors-com-calculate-api-openapi.yml
  format: yaml
  label: emission-factors-com Calculate API
  slug: emission-factors-com-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-calculate-api-openapi.yml
- filename: emission-factors-com-cleanest-hours-api-openapi.yml
  format: yaml
  label: emission-factors-com Cleanest Hours API
  slug: emission-factors-com-cleanest-hours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-cleanest-hours-api-openapi.yml
- filename: emission-factors-com-compare-api-openapi.yml
  format: yaml
  label: emission-factors-com Compare API
  slug: emission-factors-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-compare-api-openapi.yml
- filename: emission-factors-com-fuel-emissions-api-openapi.yml
  format: yaml
  label: emission-factors-com Fuel Emissions API
  slug: emission-factors-com-fuel-emissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-fuel-emissions-api-openapi.yml
- filename: emission-factors-com-health-api-openapi.yml
  format: yaml
  label: emission-factors-com Health API
  slug: emission-factors-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-health-api-openapi.yml
- filename: emission-factors-com-intensity-api-openapi.yml
  format: yaml
  label: emission-factors-com Intensity API
  slug: emission-factors-com-intensity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-intensity-api-openapi.yml
- filename: emission-factors-com-lookup-api-openapi.yml
  format: yaml
  label: emission-factors-com Lookup API
  slug: emission-factors-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-lookup-api-openapi.yml
- filename: emission-factors-com-mcp-api-openapi.yml
  format: yaml
  label: emission-factors-com MCP API
  slug: emission-factors-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-mcp-api-openapi.yml
- filename: emission-factors-com-methodology-api-openapi.yml
  format: yaml
  label: emission-factors-com Methodology API
  slug: emission-factors-com-methodology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-methodology-api-openapi.yml
- filename: emission-factors-com-openapi-json-api-openapi.yml
  format: yaml
  label: emission-factors-com Openapi.json API
  slug: emission-factors-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-openapi-json-api-openapi.yml
- filename: emission-factors-com-plant-emissions-api-openapi.yml
  format: yaml
  label: emission-factors-com Plant Emissions API
  slug: emission-factors-com-plant-emissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-plant-emissions-api-openapi.yml
- filename: emission-factors-com-rate-api-openapi.yml
  format: yaml
  label: emission-factors-com Rate API
  slug: emission-factors-com-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-rate-api-openapi.yml
- filename: emission-factors-com-status-api-openapi.yml
  format: yaml
  label: emission-factors-com Status API
  slug: emission-factors-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-status-api-openapi.yml
- filename: emission-factors-com-utility-rate-api-openapi.yml
  format: yaml
  label: emission-factors-com Utility Rate API
  slug: emission-factors-com-utility-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-utility-rate-api-openapi.yml
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
  - summary: Unlawful purposes
    text: Do not use the API for any unlawful purpose.
  verification:
    approval_required: false
    kyb: false
    kyc: false
    text: 'The API is free and keyless: no signup, no API key, no paid tier.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: emission-factors-com
provenance_date: '2026-11-09'
provider_name: emission-factors-com
provider_slug: emission-factors-com
slug: emission-factors-com-eligibility
source_date: '2026-11-09'
source_filename: emission-factors-com-eligibility.yml
source_heading: Eligibility
source_page: https://emission-factors.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: emission-factors-com\naid: emission-factors-com\nurl: https://emission-factors.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Do not use the API for any unlawful purpose.\nverification:\n  kyc: false\n  kyb: false\n  approval_required: false\n  text: 'The API is free and keyless: no signup, no API key, no paid tier.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emission-factors-com/eligibility/emission-factors-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from emission-factors-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emission
- Carbon
- Energy
- Sustainability
---
