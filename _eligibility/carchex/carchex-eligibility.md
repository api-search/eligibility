---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CARCHEX makes no claims that the Site may be lawfully viewed, accessed or used outside the United States.
  entity_types:
  - text: you acknowledge that you are a legal adult age 18 or older
    type: individual
  minimum_age:
    text: YOU ACKNOWLEDGE THAT YOU ARE A LEGAL ADULT AGE 18 OR OLDER.
    value: '18'
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
name: Carchex
provenance_date: '2026-11-09'
provider_name: Carchex
provider_slug: carchex
slug: carchex-eligibility
source_date: '2026-11-09'
source_filename: carchex-eligibility.yml
source_heading: Eligibility
source_page: https://www.carchex.com/about-us/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carchex\naid: carchex\nurl: https://www.carchex.com/about-us/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CARCHEX makes no claims that the Site may be lawfully viewed, accessed or used outside the United States.\nentity_types:\n- type: individual\n  text: you acknowledge that you are a legal adult age 18 or older\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ACKNOWLEDGE THAT YOU ARE A LEGAL ADULT AGE 18 OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/carchex/eligibility/carchex-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Carchex's own page on 2026-11-09.
synthetic: false
tags:
- VehicleProtection
- Warranty
- Automotive
- US
- Insurance
---
