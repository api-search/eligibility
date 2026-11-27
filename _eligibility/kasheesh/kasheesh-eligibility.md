---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for users over the age of eighteen (18) who are located in the United States.
  entity_types:
  - text: The Services are for personal use only.
    type: individual
  minimum_age:
    text: The Services are intended for users over the age of eighteen (18)
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: you will not use the Services for or on behalf for any other entity or person.
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
name: Kasheesh
provenance_date: '2026-11-09'
provider_name: Kasheesh
provider_slug: kasheesh
slug: kasheesh-eligibility
source_date: '2026-11-09'
source_filename: kasheesh-eligibility.yml
source_heading: Eligibility
source_page: https://www.kasheesh.co/legal-documents/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kasheesh\naid: kasheesh\nurl: https://www.kasheesh.co/legal-documents/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for users over the age of eighteen (18) who are located in the United States.\nentity_types:\n- type: individual\n  text: The Services are for personal use only.\nrestricted_uses:\n- summary: Personal use only\n  text: you will not use the Services for or on behalf for any other entity or person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The\
  \ Services are intended for users over the age of eighteen (18)\n"
source_yaml_url: https://artifacts.apis.io/kasheesh/eligibility/kasheesh-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kasheesh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Consumer Finance
- Credit Cards
- Card Splitting
- Mastercard
- Rewards
---
