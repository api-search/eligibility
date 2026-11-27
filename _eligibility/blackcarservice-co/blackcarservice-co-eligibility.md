---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract under California law to make a reservation.
    type: individual
  - text: If you are booking on behalf of another passenger or a company, you represent that you have authority to do so and to bind that passenger or company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract under California law to make a reservation.
    value: '18'
  restricted_uses:
  - summary: Illegal items and conduct in vehicle
    text: Carry, use, or transport illegal drugs or unlawful firearms.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We may refuse or cancel a reservation if (i) the requested service is outside our permitted operating area, (ii) we cannot reasonably verify your identity or payment method
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Black Car Service
provenance_date: '2026-11-09'
provider_name: Black Car Service
provider_slug: blackcarservice-co
slug: blackcarservice-co-eligibility
source_date: '2026-11-09'
source_filename: blackcarservice-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.blackcarservice.co/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Black Car Service\naid: blackcarservice-co\nurl: https://www.blackcarservice.co/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract under California law to make a reservation.\n- type: business\n  text: If you are booking on behalf of another passenger or a company, you represent that you have authority to\n    do so and to bind that passenger or company to these Terms.\nrestricted_uses:\n- summary: Illegal items and conduct in vehicle\n  text: Carry,\
  \ use, or transport illegal drugs or unlawful firearms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We may refuse or cancel a reservation if (i) the requested service is outside our permitted operating area,\n    (ii) we cannot reasonably verify your identity or payment method\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract under California law to make a reservation.\n"
source_yaml_url: https://artifacts.apis.io/blackcarservice-co/eligibility/blackcarservice-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Black Car Service's own page on 2026-11-09.
synthetic: false
tags:
- Chauffeur
- Airport Transfer
- Hourly Service
- Napa Transportation
- Corporate Travel
- Private Car Service
---
