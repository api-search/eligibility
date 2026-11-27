---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU REPRESENT THAT YOU ARE OVER THE AGE OF 18
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE OVER THE AGE OF 18
    value: '18'
  restricted_uses:
  - summary: Direct competitors of Headnote may not use the Service
    text: IF YOU ARE A DIRECT COMPETITOR OF HEADNOTE (OR REPRESENT THE INTERESTS, DIRECTLY OR INDIRECTLY, OF A DIRECT COMPETITOR) YOU MAY NOT USE THIS SERVICE
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: you are giving your permission for Headnote to perform research on your identify and/or business using various identification and validation tools including consent for a consumer credit report of all business owners listed on the application of the Customer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Headnote
provenance_date: '2026-11-09'
provider_name: Headnote
provider_slug: headnote
slug: headnote-eligibility
source_date: '2026-11-09'
source_filename: headnote-eligibility.yml
source_heading: Eligibility
source_page: https://headnote.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Headnote\naid: headnote\nurl: https://headnote.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU REPRESENT THAT YOU ARE OVER THE AGE OF 18\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY\nrestricted_uses:\n- summary: Direct competitors of Headnote may not use the Service\n  text: IF YOU ARE A DIRECT COMPETITOR OF HEADNOTE (OR REPRESENT THE INTERESTS, DIRECTLY OR INDIRECTLY, OF A DIRECT\n    COMPETITOR) YOU MAY NOT USE THIS SERVICE\nverification:\n  kyc: true\n\
  \  kyb: true\n  approval_required: null\n  text: you are giving your permission for Headnote to perform research on your identify and/or business using various\n    identification and validation tools including consent for a consumer credit report of all business owners listed\n    on the application of the Customer\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE OVER THE AGE OF 18\n"
source_yaml_url: https://artifacts.apis.io/headnote/eligibility/headnote-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Headnote's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Payments
- Accounts Receivable
- Law Firms
- eCheck
- ACH
- Credit Card Payments
- Trust Accounting
- IOLTA
- Compliance
---
