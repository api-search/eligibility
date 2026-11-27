---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Alfa Laval Inc., Canada Standard Terms & Conditions of Sale; prices quoted in Canadian currency
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export/sanctions compliance
    text: Products and services under any Agreement may be subject to export and sanctions laws and regulations
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Each transaction is subject to approval of Customer's credit by Alfa Laval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alfa Laval
provenance_date: '2026-11-09'
provider_name: Alfa Laval
provider_slug: alfalaval
slug: alfalaval-eligibility
source_date: '2026-11-09'
source_filename: alfalaval-eligibility.yml
source_heading: Eligibility
source_page: https://www.alfalaval.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alfa Laval\naid: alfalaval\nurl: https://www.alfalaval.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Alfa Laval Inc., Canada Standard Terms & Conditions of Sale; prices quoted in Canadian currency\nentity_types: []\nrestricted_uses:\n- summary: Export/sanctions compliance\n  text: Products and services under any Agreement may be subject to export and sanctions laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Each transaction is subject to approval of Customer's credit by Alfa Laval.\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/alfalaval/eligibility/alfalaval-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Alfa Laval's own page on 2026-11-09.
synthetic: false
tags:
- Heat Transfer
- Separation
- Fluid Handling
- Energy
- Food
- Water
- Marine
---
