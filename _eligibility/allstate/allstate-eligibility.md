---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Allstate's products, features, and discounts may not be available in all jurisdictions.
  entity_types:
  - text: The Site is intended for individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Site is intended for individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Personal use only
    text: You may access and use the Site only for personal, noncommercial purposes unless Allstate provides express written permission otherwise.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services is subject to the final determination of underwriting qualifications and acceptance by the company providing such products or services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Allstate
provenance_date: '2026-11-09'
provider_name: Allstate
provider_slug: allstate
slug: allstate-eligibility
source_date: '2026-11-09'
source_filename: allstate-eligibility.yml
source_heading: Eligibility
source_page: https://www.allstate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allstate\naid: allstate\nurl: https://www.allstate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Allstate's products, features, and discounts may not be available in all jurisdictions.\nentity_types:\n- type: individual\n  text: The Site is intended for individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Personal use only\n  text: You may access and use the Site only for personal, noncommercial purposes unless Allstate provides express\n    written permission otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your\
  \ eligibility for particular products and services is subject to the final determination of underwriting\n    qualifications and acceptance by the company providing such products or services.\nminimum_age:\n  value: '13'\n  text: The Site is intended for individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/allstate/eligibility/allstate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Allstate's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Auto Insurance
- Home Insurance
- Life Insurance
- Personal Lines
- Property and Casualty
---
