---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Sites and the App are intended for use by United Kingdom residents only.
  entity_types:
  - text: You must be at least 17 years of age to download the App.
    type: individual
  - source: https://www.bymiles.co.uk/terms-of-business
    text: “You” refers to the individual asking us to work on your behalf under these terms of business.
    type: individual
  minimum_age:
    text: You must be at least 17 years of age to download the App.
    value: '17'
  restricted_uses:
  - summary: Driving use of app
    text: Remember, you should never use the App while driving or in control of your vehicle.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    source: https://www.bymiles.co.uk/terms-of-business
    text: we or our partners may need to perform a credit search on you and any additional drivers in order to check your identity and assess your credit score.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: By Miles
provenance_date: '2026-11-09'
provider_name: By Miles
provider_slug: by-miles
slug: by-miles-eligibility
source_date: '2026-11-09'
source_filename: by-miles-eligibility.yml
source_heading: Eligibility
source_page: https://www.bymiles.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: By Miles\naid: by-miles\nurl: https://www.bymiles.co.uk/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.bymiles.co.uk/terms\n  - https://www.bymiles.co.uk/terms-of-business\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Sites and the App are intended for use by United Kingdom residents only.\nentity_types:\n- type: individual\n  text: You must be at least 17 years of age to download the App.\n- type: individual\n  text: “You” refers to the individual asking us to work on your behalf under these terms of business.\n  source: https://www.bymiles.co.uk/terms-of-business\nrestricted_uses:\n\
  - summary: Driving use of app\n  text: Remember, you should never use the App while driving or in control of your vehicle.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we or our partners may need to perform a credit search on you and any additional drivers in order to check\n    your identity and assess your credit score.\n  source: https://www.bymiles.co.uk/terms-of-business\nminimum_age:\n  value: '17'\n  text: You must be at least 17 years of age to download the App.\n"
source_yaml_url: https://artifacts.apis.io/by-miles/eligibility/by-miles-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from By Miles's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United Kingdom
- Insurtech
- Property and Casualty
- Auto Insurance
- Usage-Based Insurance
- Telematics
- Connected Vehicles
- Direct to Consumer
- Open Banking
---
