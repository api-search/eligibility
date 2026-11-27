---
api_specs:
- filename: govconapi-com-openapi-generated.yml
  format: yaml
  label: govconapi-com API
  slug: govconapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govconapi-com/openapi/_ae-authored/govconapi-com-openapi-generated.yml
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
  - summary: Production use needs paid plan
    text: Using it in production, or in a product or service you sell, requires a paid plan.
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
name: govconapi-com
provenance_date: '2026-11-09'
provider_name: govconapi-com
provider_slug: govconapi-com
slug: govconapi-com-eligibility
source_date: '2026-11-09'
source_filename: govconapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://govconapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: govconapi-com\naid: govconapi-com\nurl: https://govconapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Production use needs paid plan\n  text: Using it in production, or in a product or service you sell, requires a paid plan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/govconapi-com/eligibility/govconapi-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from govconapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Federal
- Procurement
- Data
---
