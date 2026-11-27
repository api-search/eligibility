---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU, AND ANY USERS OF A MEGA BUSINESS ACCOUNT OF WHICH YOU ARE THE ADMINISTRATOR, MUST BE AT LEAST 18 YEARS OF AGE
    type: individual
  minimum_age:
    text: YOU, AND ANY USERS OF A MEGA BUSINESS ACCOUNT OF WHICH YOU ARE THE ADMINISTRATOR, MUST BE AT LEAST 18 YEARS OF AGE, OR THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU OR THEY RESIDE, TO USE OUR SERVICES.
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: undertake any unlawful, illicit, criminal or illegal activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: comply fully with any account verification protocols we require you to follow, including account verification via SMS
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MEGA
provenance_date: '2026-11-10'
provider_name: MEGA
provider_slug: mega-nz
slug: mega-nz-eligibility
source_date: '2026-11-10'
source_filename: mega-nz-eligibility.yml
source_heading: Eligibility
source_page: https://mega.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MEGA\naid: mega-nz\nurl: https://mega.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU, AND ANY USERS OF A MEGA BUSINESS ACCOUNT OF WHICH YOU ARE THE ADMINISTRATOR, MUST BE AT LEAST 18 YEARS\n    OF AGE\nrestricted_uses:\n- summary: Illegal activity\n  text: undertake any unlawful, illicit, criminal or illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: comply fully with any account verification protocols we require you to follow, including account verification\n\
  \    via SMS\nminimum_age:\n  value: '18'\n  text: YOU, AND ANY USERS OF A MEGA BUSINESS ACCOUNT OF WHICH YOU ARE THE ADMINISTRATOR, MUST BE AT LEAST 18 YEARS\n    OF AGE, OR THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU OR THEY RESIDE, TO USE OUR SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/mega-nz/eligibility/mega-nz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from MEGA's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
