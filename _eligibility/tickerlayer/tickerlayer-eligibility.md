---
api_specs:
- filename: tickerlayer-openapi-generated.yml
  format: yaml
  label: TickerLayer API
  slug: tickerlayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerlayer/openapi/_ae-authored/tickerlayer-openapi-generated.yml
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
  - summary: Perpetual and derivative restrictions by jurisdiction
    text: Perpetual futures and similar derivatives are restricted or prohibited in some jurisdictions. You are responsible for every licence, registration, and restriction that applies to your use or display of this data.
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
name: TickerLayer
provenance_date: '2026-11-10'
provider_name: TickerLayer
provider_slug: tickerlayer
slug: tickerlayer-eligibility
source_date: '2026-11-10'
source_filename: tickerlayer-eligibility.yml
source_heading: Eligibility
source_page: https://tickerlayer.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TickerLayer\naid: tickerlayer\nurl: https://tickerlayer.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Perpetual and derivative restrictions by jurisdiction\n  text: Perpetual futures and similar derivatives are restricted or prohibited in some jurisdictions. You are responsible\n    for every licence, registration, and restriction that applies to your use or display of this data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tickerlayer/eligibility/tickerlayer-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TickerLayer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Data
- Real-Time
- Finance
---
