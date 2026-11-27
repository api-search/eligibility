---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: At this time, we can only process and ship orders within the United States of America and Canada.
  entity_types:
  - text: Marketplace access is available to individual accounts only.
    type: individual
  - text: No corporate account or service-provider account associated with a corporate account may sell products in the Marketplace.
    type: business
  minimum_age:
    text: By agreeing to these Terms, you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Weapons and firearms
    text: Is not designed or intended to be used as or to manufacture, assemble, complete, repair, modify, convert, conceal, or facilitate the use of, any weapon, firearm, firearm frame, firearm receiver
  - summary: Vehicle, hazardous, or fail-safe uses (Marketplace)
    text: Is not designed or intended to be used (a) as a structural part in a vehicle, (b) in hazardous or mission-critical circumstances, (c) or in circumstances requiring fail-safe performance.
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
name: SendCutSend
provenance_date: '2026-11-10'
provider_name: SendCutSend
provider_slug: sendcutsend
slug: sendcutsend-eligibility
source_date: '2026-11-10'
source_filename: sendcutsend-eligibility.yml
source_heading: Eligibility
source_page: https://sendcutsend.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SendCutSend\naid: sendcutsend\nurl: https://sendcutsend.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: At this time, we can only process and ship orders within the United States of America and Canada.\nentity_types:\n- type: individual\n  text: Marketplace access is available to individual accounts only.\n- type: business\n  text: No corporate account or service-provider account associated with a corporate account may sell products in\n    the Marketplace.\nrestricted_uses:\n- summary: Weapons and firearms\n  text: Is not designed or intended to\
  \ be used as or to manufacture, assemble, complete, repair, modify, convert,\n    conceal, or facilitate the use of, any weapon, firearm, firearm frame, firearm receiver\n- summary: Vehicle, hazardous, or fail-safe uses (Marketplace)\n  text: Is not designed or intended to be used (a) as a structural part in a vehicle, (b) in hazardous or mission-critical\n    circumstances, (c) or in circumstances requiring fail-safe performance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By agreeing to these Terms, you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/sendcutsend/eligibility/sendcutsend-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from SendCutSend's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Laser Cutting
- Sheet Metal Fabrication
- CNC Machining
- Waterjet Cutting
- Custom Manufacturing
- On-Demand Manufacturing
---
