---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Services is limited to authorised Customers that are of legal age and who have the legal capacity to enter into and form contracts under any applicable law.
    type: individual
  minimum_age:
    text: 'If you are below 18 years old: you must obtain consent from your parent(s) or legal guardian(s)'
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited materials
    text: use the Platform or Services for illegal purposes
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
name: PawnHero
provenance_date: '2026-11-10'
provider_name: PawnHero
provider_slug: pawnhero
slug: pawnhero-eligibility
source_date: '2026-11-10'
source_filename: pawnhero-eligibility.yml
source_heading: Eligibility
source_page: https://pawnhero.ph/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PawnHero\naid: pawnhero\nurl: https://pawnhero.ph/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of the Services is limited to authorised Customers that are of legal age and who have the legal capacity\n    to enter into and form contracts under any applicable law.\nrestricted_uses:\n- summary: Illegal or prohibited materials\n  text: use the Platform or Services for illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'If you are\
  \ below 18 years old: you must obtain consent from your parent(s) or legal guardian(s)'\n"
source_yaml_url: https://artifacts.apis.io/pawnhero/eligibility/pawnhero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PawnHero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pawnshop
- Lending
- Fintech
- Consumer Finance
- Collateral Loans
- Philippines
---
