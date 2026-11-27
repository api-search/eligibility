---
api_specs:
- filename: recurrency-e-procurement-api-openapi.yml
  format: yaml
  label: Recurrency E-Procurement API
  slug: recurrency-e-procurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recurrency/openapi/recurrency-e-procurement-api-openapi.yml
- filename: recurrency-orders-api-openapi.yml
  format: yaml
  label: Recurrency Orders API
  slug: recurrency-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recurrency/openapi/recurrency-orders-api-openapi.yml
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
  - summary: Illegal use prohibited
    text: (l) use the Services for any purpose that is illegal in any way or that advocates illegal activity
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
name: Recurrency
provenance_date: '2026-11-10'
provider_name: Recurrency
provider_slug: recurrency
slug: recurrency-eligibility
source_date: '2026-11-10'
source_filename: recurrency-eligibility.yml
source_heading: Eligibility
source_page: https://www.recurrency.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recurrency\naid: recurrency\nurl: https://www.recurrency.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use prohibited\n  text: (l) use the Services for any purpose that is illegal in any way or that advocates illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recurrency/eligibility/recurrency-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Recurrency's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- ERP
- Distribution
- Wholesale
- eProcurement
- Supply Chain
- Order
---
