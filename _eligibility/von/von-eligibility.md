---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this TOS
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: U.S. export restrictions
    text: You may not remove or export from the United States or allow the export or re-export of the Services or anything related thereto
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
name: Von
provenance_date: '2026-11-10'
provider_name: Von
provider_slug: von
slug: von-eligibility
source_date: '2026-11-10'
source_filename: von-eligibility.yml
source_heading: Eligibility
source_page: https://vonlabs.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Von\naid: von\nurl: https://vonlabs.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS\nrestricted_uses:\n- summary: U.S. export restrictions\n  text: You may not remove or export from the United States or allow the export or re-export of the Services or\n    anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/von/eligibility/von-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Von's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Revenue Operations
- Sales
- CRM
- Analytics
- Software-as-a-Service
---
