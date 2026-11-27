---
api_specs:
- filename: ripe-insurance-content-api-openapi.yml
  format: yaml
  label: Ripe Insurance Content API
  slug: ripe-insurance-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ripe-insurance/openapi/ripe-insurance-content-api-openapi.yml
- filename: ripe-insurance-media-api-openapi.yml
  format: yaml
  label: Ripe Insurance Media API
  slug: ripe-insurance-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ripe-insurance/openapi/ripe-insurance-media-api-openapi.yml
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
  - summary: Site interference
    text: Interference or entry to the Site with intent to corrupt, damage or deny service from the Site or for other commercial benefit shall be taken seriously
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
name: Ripe Insurance
provenance_date: '2026-11-10'
provider_name: Ripe Insurance
provider_slug: ripe-insurance
slug: ripe-insurance-eligibility
source_date: '2026-11-10'
source_filename: ripe-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.ripeinsurance.co.uk/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ripe Insurance\naid: ripe-insurance\nurl: https://www.ripeinsurance.co.uk/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Site interference\n  text: Interference or entry to the Site with intent to corrupt, damage or deny service from the Site or for other\n    commercial benefit shall be taken seriously\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ripe-insurance/eligibility/ripe-insurance-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Ripe Insurance's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- United Kingdom
- Insurtech
- Managing General Agent
- Specialist Insurance
- Personal Lines
- Small Business Insurance
- Underwriting
- Direct to Consumer
- Brokerage
---
