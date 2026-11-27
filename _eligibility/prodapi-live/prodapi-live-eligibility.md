---
api_specs:
- filename: prodapi-live-openapi-generated.yml
  format: yaml
  label: prodapi-live API
  slug: prodapi-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prodapi-live/openapi/_ae-authored/prodapi-live-openapi-generated.yml
claim_count: 2
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
  - summary: Lawful use only
    text: Customers must use the APIs lawfully, provide only inputs they are entitled to process and respect third-party websites, platform rules, privacy rights and intellectual-property rights.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Assisted and pilot services require written activation before access is provisioned.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: prodapi-live
provenance_date: '2026-11-10'
provider_name: prodapi-live
provider_slug: prodapi-live
slug: prodapi-live-eligibility
source_date: '2026-11-10'
source_filename: prodapi-live-eligibility.yml
source_heading: Eligibility
source_page: https://prodapi.live/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: prodapi-live\naid: prodapi-live\nurl: https://prodapi.live/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: Customers must use the APIs lawfully, provide only inputs they are entitled to process and respect third-party\n    websites, platform rules, privacy rights and intellectual-property rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Assisted and pilot services require written activation before access is provisioned.\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/prodapi-live/eligibility/prodapi-live-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from prodapi-live's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Artificial Intelligence
- Data Extraction
- Monitoring
---
