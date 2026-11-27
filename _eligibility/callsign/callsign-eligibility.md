---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The App is intended for use only by persons who are at least 18 years of age.
    type: individual
  - text: you (or the business you work for) must be subscribed to the Callsign services in order to use the App
    type: business
  minimum_age:
    text: The App is intended for use only by persons who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: only for lawful purposes (complying with all applicable laws and regulations), and in a responsible manner
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
name: CallSign
provenance_date: '2026-11-09'
provider_name: CallSign
provider_slug: callsign
slug: callsign-eligibility
source_date: '2026-11-09'
source_filename: callsign-eligibility.yml
source_heading: Eligibility
source_page: https://www.callsign.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallSign\naid: callsign\nurl: https://www.callsign.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The App is intended for use only by persons who are at least 18 years of age.\n- type: business\n  text: you (or the business you work for) must be subscribed to the Callsign services in order to use the App\nrestricted_uses:\n- summary: Lawful purposes only\n  text: only for lawful purposes (complying with all applicable laws and regulations), and in a responsible manner\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The App is intended for use only by persons who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/callsign/eligibility/callsign-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CallSign's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Identity
- Authentication
- Fraud Prevention
- Behavioral Biometrics
- Security
- Fintech
---
