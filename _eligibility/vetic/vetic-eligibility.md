---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You may access the Service only in geographic locations within India.
  entity_types:
  - text: The Service is not available to persons, under the age of 18 (eighteen) years or to any User suspended or removed from the Platform for any reason whatsoever.
    type: individual
  minimum_age:
    text: The Service is not available to persons, under the age of 18 (eighteen) years
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: This license is for the sole purpose of enabling You to use and enjoy the benefit of the Service for Your personal and non-commercial use
  - summary: No public performances
    text: You agree not to use the Service for any public performances.
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
name: Vetic
provenance_date: '2026-11-10'
provider_name: Vetic
provider_slug: vetic
slug: vetic-eligibility
source_date: '2026-11-10'
source_filename: vetic-eligibility.yml
source_heading: Eligibility
source_page: https://vetic.in/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vetic\naid: vetic\nurl: https://vetic.in/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You may access the Service only in geographic locations within India.\nentity_types:\n- type: individual\n  text: The Service is not available to persons, under the age of 18 (eighteen) years or to any User suspended or\n    removed from the Platform for any reason whatsoever.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: This license is for the sole purpose of enabling You to use and enjoy the benefit of the Service for Your\n    personal and non-commercial\
  \ use\n- summary: No public performances\n  text: You agree not to use the Service for any public performances.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not available to persons, under the age of 18 (eighteen) years\n"
source_yaml_url: https://artifacts.apis.io/vetic/eligibility/vetic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vetic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Pet Care
- Veterinary
- Pet Healthcare
- Animal Health
- Mobile App
- India
- Diagnostics
- Pharmacy
---
