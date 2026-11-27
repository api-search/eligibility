---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Level Services provided or accessed through or on the Level Sites or through the Level Software are not available to all persons or in all countries.
  entity_types:
  - text: You represent that you are of sufficient legal age in your jurisdiction or residence to use or access the Level Services and Products
    type: individual
  minimum_age:
    text: Any use or access to the Level Services and Products by individuals under the age of 13 (or the equivalent minimum age in the applicable jurisdiction) is strictly prohibited
    value: '13'
  restricted_uses:
  - summary: No emergency response use
    text: the Level Services and Products, whether standing alone or when interfaced with Third-Party Products or Services, are not certified for emergency response and agree not to use the Level Services and Products for this purpose.
  - summary: No time-critical or life safety reliance
    text: YOU AGREE NOT TO RELY ON THE LEVEL SERVICES FOR ANY TIME-CRITICAL OR LIFE SAFETY PURPOSES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Level Services and Products, you must sign up for a user account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Level Home
provenance_date: '2026-11-09'
provider_name: Level Home
provider_slug: level-home
slug: level-home-eligibility
source_date: '2026-11-09'
source_filename: level-home-eligibility.yml
source_heading: Eligibility
source_page: https://level.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Level Home\naid: level-home\nurl: https://level.co/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the Level Services provided or accessed through or on the Level Sites or through the Level Software are\n    not available to all persons or in all countries.\nentity_types:\n- type: individual\n  text: You represent that you are of sufficient legal age in your jurisdiction or residence to use or access the\n    Level Services and Products\nrestricted_uses:\n- summary: No emergency response use\n  text: the Level Services and Products, whether standing alone or when\
  \ interfaced with Third-Party Products or\n    Services, are not certified for emergency response and agree not to use the Level Services and Products for\n    this purpose.\n- summary: No time-critical or life safety reliance\n  text: YOU AGREE NOT TO RELY ON THE LEVEL SERVICES FOR ANY TIME-CRITICAL OR LIFE SAFETY PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Level Services and Products, you must sign up for a user account\nminimum_age:\n  value: '13'\n  text: Any use or access to the Level Services and Products by individuals under the age of 13 (or the equivalent\n    minimum age in the applicable jurisdiction) is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/level-home/eligibility/level-home-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Level Home's own page on 2026-11-09.
synthetic: false
tags:
- Smart Lock
- Smart Home
- Home Automation
- IoT
- Access Control
- Matter
- Threads
- Bluetooth LE
- apple-home-key
- Consumer Hardware
- Multifamily
- PropTech
- GraphQL
---
