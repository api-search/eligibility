---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Service is currently only available to individuals who are located in states in which we offer the Service
  entity_types:
  - text: Our Service is currently only available to individuals who are located in states in which we offer the Service
    type: individual
  minimum_age:
    text: are at least eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Supplements age limit
    text: Supplements are only available to those 18 years of age and older.
  - summary: Controlled substances excluded from CustomRx
    text: Certain controlled substances are not eligible for CustomRx subscriptions.
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
name: Midi Health
provenance_date: '2026-11-10'
provider_name: Midi Health
provider_slug: midi-health
slug: midi-health-eligibility
source_date: '2026-11-10'
source_filename: midi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinmidi.com/legals/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Midi Health\naid: midi-health\nurl: https://www.joinmidi.com/legals/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Our Service is currently only available to individuals who are located in states in which we offer the Service\nentity_types:\n- type: individual\n  text: Our Service is currently only available to individuals who are located in states in which we offer the Service\nrestricted_uses:\n- summary: Supplements age limit\n  text: Supplements are only available to those 18 years of age and older.\n- summary: Controlled substances excluded\
  \ from CustomRx\n  text: Certain controlled substances are not eligible for CustomRx subscriptions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are at least eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/midi-health/eligibility/midi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Midi Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Health
- Telehealth
- Women's Health
- Menopause
- Digital Health
---
