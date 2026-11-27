---
api_specs:
- filename: paga-business-api-openapi.yml
  format: yaml
  label: Paga Business API
  slug: paga-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paga/openapi/paga-business-api-openapi.yml
- filename: paga-collect-api-openapi.yml
  format: yaml
  label: Paga Collect API
  slug: paga-collect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paga/openapi/paga-collect-api-openapi.yml
- filename: paga-direct-debit-api-openapi.yml
  format: yaml
  label: Paga Direct Debit API
  slug: paga-direct-debit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paga/openapi/paga-direct-debit-api-openapi.yml
- filename: paga-reference-api-openapi.yml
  format: yaml
  label: Paga Reference API
  slug: paga-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paga/openapi/paga-reference-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customers who are under 18 years of age should review these terms and conditions with a parent or guardian.
    type: individual
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
name: Paga
provenance_date: '2026-11-10'
provider_name: Paga
provider_slug: paga
slug: paga-eligibility
source_date: '2026-11-10'
source_filename: paga-eligibility.yml
source_heading: Eligibility
source_page: https://www.mypaga.com/paga-web/terms.paga
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paga\naid: paga\nurl: https://www.mypaga.com/paga-web/terms.paga\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customers who are under 18 years of age should review these terms and conditions with a parent or guardian.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paga/eligibility/paga-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Paga's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Mobile Money
- Fintech
- Collection
- Nigeria
---
