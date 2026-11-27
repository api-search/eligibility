---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You need to be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: No unlawful use or harassment
    text: Use the Service for any unlawful purpose or for the promotion of illegal activities
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
name: Tasso
provenance_date: '2026-11-10'
provider_name: Tasso
provider_slug: tasso
slug: tasso-eligibility
source_date: '2026-11-10'
source_filename: tasso-eligibility.yml
source_heading: Eligibility
source_page: https://www.tassoinc.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tasso\naid: tasso\nurl: https://www.tassoinc.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unlawful use or harassment\n  text: Use the Service for any unlawful purpose or for the promotion of illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You need to be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/tasso/eligibility/tasso-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Tasso's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blood Collection
- Microsampling
- Diagnostics
- Clinical Trials
- Decentralized Trials
- Medical Devices
- Healthcare
- Life Sciences
- Logistics
---
