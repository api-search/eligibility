---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: WebBeds is a global B2B travel marketplace servicing the travel trade, an intermediary connecting hotels and suppliers with travel buyers all around the world.
    type: business
  minimum_age:
    text: null
    value: null
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
name: WebBeds
provenance_date: '2026-11-10'
provider_name: WebBeds
provider_slug: webbeds
slug: webbeds-eligibility
source_date: '2026-11-10'
source_filename: webbeds-eligibility.yml
source_heading: Eligibility
source_page: https://www.webbeds.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WebBeds\naid: webbeds\nurl: https://www.webbeds.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: WebBeds is a global B2B travel marketplace servicing the travel trade, an intermediary connecting hotels\n    and suppliers with travel buyers all around the world.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/webbeds/eligibility/webbeds-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from WebBeds's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Marketplace
- B2B
- Hospitality
---
