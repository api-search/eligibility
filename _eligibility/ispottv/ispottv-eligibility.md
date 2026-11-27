---
api_specs:
- filename: ispottv-openapi-generated.yml
  format: yaml
  label: iSpot.tv API
  slug: ispottv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ispottv/openapi/_ae-authored/ispottv-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing the iSpot Site from an embargoed country is prohibited; no countries are named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized regulated professional practice
    text: Engaging in the unauthorized practice of any regulated profession, including the financial, legal, or medical/health professions
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
name: iSpot.tv
provenance_date: '2026-11-09'
provider_name: iSpot.tv
provider_slug: ispottv
slug: ispottv-eligibility
source_date: '2026-11-09'
source_filename: ispottv-eligibility.yml
source_heading: Eligibility
source_page: https://www.ispot.tv/hub/agreements/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iSpot.tv\naid: ispottv\nurl: https://www.ispot.tv/hub/agreements/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing the iSpot Site from an embargoed country is prohibited; no countries are named.\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized regulated professional practice\n  text: Engaging in the unauthorized practice of any regulated profession, including the financial, legal, or medical/health\n    professions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ispottv/eligibility/ispottv-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from iSpot.tv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- TV Advertising
- Advertising Measurement
- Analytics
- Attribution
- Media
- Marketing
- Streaming
---
