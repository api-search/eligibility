---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The User refers to an adult individual who registers an account with Brighterly
    type: individual
  minimum_age:
    text: To register for the Service, You must be over the age of 18.
    value: '18'
  restricted_uses:
  - summary: No illegal or unauthorized use
    text: You will not use the Service for any illegal or unauthorized purpose
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
name: Brightly
provenance_date: '2026-11-09'
provider_name: Brightly
provider_slug: brightly
slug: brightly-eligibility
source_date: '2026-11-09'
source_filename: brightly-eligibility.yml
source_heading: Eligibility
source_page: https://brighterly.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightly\naid: brightly\nurl: https://brighterly.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The User refers to an adult individual who registers an account with Brighterly\nrestricted_uses:\n- summary: No illegal or unauthorized use\n  text: You will not use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To register for the Service, You must be over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/brightly/eligibility/brightly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Brightly's own page on 2026-11-09.
synthetic: false
tags:
- Education
- K-12
- Tutoring
- Math
- Reading
- Online
---
