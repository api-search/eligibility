---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PlayQ makes no representations that the Services are appropriate or available for use in other locations.
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old
    value: '13'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You represent that you are (i) at least thirteen (13) years old; (ii) of legal age to form a binding contract
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PlayQ
provenance_date: '2026-11-10'
provider_name: PlayQ
provider_slug: playq
slug: playq-eligibility
source_date: '2026-11-10'
source_filename: playq-eligibility.yml
source_heading: Eligibility
source_page: https://www.playq.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlayQ\naid: playq\nurl: https://www.playq.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PlayQ makes no representations that the Services are appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You represent that you are (i) at least thirteen (13) years old; (ii) of legal age to form a binding contract\nminimum_age:\n  value: '13'\n  text: You represent that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/playq/eligibility/playq-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from PlayQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Game Development
- Entertainment
- Free-to-Play
---
