---
api_specs:
- filename: takehomeapi-com-compare-api-openapi.yml
  format: yaml
  label: takehomeapi-com Compare API
  slug: takehomeapi-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-compare-api-openapi.yml
- filename: takehomeapi-com-rates-api-openapi.yml
  format: yaml
  label: takehomeapi-com Rates API
  slug: takehomeapi-com-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-rates-api-openapi.yml
- filename: takehomeapi-com-take-home-api-openapi.yml
  format: yaml
  label: takehomeapi-com Take Home API
  slug: takehomeapi-com-take-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-take-home-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for businesses and developers.
    type: business
  - text: The Service is intended for businesses and developers.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Estimates not advice
    text: They are not tax, financial, legal or payroll advice, and must not be relied on as the sole basis for payroll runs, tax returns or financial decisions.
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
name: takehomeapi-com
provenance_date: '2026-11-10'
provider_name: takehomeapi-com
provider_slug: takehomeapi-com
slug: takehomeapi-com-eligibility
source_date: '2026-11-10'
source_filename: takehomeapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://takehomeapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: takehomeapi-com\naid: takehomeapi-com\nurl: https://takehomeapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for businesses and developers.\n- type: developer\n  text: The Service is intended for businesses and developers.\nrestricted_uses:\n- summary: Estimates not advice\n  text: They are not tax, financial, legal or payroll advice, and must not be relied on as the sole basis for payroll\n    runs, tax returns or financial decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/takehomeapi-com/eligibility/takehomeapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from takehomeapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- United Kingdom
- Finance
- Tax
- Payroll
---
