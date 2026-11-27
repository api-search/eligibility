---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Masabi Services are provided for the benefit of users who are over the age of 18.
    type: individual
  minimum_age:
    text: Masabi Services are provided for the benefit of users who are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Illegal or disruptive use
    text: use Masabi Services in a manner which may cause Masabi Services to be interrupted, damaged, rendered less efficient
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
name: Masabi
provenance_date: '2026-11-10'
provider_name: Masabi
provider_slug: masabi
slug: masabi-eligibility
source_date: '2026-11-10'
source_filename: masabi-eligibility.yml
source_heading: Eligibility
source_page: https://www.masabi.com/policies/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Masabi\naid: masabi\nurl: https://www.masabi.com/policies/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Masabi Services are provided for the benefit of users who are over the age of 18.\nrestricted_uses:\n- summary: Illegal or disruptive use\n  text: use Masabi Services in a manner which may cause Masabi Services to be interrupted, damaged, rendered less\n    efficient\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Masabi Services are provided\
  \ for the benefit of users who are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/masabi/eligibility/masabi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Masabi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Transit
- Software-as-a-Service
- MobileTicketing
- Open Payments
---
