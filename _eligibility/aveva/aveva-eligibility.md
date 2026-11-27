---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: In accessing and using the Website, you affirm that you are not located in Cuba, Iran, North Korea, Syria, or the restricted regions of Ukraine
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Weapons proliferation and restricted activities
    text: you are not accessing or using the Website for any purpose relating to nuclear, chemical or biological weapons proliferation or other restricted nuclear activities, missile or rocket systems, military intelligence, or unauthorized surveillance.
  - summary: Sanctioned or export-restricted users
    text: that you are not subject to sanctions or export restrictions prohibiting your access or use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AVEVA
provenance_date: '2026-11-09'
provider_name: AVEVA
provider_slug: aveva
slug: aveva-eligibility
source_date: '2026-11-09'
source_filename: aveva-eligibility.yml
source_heading: Eligibility
source_page: https://www.aveva.com/en/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AVEVA\naid: aveva\nurl: https://www.aveva.com/en/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: In accessing and using the Website, you affirm that you are not located in Cuba, Iran, North Korea, Syria,\n    or the restricted regions of Ukraine\nentity_types: []\nrestricted_uses:\n- summary: Weapons proliferation and restricted activities\n  text: you are not accessing or using the Website for any purpose relating to nuclear, chemical or biological weapons\n    proliferation or other restricted nuclear activities, missile or rocket\
  \ systems, military intelligence, or unauthorized\n    surveillance.\n- summary: Sanctioned or export-restricted users\n  text: that you are not subject to sanctions or export restrictions prohibiting your access or use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aveva/eligibility/aveva-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from AVEVA's own page on 2026-11-09.
synthetic: false
tags:
- SCADA
- MES
- Industrial Automation
- Manufacturing
- Industrial IoT
- Industrial Data
- Energy
- Industrial
---
