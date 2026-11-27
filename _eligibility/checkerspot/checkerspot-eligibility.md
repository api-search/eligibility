---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Products and Service are intended for visitors located within United States. We make no representation that the Products and/or Service are appropriate or available for purchase and/or use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Products not for human consumption
    text: YOU WARRANT THAT ANY ITEM PRODUCED USING THE PRODUCT OR ITEM RESULTING FROM SERVICES PROVIDED BY CHECKERSPOT AS AN INPUT IS NOT INTENDED FOR HUMAN CONSUMPTION.
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
name: Checkerspot
provenance_date: '2026-11-09'
provider_name: Checkerspot
provider_slug: checkerspot
slug: checkerspot-eligibility
source_date: '2026-11-09'
source_filename: checkerspot-eligibility.yml
source_heading: Eligibility
source_page: https://www.checkerspot.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Checkerspot\naid: checkerspot\nurl: https://www.checkerspot.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Products and Service are intended for visitors located within United States. We make no representation that\n    the Products and/or Service are appropriate or available for purchase and/or use outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Products not for human consumption\n  text: YOU WARRANT THAT ANY ITEM PRODUCED USING THE PRODUCT OR ITEM RESULTING FROM SERVICES PROVIDED BY CHECKERSPOT\n    AS AN INPUT IS NOT INTENDED\
  \ FOR HUMAN CONSUMPTION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/checkerspot/eligibility/checkerspot-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Checkerspot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Precision Fermentation
- Synthetic Biology
- Microalgae
- Lipids
- Fats and Oils
- Ingredients
- Infant Nutrition
- Food Technology
- Cosmetics
- Personal Care
- Materials
- Sustainability
- United States
---
