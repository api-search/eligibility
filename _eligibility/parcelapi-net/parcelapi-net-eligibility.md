---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ParcelAPI (parcelapi.net) is operated by Howard, a sole proprietor in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer report decisions
    text: the data is not a consumer report and must not be used for credit, employment, insurance or tenant screening decisions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By obtaining an API key or calling the API you agree to them.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: parcelapi-net
provenance_date: '2026-11-10'
provider_name: parcelapi-net
provider_slug: parcelapi-net
slug: parcelapi-net-eligibility
source_date: '2026-11-10'
source_filename: parcelapi-net-eligibility.yml
source_heading: Eligibility
source_page: https://parcelapi.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: parcelapi-net\naid: parcelapi-net\nurl: https://parcelapi.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ParcelAPI (parcelapi.net) is operated by Howard, a sole proprietor in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Consumer report decisions\n  text: the data is not a consumer report and must not be used for credit, employment, insurance or tenant screening\n    decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By obtaining an API key or calling the API you agree to them.\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/parcelapi-net/eligibility/parcelapi-net-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from parcelapi-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data
- US
---
