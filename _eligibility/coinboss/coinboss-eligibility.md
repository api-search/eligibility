---
api_specs:
- filename: coinboss-openapi-generated.yml
  format: yaml
  label: Coin Boss API
  slug: coinboss-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinboss/openapi/_ae-authored/coinboss-openapi-generated.yml
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
  - summary: Unlawful activity
    text: Users must not use the Site for any unlawful activity or to infringe on the rights of others.
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
name: Coin Boss
provenance_date: '2026-11-09'
provider_name: Coin Boss
provider_slug: coinboss
slug: coinboss-eligibility
source_date: '2026-11-09'
source_filename: coinboss-eligibility.yml
source_heading: Eligibility
source_page: https://www.coinboss.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coin Boss\naid: coinboss\nurl: https://www.coinboss.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful activity\n  text: Users must not use the Site for any unlawful activity or to infringe on the rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coinboss/eligibility/coinboss-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Coin Boss's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Derivatives
- Market Data
- Finance
---
