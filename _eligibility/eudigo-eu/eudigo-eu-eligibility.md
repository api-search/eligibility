---
api_specs:
- filename: eudigo-eu-deadlines-api-openapi.yml
  format: yaml
  label: Eudigo Deadlines API
  slug: eudigo-eu-deadlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudigo-eu/openapi/eudigo-eu-deadlines-api-openapi.yml
- filename: eudigo-eu-developers-api-openapi.yml
  format: yaml
  label: Eudigo Developers API
  slug: eudigo-eu-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudigo-eu/openapi/eudigo-eu-developers-api-openapi.yml
- filename: eudigo-eu-index-api-openapi.yml
  format: yaml
  label: Eudigo Index API
  slug: eudigo-eu-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudigo-eu/openapi/eudigo-eu-index-api-openapi.yml
- filename: eudigo-eu-knowledge-api-openapi.yml
  format: yaml
  label: Eudigo Knowledge API
  slug: eudigo-eu-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudigo-eu/openapi/eudigo-eu-knowledge-api-openapi.yml
- filename: eudigo-eu-registers-api-openapi.yml
  format: yaml
  label: Eudigo Registers API
  slug: eudigo-eu-registers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudigo-eu/openapi/eudigo-eu-registers-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: No API key
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eudigo
provenance_date: '2026-11-09'
provider_name: Eudigo
provider_slug: eudigo-eu
slug: eudigo-eu-eligibility
source_date: '2026-11-09'
source_filename: eudigo-eu-eligibility.yml
source_heading: Eligibility
source_page: https://eudigo.eu/en/developers/api/#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eudigo\naid: eudigo-eu\nurl: https://eudigo.eu/en/developers/api/#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: No API key\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eudigo-eu/eligibility/eudigo-eu-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Eudigo's own page on 2026-11-09.
synthetic: false
tags:
- Digital Identity
- EUDI Wallet
- EU
- Open Data
- Guides
---
