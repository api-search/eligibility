---
api_specs:
- filename: veeqo-openapi-generated.yml
  format: yaml
  label: Veeqo API
  slug: veeqo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeqo/openapi/_ae-authored/veeqo-openapi-generated.yml
- filename: veeqo-current-user-api-openapi.yml
  format: yaml
  label: Veeqo Current User API
  slug: veeqo-current-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeqo/openapi/veeqo-current-user-api-openapi.yml
- filename: veeqo-oauth-api-openapi.yml
  format: yaml
  label: Veeqo OAuth API
  slug: veeqo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeqo/openapi/veeqo-oauth-api-openapi.yml
- filename: veeqo-orders-api-openapi.yml
  format: yaml
  label: Veeqo Orders API
  slug: veeqo-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeqo/openapi/veeqo-orders-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to create an account and use the Service.
    type: individual
  - text: to you or the business you represent
    type: business
  minimum_age:
    text: You must be at least 18 years of age to create an account and use the Service.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export compliance
    text: you are not the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments of the country where you are using the Service
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
name: Veeqo
provenance_date: '2026-11-10'
provider_name: Veeqo
provider_slug: veeqo
slug: veeqo-eligibility
source_date: '2026-11-10'
source_filename: veeqo-eligibility.yml
source_heading: Eligibility
source_page: https://www.veeqo.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veeqo\naid: veeqo\nurl: https://www.veeqo.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to create an account and use the Service.\n- type: business\n  text: to you or the business you represent\nrestricted_uses:\n- summary: Sanctions and export compliance\n  text: you are not the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments\n    of the country where you are using the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an account and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/veeqo/eligibility/veeqo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Veeqo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Inventory
- Order Fulfillment
- Multi-Channel
- Software-as-a-Service
---
