---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You cannot use the Service if you are under 18 years old.
    type: individual
  minimum_age:
    text: You must be 18 or older to use it
    value: '18'
  restricted_uses:
  - summary: Not a replacement for medical treatment
    text: The Service should never be used as a replacement for recommended medical or mental health treatment.
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
name: Noom
provenance_date: '2026-11-10'
provider_name: Noom
provider_slug: noom
slug: noom-eligibility
source_date: '2026-11-10'
source_filename: noom-eligibility.yml
source_heading: Eligibility
source_page: https://www.noom.com/terms-and-conditions-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noom\naid: noom\nurl: https://www.noom.com/terms-and-conditions-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You cannot use the Service if you are under 18 years old.\nrestricted_uses:\n- summary: Not a replacement for medical treatment\n  text: The Service should never be used as a replacement for recommended medical or mental health treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to use it\n"
source_yaml_url: https://artifacts.apis.io/noom/eligibility/noom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Noom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Weight Management
- Wellness
- Behavioral Health
- Telehealth
- Nutrition
- Consumer Health
- Mobile App
---
