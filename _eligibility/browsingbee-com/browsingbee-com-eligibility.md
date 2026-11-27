---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 or older, and if under 18 have a parent or guardian agree to these terms.
    type: individual
  minimum_age:
    text: You must be 13 or older
    value: '13'
  restricted_uses:
  - summary: Acceptable use limits
    text: 'Do not use BrowsingBee to: access content you are not allowed to access'
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
name: BrowsingBee
provenance_date: '2026-11-09'
provider_name: BrowsingBee
provider_slug: browsingbee-com
slug: browsingbee-com-eligibility
source_date: '2026-11-09'
source_filename: browsingbee-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.browsingbee.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrowsingBee\naid: browsingbee-com\nurl: https://www.browsingbee.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 or older, and if under 18 have a parent or guardian agree to these terms.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: 'Do not use BrowsingBee to: access content you are not allowed to access'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older\n"
source_yaml_url: https://artifacts.apis.io/browsingbee-com/eligibility/browsingbee-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BrowsingBee's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Browser
- Connector
- Claude
- ChatGPT
---
