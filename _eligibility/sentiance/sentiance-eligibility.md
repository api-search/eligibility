---
api_specs:
- filename: sentiance-openapi-generated.yml
  format: yaml
  label: Sentiance API
  slug: sentiance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentiance/openapi/_ae-authored/sentiance-openapi-generated.yml
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
  - summary: No vulgar or obscene app content
    text: the Mobile Application does not infringe upon third party rights and is not vulgar, profane, pornographic or obscene
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
name: Sentiance
provenance_date: '2026-11-10'
provider_name: Sentiance
provider_slug: sentiance
slug: sentiance-eligibility
source_date: '2026-11-10'
source_filename: sentiance-eligibility.yml
source_heading: Eligibility
source_page: https://sentiance.com/sdk-license-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sentiance\naid: sentiance\nurl: https://sentiance.com/sdk-license-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No vulgar or obscene app content\n  text: the Mobile Application does not infringe upon third party rights and is not vulgar, profane, pornographic\n    or obscene\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sentiance/eligibility/sentiance-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sentiance's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Behavioral-Intelligence
- Mobile
- Privacy
- On-Device
---
