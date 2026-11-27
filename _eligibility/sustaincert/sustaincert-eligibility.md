---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you will be using the Services on behalf of an organization or a client, you agree to this TOC on behalf of that organization and/or that client
    type: business
  minimum_age:
    text: Our Services are not directed to children younger than 18 years old.
    value: '18'
  restricted_uses:
  - summary: No use in relation to crimes
    text: use the Services in relation to any crimes, including theft and fraud
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
name: SustainCERT
provenance_date: '2026-11-10'
provider_name: SustainCERT
provider_slug: sustaincert
slug: sustaincert-eligibility
source_date: '2026-11-10'
source_filename: sustaincert-eligibility.yml
source_heading: Eligibility
source_page: https://sustain-cert.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SustainCERT\naid: sustaincert\nurl: https://sustain-cert.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you will be using the Services on behalf of an organization or a client, you agree to this TOC on behalf\n    of that organization and/or that client\nrestricted_uses:\n- summary: No use in relation to crimes\n  text: use the Services in relation to any crimes, including theft and fraud\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ Our Services are not directed to children younger than 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sustaincert/eligibility/sustaincert-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SustainCERT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Climate
- Carbon Markets
- Verification
- Sustainability
- Carbon Credits
- MRV
---
