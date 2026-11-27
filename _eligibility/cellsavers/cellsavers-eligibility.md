---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: govern the access or use by you, an individual, of content, products, applications, websites, and services
    type: individual
  minimum_age:
    text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to obtain an Account.
    value: '18'
  restricted_uses:
  - summary: Personal, noncommercial use only
    text: solely for your personal/noncommercial use unless otherwise agreed in writing in a separate agreement with you
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Account registration requires you to submit to Puls Technologies, Inc. certain personal information, such as your name, mobile phone number and age, as well as at least one valid form of payment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cellsavers
provenance_date: '2026-11-09'
provider_name: Cellsavers
provider_slug: cellsavers
slug: cellsavers-eligibility
source_date: '2026-11-09'
source_filename: cellsavers-eligibility.yml
source_heading: Eligibility
source_page: https://puls.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cellsavers\naid: cellsavers\nurl: https://puls.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: govern the access or use by you, an individual, of content, products, applications, websites, and services\nrestricted_uses:\n- summary: Personal, noncommercial use only\n  text: solely for your personal/noncommercial use unless otherwise agreed in writing in a separate agreement with\n    you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Account registration requires you to submit to Puls Technologies,\
  \ Inc. certain personal information, such\n    as your name, mobile phone number and age, as well as at least one valid form of payment.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than\n    18), to obtain an Account.\n"
source_yaml_url: https://artifacts.apis.io/cellsavers/eligibility/cellsavers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cellsavers's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Care
- Repair
- Handyman
- Smart Home
- Services
---
