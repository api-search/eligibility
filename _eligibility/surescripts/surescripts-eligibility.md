---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You warrant and represent that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: No commercial or unsolicited messaging
    text: Engage in commercial, competitive, or viral messaging, or sending of unsolicited advertisements, or similar communications
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
name: Surescripts
provenance_date: '2026-11-10'
provider_name: Surescripts
provider_slug: surescripts
slug: surescripts-eligibility
source_date: '2026-11-10'
source_filename: surescripts-eligibility.yml
source_heading: Eligibility
source_page: https://surescripts.com/website-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Surescripts\naid: surescripts\nurl: https://surescripts.com/website-user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial or unsolicited messaging\n  text: Engage in commercial, competitive, or viral messaging, or sending of unsolicited advertisements, or similar\n    communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You warrant and represent that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/surescripts/eligibility/surescripts-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Surescripts's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- e-Prescribing
- Health Information Network
- NCPDP SCRIPT
- Medication History
- Prior Authorization
- Interoperability
- FHIR
- Formulary
- Eligibility
- Real-Time Prescription Benefit
- Mutual TLS
- Gated
---
