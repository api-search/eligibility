---
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
  - summary: Accounts you own or manage
    text: Use Adwarp only on accounts you own or are allowed to manage
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
name: Adwarp
provenance_date: '2026-11-09'
provider_name: Adwarp
provider_slug: adwarp-dev
slug: adwarp-dev-eligibility
source_date: '2026-11-09'
source_filename: adwarp-dev-eligibility.yml
source_heading: Eligibility
source_page: https://adwarp.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adwarp\naid: adwarp-dev\nurl: https://adwarp.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Accounts you own or manage\n  text: Use Adwarp only on accounts you own or are allowed to manage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adwarp-dev/eligibility/adwarp-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Adwarp's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Open Source
- CLI
- LinkedIn
- Google Ads
---
