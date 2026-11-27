---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ALDI controls and operates the Services from offices located in the United States and makes no representations or warranties that the information, products or services contained on the Services are appropriate for use or access in other locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized use of contact information
    text: You may not use contact information provided on the Services for unauthorized purposes, including marketing.
  - summary: Use in violation of law
    text: use the Services in a manner that is inconsistent with any and all applicable laws, rules or regulations
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
name: Aldiusa
provenance_date: '2026-11-09'
provider_name: Aldiusa
provider_slug: aldiusa
slug: aldiusa-eligibility
source_date: '2026-11-09'
source_filename: aldiusa-eligibility.yml
source_heading: Eligibility
source_page: https://www.aldi.us/store/aldi/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aldiusa\naid: aldiusa\nurl: https://www.aldi.us/store/aldi/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: ALDI controls and operates the Services from offices located in the United States and makes no representations\n    or warranties that the information, products or services contained on the Services are appropriate for use or\n    access in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized use of contact information\n  text: You may not use contact information provided on the Services for unauthorized purposes,\
  \ including marketing.\n- summary: Use in violation of law\n  text: use the Services in a manner that is inconsistent with any and all applicable laws, rules or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aldiusa/eligibility/aldiusa-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Aldiusa's own page on 2026-11-09.
synthetic: false
tags:
- Grocery
- Retail
- E-Commerce
- Low‑price
- Sustainability
---
