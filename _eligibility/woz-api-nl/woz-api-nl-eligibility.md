---
api_specs:
- filename: woz-api-nl-account-api-openapi.yml
  format: yaml
  label: woz-api-nl Account API
  slug: woz-api-nl-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-account-api-openapi.yml
- filename: woz-api-nl-adressen-api-openapi.yml
  format: yaml
  label: woz-api-nl Adressen API
  slug: woz-api-nl-adressen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-adressen-api-openapi.yml
- filename: woz-api-nl-lijst-api-openapi.yml
  format: yaml
  label: woz-api-nl Lijst API
  slug: woz-api-nl-lijst-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-lijst-api-openapi.yml
- filename: woz-api-nl-proef-api-openapi.yml
  format: yaml
  label: woz-api-nl Proef API
  slug: woz-api-nl-proef-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-proef-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: De Dienst is bedoeld voor zakelijk gebruik.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Voor gebruik kan een Account vereist zijn.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: woz-api-nl
provenance_date: '2026-11-10'
provider_name: woz-api-nl
provider_slug: woz-api-nl
slug: woz-api-nl-eligibility
source_date: '2026-11-10'
source_filename: woz-api-nl-eligibility.yml
source_heading: Eligibility
source_page: https://woz-api.nl/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: woz-api-nl\naid: woz-api-nl\nurl: https://woz-api.nl/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: De Dienst is bedoeld voor zakelijk gebruik.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Voor gebruik kan een Account vereist zijn.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/woz-api-nl/eligibility/woz-api-nl-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from woz-api-nl's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Netherlands
- Property Valuation
- WOZ
---
