---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The account is personal and non-transferable; you are responsible for keeping your password safe.
    type: individual
  minimum_age:
    text: The service is intended for persons aged 18 or over (the content concerns alcoholic beverages).
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Membership entitles you to personal, non-commercial use.
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
name: bordeaux.guru
provenance_date: '2026-11-09'
provider_name: bordeaux.guru
provider_slug: bordeaux-guru
slug: bordeaux-guru-eligibility
source_date: '2026-11-09'
source_filename: bordeaux-guru-eligibility.yml
source_heading: Eligibility
source_page: https://bordeaux.guru/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bordeaux.guru\naid: bordeaux-guru\nurl: https://bordeaux.guru/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The account is personal and non-transferable; you are responsible for keeping your password safe.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Membership entitles you to personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The service is intended for persons aged 18 or over (the content concerns\
  \ alcoholic beverages).\n"
source_yaml_url: https://artifacts.apis.io/bordeaux-guru/eligibility/bordeaux-guru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from bordeaux.guru's own page on 2026-11-09.
synthetic: false
tags:
- Wine
- Vintage
- En Primeur
- Data
- Analytics
- Company
---
