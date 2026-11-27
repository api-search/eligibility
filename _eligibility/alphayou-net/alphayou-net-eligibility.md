---
api_specs:
- filename: alphayou-net-alphayou-api-openapi.yml
  format: yaml
  label: alphayou-net Alpha You API
  slug: alphayou-net-alphayou-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphayou-net/openapi/alphayou-net-alphayou-api-openapi.yml
- filename: alphayou-net-products-api-openapi.yml
  format: yaml
  label: alphayou-net Products API
  slug: alphayou-net-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphayou-net/openapi/alphayou-net-products-api-openapi.yml
- filename: alphayou-net-traders-api-openapi.yml
  format: yaml
  label: alphayou-net Traders API
  slug: alphayou-net-traders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphayou-net/openapi/alphayou-net-traders-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service from a jurisdiction where it is prohibited, including any jurisdiction we restrict from time to time.
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited jurisdictions
    text: You may not use the Service from a jurisdiction where it is prohibited, including any jurisdiction we restrict from time to time.
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
name: alphayou-net
provenance_date: '2026-11-09'
provider_name: alphayou-net
provider_slug: alphayou-net
slug: alphayou-net-eligibility
source_date: '2026-11-09'
source_filename: alphayou-net-eligibility.yml
source_heading: Eligibility
source_page: https://app.alphayou.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: alphayou-net\naid: alphayou-net\nurl: https://app.alphayou.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service from a jurisdiction where it is prohibited, including any jurisdiction we restrict\n    from time to time.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.\nrestricted_uses:\n- summary: Prohibited jurisdictions\n  text: You may not use the Service from a jurisdiction where it is prohibited, including any jurisdiction we restrict\n    from time\
  \ to time.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/alphayou-net/eligibility/alphayou-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from alphayou-net's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Stock Research
- TradingTools
- Market Analytics
- Alerts
---
