---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    text: Our Website and Services are intended for persons residing in Indonesia.
  entity_types:
  - text: You must be over 21 years old and not under guardianship.
    type: individual
  - text: '"Borrower" means an individual or legal entity who intends to seek financing through our Services.'
    type: business
  minimum_age:
    text: You must be over 21 years old and not under guardianship.
    value: '21'
  restricted_uses:
  - summary: No fraud against lenders or borrowers
    text: Do not commit fraud that causes Lender or Borrower in the Loan Agreement to suffer losses.
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
name: Amartha
provenance_date: '2026-11-09'
provider_name: Amartha
provider_slug: amartha
slug: amartha-eligibility
source_date: '2026-11-09'
source_filename: amartha-eligibility.yml
source_heading: Eligibility
source_page: https://amartha.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amartha\naid: amartha\nurl: https://amartha.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ID\n  excluded: []\n  text: Our Website and Services are intended for persons residing in Indonesia.\nentity_types:\n- type: individual\n  text: You must be over 21 years old and not under guardianship.\n- type: business\n  text: '\"Borrower\" means an individual or legal entity who intends to seek financing through our Services.'\nrestricted_uses:\n- summary: No fraud against lenders or borrowers\n  text: Do not commit fraud that causes Lender or Borrower in the Loan Agreement to suffer\
  \ losses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You must be over 21 years old and not under guardianship.\n"
source_yaml_url: https://artifacts.apis.io/amartha/eligibility/amartha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Amartha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Microfinance
- Peer-to-Peer Lending
- Financial Inclusion
- Payments
- Indonesia
---
