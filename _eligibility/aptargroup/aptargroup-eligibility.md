---
api_specs:
- filename: aptargroup-orders-api-openapi.yml
  format: yaml
  label: AptarGroup Orders API
  slug: aptargroup-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptargroup/openapi/aptargroup-orders-api-openapi.yml
- filename: aptargroup-products-api-openapi.yml
  format: yaml
  label: AptarGroup Products API
  slug: aptargroup-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptargroup/openapi/aptargroup-products-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to the Website is open to adults. Any use of the Website by a minor must be carried out under the full responsibility of the minor’s parental authority.
    type: individual
  minimum_age:
    text: Access to the Website is open to adults.
    value: adults
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
name: AptarGroup
provenance_date: '2026-11-09'
provider_name: AptarGroup
provider_slug: aptargroup
slug: aptargroup-eligibility
source_date: '2026-11-09'
source_filename: aptargroup-eligibility.yml
source_heading: Eligibility
source_page: https://www.aptar.com/en-us/general-terms-and-conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AptarGroup\naid: aptargroup\nurl: https://www.aptar.com/en-us/general-terms-and-conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to the Website is open to adults. Any use of the Website by a minor must be carried out under the\n    full responsibility of the minor’s parental authority.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adults\n  text: Access to the Website is open to adults.\n"
source_yaml_url: https://artifacts.apis.io/aptargroup/eligibility/aptargroup-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AptarGroup's own page on 2026-11-09.
synthetic: false
tags:
- Packaging
- Dispensing
- Manufacturing
- Sustainability
- Consumer Goods
- Fortune 1000
---
