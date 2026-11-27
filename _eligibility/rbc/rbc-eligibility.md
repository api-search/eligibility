---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products, services and Information are not available in all jurisdictions outside of Canada and/or the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: You may not use, export or re-export the Information or any copy or adaptation thereof in violation of any applicable laws or regulations, including export laws and regulations of Canada or the United States in force from time to time.
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
name: Royal Bank of Canada
provenance_date: '2026-11-10'
provider_name: Royal Bank of Canada
provider_slug: rbc
slug: rbc-eligibility
source_date: '2026-11-10'
source_filename: rbc-eligibility.yml
source_heading: Eligibility
source_page: https://www.rbc.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Royal Bank of Canada\naid: rbc\nurl: https://www.rbc.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products, services and Information are not available in all jurisdictions outside of Canada and/or the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Export compliance\n  text: You may not use, export or re-export the Information or any copy or adaptation thereof in violation of any\n    applicable laws or regulations, including export laws and regulations of Canada or the United States in force\n    from time to time.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rbc/eligibility/rbc-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Royal Bank of Canada's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Big Six
- Payments
- Interac
- Open Banking
---
