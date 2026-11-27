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
  - summary: Illegal content
    text: Transmit illegal content under Norwegian or EU law
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
name: runlocal-eu
provenance_date: '2026-11-10'
provider_name: runlocal-eu
provider_slug: runlocal-eu
slug: runlocal-eu-eligibility
source_date: '2026-11-10'
source_filename: runlocal-eu-eligibility.yml
source_heading: Eligibility
source_page: https://runlocal.eu/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: runlocal-eu\naid: runlocal-eu\nurl: https://runlocal.eu/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal content\n  text: Transmit illegal content under Norwegian or EU law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runlocal-eu/eligibility/runlocal-eu-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from runlocal-eu's own page on 2026-11-10.
synthetic: false
tags:
- Developer Tools
- Networking
- Security
- Privacy
- EU
---
