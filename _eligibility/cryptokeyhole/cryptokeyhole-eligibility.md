---
api_specs:
- filename: cryptokeyhole-charts-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Charts API
  slug: cryptokeyhole-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-charts-api-openapi.yml
- filename: cryptokeyhole-indices-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Indices API
  slug: cryptokeyhole-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-indices-api-openapi.yml
- filename: cryptokeyhole-markets-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Markets API
  slug: cryptokeyhole-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-markets-api-openapi.yml
- filename: cryptokeyhole-platform-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Platform API
  slug: cryptokeyhole-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-platform-api-openapi.yml
- filename: cryptokeyhole-tools-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Tools API
  slug: cryptokeyhole-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Plus and Pro are personal plans.
    type: individual
  - text: For business customers, our total liability in any 12 months is limited to the amount paid for the service in that period.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal plans for own research
    text: Use the charts, downloads and API they add for your own research and decisions, including your own trading.
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
name: CryptoKeyhole
provenance_date: '2026-11-09'
provider_name: CryptoKeyhole
provider_slug: cryptokeyhole
slug: cryptokeyhole-eligibility
source_date: '2026-11-09'
source_filename: cryptokeyhole-eligibility.yml
source_heading: Eligibility
source_page: https://cryptokeyhole.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CryptoKeyhole\naid: cryptokeyhole\nurl: https://cryptokeyhole.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Plus and Pro are personal plans.\n- type: business\n  text: For business customers, our total liability in any 12 months is limited to the amount paid for the service\n    in that period.\nrestricted_uses:\n- summary: Personal plans for own research\n  text: Use the charts, downloads and API they add for your own research and decisions, including your own trading.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cryptokeyhole/eligibility/cryptokeyhole-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CryptoKeyhole's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Blockchain
- Analytics
- Data
- Charts
---
