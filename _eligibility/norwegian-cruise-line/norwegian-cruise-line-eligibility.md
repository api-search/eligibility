---
claim_count: 4
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
  - summary: Pregnancy limit
    text: Norwegian Cruise Line cannot accept guests who will have entered their 24th week of pregnancy by the beginning of, or at any time during the cruise
  - summary: Infant age limit
    text: no infants under the age of six (6) months shall be permitted to board and/or sail on the vessel.
  - summary: Unfit for travel
    text: Norwegian Cruise Line has the right to refuse or revoke passage to anyone who, in its judgment, is in a physical or mental condition unfit for travel
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All guests must provide their full legal name exactly as it appears on their passport or required travel documentation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Norwegian Cruise Line Holdings
provenance_date: '2026-11-10'
provider_name: Norwegian Cruise Line Holdings
provider_slug: norwegian-cruise-line
slug: norwegian-cruise-line-eligibility
source_date: '2026-11-10'
source_filename: norwegian-cruise-line-eligibility.yml
source_heading: Eligibility
source_page: https://www.ncl.com/terms#legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Norwegian Cruise Line Holdings\naid: norwegian-cruise-line\nurl: https://www.ncl.com/terms#legal-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Pregnancy limit\n  text: Norwegian Cruise Line cannot accept guests who will have entered their 24th week of pregnancy by the beginning\n    of, or at any time during the cruise\n- summary: Infant age limit\n  text: no infants under the age of six (6) months shall be permitted to board and/or sail on the vessel.\n- summary: Unfit for travel\n  text: Norwegian\
  \ Cruise Line has the right to refuse or revoke passage to anyone who, in its judgment, is in a\n    physical or mental condition unfit for travel\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All guests must provide their full legal name exactly as it appears on their passport or required travel\n    documentation.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/norwegian-cruise-line/eligibility/norwegian-cruise-line-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Norwegian Cruise Line Holdings's own page on 2026-11-10.
synthetic: false
tags:
- Cruise Lines
- Travel
- Hospitality
- Leisure
- Publicly Traded
---
