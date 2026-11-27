---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Services.
    value: '16'
  restricted_uses:
  - summary: No protected health information (HIPAA)
    text: You agree that you will not transmit, submit, upload or store on or through the Services any protected health information
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
name: VoidZero
provenance_date: '2026-11-10'
provider_name: VoidZero
provider_slug: voidzero
slug: voidzero-eligibility
source_date: '2026-11-10'
source_filename: voidzero-eligibility.yml
source_heading: Eligibility
source_page: https://voidzero.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VoidZero\naid: voidzero\nurl: https://voidzero.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity to this Agreement\nrestricted_uses:\n- summary: No protected health information (HIPAA)\n  text: You agree that you will not transmit, submit, upload or store on or through the Services any protected health\n    information\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/voidzero/eligibility/voidzero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from VoidZero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- JavaScript
- Build Tools
- Toolchain
- Open Source
- Testing
- Bundler
---
