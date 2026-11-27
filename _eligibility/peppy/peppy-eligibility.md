---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - IE
    text: Our Practitioners are only able to offer prescription services to individuals who are based and reside in the United Kingdom or the Republic of Ireland
  entity_types:
  - text: The Services are for Your personal and non-commercial use.
    type: individual
  minimum_age:
    text: that You are 18 years of age or older and are able to enter into a binding contract
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: If You use the Peppy Applications or Services for any commercial, business or resale purpose We will have no liability to You
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order for Our Practitioners to write a prescription, they may require You to upload a copy of Your passport and proof of address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Peppy
provenance_date: '2026-11-10'
provider_name: Peppy
provider_slug: peppy
slug: peppy-eligibility
source_date: '2026-11-10'
source_filename: peppy-eligibility.yml
source_heading: Eligibility
source_page: https://peppy.health/end-user-licence-agreement-2026
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peppy\naid: peppy\nurl: https://peppy.health/end-user-licence-agreement-2026\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - IE\n  excluded: []\n  text: Our Practitioners are only able to offer prescription services to individuals who are based and reside in\n    the United Kingdom or the Republic of Ireland\nentity_types:\n- type: individual\n  text: The Services are for Your personal and non-commercial use.\nrestricted_uses:\n- summary: No commercial use\n  text: If You use the Peppy Applications or Services for any commercial, business or resale purpose We will have\n    no liability to You\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order for Our Practitioners to write a prescription, they may require You to upload a copy of Your passport\n    and proof of address.\nminimum_age:\n  value: '18'\n  text: that You are 18 years of age or older and are able to enter into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/peppy/eligibility/peppy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Peppy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Employee Benefits
- Digital Health
- Women's Health
- Menopause
- Fertility
- Neurodiversity
- Wellbeing
---
