---
api_specs:
- filename: convelio-shipping-api-openapi.yml
  format: yaml
  label: Convelio Shipping API
  slug: convelio-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convelio/openapi/convelio-shipping-api-openapi.yml
- filename: convelio-webhook-api-openapi.yml
  format: yaml
  label: Convelio Webhook API
  slug: convelio-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convelio/openapi/convelio-webhook-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These terms & conditions apply to all transport transactions, storage and logistic services provided by Convelio SAS, covering operations in France and the United States.
  minimum_age:
    text: null
    value: null
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
name: Convelio
provenance_date: '2026-11-09'
provider_name: Convelio
provider_slug: convelio
slug: convelio-eligibility
source_date: '2026-11-09'
source_filename: convelio-eligibility.yml
source_heading: Eligibility
source_page: https://www.convelio.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convelio\naid: convelio\nurl: https://www.convelio.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: These terms & conditions apply to all transport transactions, storage and logistic services provided by\n    Convelio SAS, covering operations in France and the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/convelio/eligibility/convelio-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Convelio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- FineArt
- Freight
- E-Commerce
- Quotes
- Webhook
- Customs
- Insurance
---
