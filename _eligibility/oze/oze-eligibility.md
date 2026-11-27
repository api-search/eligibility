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
  - summary: Prohibited money-transfer categories
    text: 'You agree that you will not use the Service to request, send or receive money related to any of the following: Pharmaceuticals and other controlled substances; Illegal drugs; Drug paraphernalia; Firearms, ammunition or other weapons'
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
name: Oze
provenance_date: '2026-11-10'
provider_name: Oze
provider_slug: oze
slug: oze-eligibility
source_date: '2026-11-10'
source_filename: oze-eligibility.yml
source_heading: Eligibility
source_page: https://getoze.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oze\naid: oze\nurl: https://getoze.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS\nrestricted_uses:\n- summary: Prohibited money-transfer categories\n  text: 'You agree that you will not use the Service to request, send or receive money related to any of the following:\n    Pharmaceuticals and other controlled substances; Illegal\
  \ drugs; Drug paraphernalia; Firearms, ammunition or\n    other weapons'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/oze/eligibility/oze-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Small Business
- Bookkeeping
- Invoicing
- Lending
- Africa
---
