---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16 or older to use TrickyBird, and by using it you confirm that you are.
    type: individual
  minimum_age:
    text: You must be 16 or older to use TrickyBird
    value: '16'
  restricted_uses:
  - summary: Copyright infringement
    text: we also close the Premium accounts of people who repeatedly infringe copyright, as our Copyright Policy describes
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
name: TrickyBird
provenance_date: '2026-11-10'
provider_name: TrickyBird
provider_slug: trickybird
slug: trickybird-eligibility
source_date: '2026-11-10'
source_filename: trickybird-eligibility.yml
source_heading: Eligibility
source_page: https://trickybird.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrickyBird\naid: trickybird\nurl: https://trickybird.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16 or older to use TrickyBird, and by using it you confirm that you are.\nrestricted_uses:\n- summary: Copyright infringement\n  text: we also close the Premium accounts of people who repeatedly infringe copyright, as our Copyright Policy\n    describes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 or older to use TrickyBird\n"
source_yaml_url: https://artifacts.apis.io/trickybird/eligibility/trickybird-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TrickyBird's own page on 2026-11-10.
synthetic: false
tags:
- web proxy
- Unblock
- No-install
- Browser
- Agent-Native
- WebMCP
- Llms.txt
- Privacy
- network filtering circumvention
---
