---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Musely's Seller, Muse and Buyer Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: individuals who are 18 years and older
    value: '18'
  restricted_uses:
  - summary: Prescription products
    text: All sales of products that require prescriptions shall be made only in compliance with all laws and regulations that apply in the State in which you reside or are purchasing the Product.
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
name: Musely
provenance_date: '2026-11-10'
provider_name: Musely
provider_slug: musely
slug: musely-eligibility
source_date: '2026-11-10'
source_filename: musely-eligibility.yml
source_heading: Eligibility
source_page: https://www.musely.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Musely\naid: musely\nurl: https://www.musely.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Musely's Seller, Muse and Buyer Services are available only to, and may only be used by, individuals who\n    are 18 years and older who can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Prescription products\n  text: All sales of products that require prescriptions shall be made only in compliance with all laws and regulations\n    that apply in the State in which you reside or are purchasing\
  \ the Product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: individuals who are 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/musely/eligibility/musely-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Musely's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Telehealth
- Skincare
- Dermatology
- Prescription
- Health
- Longevity
---
