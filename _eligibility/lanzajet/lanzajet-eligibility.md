---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Site is intended for and applicable only individuals age 18 or older.
    type: individual
  minimum_age:
    text: This Site is intended for and applicable only individuals age 18 or older.
    value: '18'
  restricted_uses:
  - summary: No unsolicited advertising or solicitation
    text: you will not upload, post, email, or otherwise transmit any advertising or promotional materials or any other form of solicitation or unauthorized communication
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
name: LanzaJet
provenance_date: '2026-11-09'
provider_name: LanzaJet
provider_slug: lanzajet
slug: lanzajet-eligibility
source_date: '2026-11-09'
source_filename: lanzajet-eligibility.yml
source_heading: Eligibility
source_page: https://www.lanzajet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LanzaJet\naid: lanzajet\nurl: https://www.lanzajet.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Site is intended for and applicable only individuals age 18 or older.\nrestricted_uses:\n- summary: No unsolicited advertising or solicitation\n  text: you will not upload, post, email, or otherwise transmit any advertising or promotional materials or any\n    other form of solicitation or unauthorized communication\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: This Site is intended for and applicable only individuals age 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/lanzajet/eligibility/lanzajet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from LanzaJet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Sustainable Aviation Fuel
- Renewable Fuels
- Aviation
- Climate Tech
- Sustainability
- Biofuels
- Carbon Recycling
- Chemicals
---
