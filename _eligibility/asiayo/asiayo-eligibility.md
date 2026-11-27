---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be at least 18 years of age (or has reached the statutory adult age at your home country or region) and have the full capacity to conduct transactions.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent bookings
    text: If AsiaYo detects any suspicious transaction records, potentially involving unauthorized use or activity not conducted by the account holder, it reserves the right to suspend or reject the transaction
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
name: Asiayo
provenance_date: '2026-11-09'
provider_name: Asiayo
provider_slug: asiayo
slug: asiayo-eligibility
source_date: '2026-11-09'
source_filename: asiayo-eligibility.yml
source_heading: Eligibility
source_page: https://asiayo.com/en-us/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asiayo\naid: asiayo\nurl: https://asiayo.com/en-us/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fraudulent bookings\n  text: If AsiaYo detects any suspicious transaction records, potentially involving unauthorized use or activity\n    not conducted by the account holder, it reserves the right to suspend or reject the transaction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age (or has reached the statutory\
  \ adult age at your home country or region)\n    and have the full capacity to conduct transactions.\n"
source_yaml_url: https://artifacts.apis.io/asiayo/eligibility/asiayo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Asiayo's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Marketplace
- Booking
- Tours
- Hospitality
---
