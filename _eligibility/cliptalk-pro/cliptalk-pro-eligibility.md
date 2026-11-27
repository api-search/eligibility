---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that Company Properties are appropriate or available for use in other locations.
  entity_types:
  - text: You represent that you are (i) at least thirteen (13) years old
    type: individual
  - text: you have the authority to enter into the terms of use personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: Commercial activities without consent
    text: involves commercial activities and/or sales, such as contests, sweepstakes, barter, advertising, or pyramid schemes without Company’s prior written consent
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
name: ClipTalk
provenance_date: '2026-11-09'
provider_name: ClipTalk
provider_slug: cliptalk-pro
slug: cliptalk-pro-eligibility
source_date: '2026-11-09'
source_filename: cliptalk-pro-eligibility.yml
source_heading: Eligibility
source_page: https://www.cliptalk.pro/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClipTalk\naid: cliptalk-pro\nurl: https://www.cliptalk.pro/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that Company Properties are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You represent that you are (i) at least thirteen (13) years old\n- type: business\n  text: you have the authority to enter into the terms of use personally or on behalf of the entity you have named\n    as the user\nrestricted_uses:\n- summary: Commercial activities without consent\n  text:\
  \ involves commercial activities and/or sales, such as contests, sweepstakes, barter, advertising, or pyramid\n    schemes without Company’s prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/cliptalk-pro/eligibility/cliptalk-pro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ClipTalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Social Media
- Automation
---
