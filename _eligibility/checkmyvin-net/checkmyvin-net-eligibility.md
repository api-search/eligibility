---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: CheckMyVIN is free to use without an account for individuals checking vehicles they intend to buy, own, or have an interest in.
    type: individual
  minimum_age:
    text: By using CheckMyVIN you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No locating or harassing owners
    text: use the site to try to identify, locate or harass a vehicle's owner
  - summary: No unlawful use
    text: use CheckMyVIN for anything unlawful, or in breach of the rules of the card networks and payment methods used to pay for it
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
name: CheckMyVIN
provenance_date: '2026-11-09'
provider_name: CheckMyVIN
provider_slug: checkmyvin-net
slug: checkmyvin-net-eligibility
source_date: '2026-11-09'
source_filename: checkmyvin-net-eligibility.yml
source_heading: Eligibility
source_page: https://checkmyvin.net/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CheckMyVIN\naid: checkmyvin-net\nurl: https://checkmyvin.net/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: CheckMyVIN is free to use without an account for individuals checking vehicles they intend to buy, own,\n    or have an interest in.\nrestricted_uses:\n- summary: No locating or harassing owners\n  text: use the site to try to identify, locate or harass a vehicle's owner\n- summary: No unlawful use\n  text: use CheckMyVIN for anything unlawful, or in breach of the rules of the card networks and payment methods\n\
  \    used to pay for it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using CheckMyVIN you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/checkmyvin-net/eligibility/checkmyvin-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CheckMyVIN's own page on 2026-11-09.
synthetic: false
tags:
- Company
- VIN
- Automotive
- NHTSA
- Free
---
