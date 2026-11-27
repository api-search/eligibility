---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least eighteen (18) years of age and you will supervise any minor or any third party who uses your computer, mobile phone or any other electronic device and/or your name or your account to access the Sites
    type: individual
  - source: https://www.transat.com/en-CA/website-terms-and-conditions
    text: you are at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Non-commercial use of content
    text: TTC grants you a non-exclusive, non-transferable license to use and display the Sites and their Content on your computer, mobile phone or any other electronic device, solely for personal and non-commercial use
  - source: https://www.transat.com/en-CA/website-terms-and-conditions
    summary: Purchases for self or authorized third parties only
    text: you will use the Sites only to purchase travel services for yourself or for third parties who have duly authorized you for these purposes
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
name: Transat
provenance_date: '2026-11-10'
provider_name: Transat
provider_slug: transat
slug: transat-eligibility
source_date: '2026-11-10'
source_filename: transat-eligibility.yml
source_heading: Eligibility
source_page: https://www.airtransat.com/en-CA/legal-notice/terms-of-use-of-the-air-transat-sites
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Transat\naid: transat\nurl: https://www.airtransat.com/en-CA/legal-notice/terms-of-use-of-the-air-transat-sites\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.airtransat.com/en-CA/legal-notice/terms-of-use-of-the-air-transat-sites\n  - https://www.transat.com/en-CA/website-terms-and-conditions\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age and you will supervise any minor or any third party who uses\n    your computer, mobile phone or any other electronic device and/or your name or your account to access\
  \ the Sites\n- type: individual\n  text: you are at least eighteen (18) years of age\n  source: https://www.transat.com/en-CA/website-terms-and-conditions\nrestricted_uses:\n- summary: Non-commercial use of content\n  text: TTC grants you a non-exclusive, non-transferable license to use and display the Sites and their Content\n    on your computer, mobile phone or any other electronic device, solely for personal and non-commercial use\n- summary: Purchases for self or authorized third parties only\n  text: you will use the Sites only to purchase travel services for yourself or for third parties who have duly\n    authorized you for these purposes\n  source: https://www.transat.com/en-CA/website-terms-and-conditions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/transat/eligibility/transat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Transat's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- Distribution
- NDC
- Booking
- Tour Operator
- Corporate Travel
- GDS
---
