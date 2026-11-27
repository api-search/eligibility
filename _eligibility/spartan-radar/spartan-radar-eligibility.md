---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with the Company.
    value: legal age
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Spartan Radar
provenance_date: '2026-11-10'
provider_name: Spartan Radar
provider_slug: spartan-radar
slug: spartan-radar-eligibility
source_date: '2026-11-10'
source_filename: spartan-radar-eligibility.yml
source_heading: Eligibility
source_page: https://www.spartanradar.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spartan Radar\naid: spartan-radar\nurl: https://www.spartanradar.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with\n    the Company.\n"
source_yaml_url: https://artifacts.apis.io/spartan-radar/eligibility/spartan-radar-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Spartan Radar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automotive
- Radar
- Sensors
- ADAS
- Autonomous Vehicles
- Perception
- Signal Processing
- Commercial Vehicles
- Embedded Software
- Safety
---
