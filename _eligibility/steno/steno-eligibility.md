---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree that You are at least eighteen (18) years old and fully able and competent to understand, agree to, and abide by the terms
    type: individual
  - text: IF YOU ACCEPT THESE TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT THAT YOU ARE A DULY AUTHORIZED REPRESENTATIVE
    type: business
  minimum_age:
    text: You agree that You are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Export control compliance
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Steno
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
name: Steno
provenance_date: '2026-11-10'
provider_name: Steno
provider_slug: steno
slug: steno-eligibility
source_date: '2026-11-10'
source_filename: steno-eligibility.yml
source_heading: Eligibility
source_page: https://steno.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Steno\naid: steno\nurl: https://steno.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree that You are at least eighteen (18) years old and fully able and competent to understand, agree\n    to, and abide by the terms\n- type: business\n  text: IF YOU ACCEPT THESE TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT THAT YOU ARE A DULY AUTHORIZED REPRESENTATIVE\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S.\
  \ technical data acquired\n    from Steno\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You agree that You are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/steno/eligibility/steno-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Steno's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Court Reporting
- Depositions
- Litigation Support
- Transcription
- Video
- Artificial Intelligence
- Salesforce
---
