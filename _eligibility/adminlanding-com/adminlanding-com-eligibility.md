---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using our service, you agree to these terms.
    type: individual
  minimum_age:
    text: 'Age requirement: you must be 16 or older (or the age of digital consent in your country) to hold an account. We do not verify age at sign-up.'
    value: '16'
  restricted_uses:
  - summary: No legal advice or legal representation
    text: This does not constitute legal advice (consultation juridique), personalized legal opinion, or legal representation.
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
name: AdminLanding
provenance_date: '2026-11-09'
provider_name: AdminLanding
provider_slug: adminlanding-com
slug: adminlanding-com-eligibility
source_date: '2026-11-09'
source_filename: adminlanding-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.adminlanding.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdminLanding\naid: adminlanding-com\nurl: https://www.adminlanding.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using our service, you agree to these terms.\nrestricted_uses:\n- summary: No legal advice or legal representation\n  text: This does not constitute legal advice (consultation juridique), personalized legal opinion, or legal representation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: 'Age requirement: you must be 16 or older (or the\
  \ age of digital consent in your country) to hold an account.\n    We do not verify age at sign-up.'\n"
source_yaml_url: https://artifacts.apis.io/adminlanding-com/eligibility/adminlanding-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AdminLanding's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- French Administration
- Real Estate
- Tax
---
