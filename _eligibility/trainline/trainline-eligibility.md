---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We provide booking services for a wide range of train, coach and bus services in the UK, across Europe and beyond.
  entity_types:
  - text: You must be aged 16 or over to use our booking service and if you’re 16 or 17, you’ll need your parent or guardian’s permission.
    type: individual
  minimum_age:
    text: You must be aged 16 or over to use our booking service and if you’re 16 or 17, you’ll need your parent or guardian’s permission.
    value: '16'
  restricted_uses:
  - summary: Refusal of underage or inappropriate use
    text: We reserve the right to refuse access to our website or apps, or to reject a transaction made using our booking service if you are underage, or if we otherwise deem it appropriate to do so.
  - source: https://tps.thetrainline.com/terms-and-conditions/
    summary: Prohibited website uses
    text: Using the Website to violate any applicable laws or regulations;
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
name: Trainline
provenance_date: '2026-11-10'
provider_name: Trainline
provider_slug: trainline
slug: trainline-eligibility
source_date: '2026-11-10'
source_filename: trainline-eligibility.yml
source_heading: Eligibility
source_page: https://www.thetrainline.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trainline\naid: trainline\nurl: https://www.thetrainline.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://tps.thetrainline.com/terms-and-conditions/\n  - https://www.thetrainline.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: We provide booking services for a wide range of train, coach and bus services in the UK, across Europe and\n    beyond.\nentity_types:\n- type: individual\n  text: You must be aged 16 or over to use our booking service and if you’re 16 or 17, you’ll need your parent or\n    guardian’s permission.\nrestricted_uses:\n- summary: Refusal of underage\
  \ or inappropriate use\n  text: We reserve the right to refuse access to our website or apps, or to reject a transaction made using our\n    booking service if you are underage, or if we otherwise deem it appropriate to do so.\n- summary: Prohibited website uses\n  text: Using the Website to violate any applicable laws or regulations;\n  source: https://tps.thetrainline.com/terms-and-conditions/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be aged 16 or over to use our booking service and if you’re 16 or 17, you’ll need your parent or\n    guardian’s permission.\n"
source_yaml_url: https://artifacts.apis.io/trainline/eligibility/trainline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Trainline's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Rail
- United Kingdom
- Europe
- Booking
- Ticketing
- Distribution
- OTA
- Corporate Travel
---
