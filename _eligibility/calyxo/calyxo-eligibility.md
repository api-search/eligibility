---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The product information provided on the Site is intended solely for residents in the United States.
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: Company grants you a non-transferable, non-exclusive, revocable, limited license to use and access the Site solely for your own personal, noncommercial use.
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
name: Calyxo
provenance_date: '2026-11-09'
provider_name: Calyxo
provider_slug: calyxo
slug: calyxo-eligibility
source_date: '2026-11-09'
source_filename: calyxo-eligibility.yml
source_heading: Eligibility
source_page: https://calyxoinc.com/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calyxo\naid: calyxo\nurl: https://calyxoinc.com/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The product information provided on the Site is intended solely for residents in the United States.\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: Company grants you a non-transferable, non-exclusive, revocable, limited license to use and access the Site\n    solely for your own personal, noncommercial\
  \ use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/calyxo/eligibility/calyxo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Calyxo's own page on 2026-11-09.
synthetic: false
tags:
- Medical Devices
- Kidney Stone Care
- Healthcare
- Innovation
- Series F
---
