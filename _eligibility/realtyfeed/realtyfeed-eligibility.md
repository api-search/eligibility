---
api_specs:
- filename: realtyfeed-mls-router-postman.json
  format: json
  label: MLS Router API
  slug: mls-router-api
  spec_type: Postman
  url: https://artifacts.apis.io/realtyfeed/postman/realtyfeed-mls-router-postman.json
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
  - summary: Data submitted must comply with MLS rules
    text: Any data submitted to the platform must comply with MLS rules, licensing agreements, and applicable laws.
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
name: RealtyFeed
provenance_date: '2026-11-10'
provider_name: RealtyFeed
provider_slug: realtyfeed
slug: realtyfeed-eligibility
source_date: '2026-11-10'
source_filename: realtyfeed-eligibility.yml
source_heading: Eligibility
source_page: https://realtyfeed.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RealtyFeed\naid: realtyfeed\nurl: https://realtyfeed.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Data submitted must comply with MLS rules\n  text: Any data submitted to the platform must comply with MLS rules, licensing agreements, and applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/realtyfeed/eligibility/realtyfeed-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from RealtyFeed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- MLS
- RESO Web API
- OData
- IDX
- Property Data
---
