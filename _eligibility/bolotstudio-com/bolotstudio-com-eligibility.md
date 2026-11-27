---
api_specs:
- filename: bolotstudio-com-authentication-api-openapi.yml
  format: yaml
  label: Bolot Studio Authentication API
  slug: bolotstudio-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-authentication-api-openapi.yml
- filename: bolotstudio-com-discovery-api-openapi.yml
  format: yaml
  label: Bolot Studio Discovery API
  slug: bolotstudio-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-discovery-api-openapi.yml
- filename: bolotstudio-com-feeds-api-openapi.yml
  format: yaml
  label: Bolot Studio Feeds API
  slug: bolotstudio-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-feeds-api-openapi.yml
- filename: bolotstudio-com-mcp-api-openapi.yml
  format: yaml
  label: Bolot Studio MCP API
  slug: bolotstudio-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-mcp-api-openapi.yml
- filename: bolotstudio-com-products-api-openapi.yml
  format: yaml
  label: Bolot Studio Products API
  slug: bolotstudio-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-products-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability and shipping terms depend on the selected delivery market.
  minimum_age:
    text: you confirm that you are at least the age of majority in your country of residence, or that you have the consent required for a minor dependent to use this site under your supervision.
    value: age of majority
  restricted_uses:
  - summary: Refusal of orders on objective grounds
    text: We may refuse, limit or cancel an order only on objective grounds
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
name: Bolot Studio
provenance_date: '2026-11-09'
provider_name: Bolot Studio
provider_slug: bolotstudio-com
slug: bolotstudio-com-eligibility
source_date: '2026-11-09'
source_filename: bolotstudio-com-eligibility.yml
source_heading: Eligibility
source_page: https://bolotstudio.com/en/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bolot Studio\naid: bolotstudio-com\nurl: https://bolotstudio.com/en/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability and shipping terms depend on the selected delivery market.\nentity_types: []\nrestricted_uses:\n- summary: Refusal of orders on objective grounds\n  text: We may refuse, limit or cancel an order only on objective grounds\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you confirm that you are at least the age of majority in your country of residence,\
  \ or that you have the\n    consent required for a minor dependent to use this site under your supervision.\n"
source_yaml_url: https://artifacts.apis.io/bolotstudio-com/eligibility/bolotstudio-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bolot Studio's own page on 2026-11-09.
synthetic: false
tags:
- Print Shop
- CustomPrints
- E-Commerce
- Photography
- Aluminium
---
