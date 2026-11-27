---
api_specs:
- filename: avahit-com-catalog-api-openapi.yml
  format: yaml
  label: Avahit Catalog API
  slug: avahit-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avahit-com/openapi/avahit-com-catalog-api-openapi.yml
- filename: avahit-com-lookup-api-openapi.yml
  format: yaml
  label: Avahit Lookup API
  slug: avahit-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avahit-com/openapi/avahit-com-lookup-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person, one account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Prohibited content categories
    text: Sexual content, content involving minors, violence, or hate speech.
  - summary: Illegal products
    text: 'Products that are illegal to sell in the buyer’s country: weapons, drugs, prescription medicines, live animals.'
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
name: Avahit
provenance_date: '2026-11-09'
provider_name: Avahit
provider_slug: avahit-com
slug: avahit-com-eligibility
source_date: '2026-11-09'
source_filename: avahit-com-eligibility.yml
source_heading: Eligibility
source_page: https://avahit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avahit\naid: avahit-com\nurl: https://avahit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person, one account.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: Sexual content, content involving minors, violence, or hate speech.\n- summary: Illegal products\n  text: 'Products that are illegal to sell in the buyer’s country: weapons, drugs, prescription medicines, live\n    animals.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/avahit-com/eligibility/avahit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Avahit's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- E-Commerce
- Shopping
- Amazon
- Product Discovery
---
