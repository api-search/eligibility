---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CH
    text: Our Website is targeted at and intended for visitors residing in the United States, the United Kingdom, and Switzerland.
  entity_types:
  - text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom, and Switzerland) or older to use our Website.
    type: individual
  minimum_age:
    text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom, and Switzerland) or older to use our Website.
    value: age of majority
  restricted_uses:
  - summary: No business or commercial use
    text: This Website is intended for personal, non-commercial use and may not be exploited in connection with any business or commercial purpose, without the prior express written permission of Roivant.
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
name: Roivant
provenance_date: '2026-11-10'
provider_name: Roivant
provider_slug: roivant
slug: roivant-eligibility
source_date: '2026-11-10'
source_filename: roivant-eligibility.yml
source_heading: Eligibility
source_page: https://www.roivant.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roivant\naid: roivant\nurl: https://www.roivant.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CH\n  excluded: []\n  text: Our Website is targeted at and intended for visitors residing in the United States, the United Kingdom,\n    and Switzerland.\nentity_types:\n- type: individual\n  text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom,\n    and Switzerland) or older to use our Website.\nrestricted_uses:\n- summary: No business or commercial use\n  text: This Website is intended for personal, non-commercial use\
  \ and may not be exploited in connection with any\n    business or commercial purpose, without the prior express written permission of Roivant.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom,\n    and Switzerland) or older to use our Website.\n"
source_yaml_url: https://artifacts.apis.io/roivant/eligibility/roivant-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Roivant's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Biopharmaceutical
- Pharmaceuticals
- Drug Development
- Life Sciences
- Immunology
---
