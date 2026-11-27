---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Any illegal, fraudulent, abusive, improper, or inappropriate use of the Website or a Service
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
name: Pigeonly
provenance_date: '2026-11-10'
provider_name: Pigeonly
provider_slug: pigeonly
slug: pigeonly-eligibility
source_date: '2026-11-10'
source_filename: pigeonly-eligibility.yml
source_heading: Eligibility
source_page: https://pigeonly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pigeonly\naid: pigeonly\nurl: https://pigeonly.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Any illegal, fraudulent, abusive, improper, or inappropriate use of the Website or a Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/pigeonly/eligibility/pigeonly-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Pigeonly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Inmate Communication
- Corrections
- Prison Calls
- Photo Sharing
- Mail
- Consumer
- Communications
---
