---
api_specs:
- filename: casanest-eu-public-api-openapi.yml
  format: yaml
  label: CasaNest Public API
  slug: casanest-eu-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casanest-eu/openapi/casanest-eu-public-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We give estate agencies and private individuals a place to publish properties
    type: business
  - text: We give estate agencies and private individuals a place to publish properties
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited listings
    text: False, duplicate, discriminatory or offensive listings, listings unrelated to the purpose of the portal, and listings that infringe third-party rights are not permitted.
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
name: CasaNest
provenance_date: '2026-11-09'
provider_name: CasaNest
provider_slug: casanest-eu
slug: casanest-eu-eligibility
source_date: '2026-11-09'
source_filename: casanest-eu-eligibility.yml
source_heading: Eligibility
source_page: https://casanest.eu/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CasaNest\naid: casanest-eu\nurl: https://casanest.eu/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We give estate agencies and private individuals a place to publish properties\n- type: individual\n  text: We give estate agencies and private individuals a place to publish properties\nrestricted_uses:\n- summary: Prohibited listings\n  text: False, duplicate, discriminatory or offensive listings, listings unrelated to the purpose of the portal,\n    and listings that infringe third-party rights are not permitted.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/casanest-eu/eligibility/casanest-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CasaNest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Listings
- Portugal
- PropTech
- CRM Integration
- MCP
- Housing Statistics
---
