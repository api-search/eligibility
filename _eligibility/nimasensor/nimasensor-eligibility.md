---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - SG
    text: NIMA Partners currently supports shipments within the United States, Canada, and Singapore only.
  minimum_age:
    text: you are sixteen (16) years of age or older
    value: '16'
  restricted_uses:
  - summary: No resale or commercial use
    text: This restriction applies to individuals, businesses, organizations, institutions, and any other entity.
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
name: NimaSensor
provenance_date: '2026-11-10'
provider_name: NimaSensor
provider_slug: nimasensor
slug: nimasensor-eligibility
source_date: '2026-11-10'
source_filename: nimasensor-eligibility.yml
source_heading: Eligibility
source_page: https://nimanow.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NimaSensor\naid: nimasensor\nurl: https://nimanow.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - SG\n  excluded: []\n  text: NIMA Partners currently supports shipments within the United States, Canada, and Singapore only.\nentity_types: []\nrestricted_uses:\n- summary: No resale or commercial use\n  text: This restriction applies to individuals, businesses, organizations, institutions, and any other entity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are sixteen (16) years of age\
  \ or older\n"
source_yaml_url: https://artifacts.apis.io/nimasensor/eligibility/nimasensor-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NimaSensor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Consumer Hardware
- Food Safety
- Gluten
- Celiac
- E-Commerce
- IoT
---
