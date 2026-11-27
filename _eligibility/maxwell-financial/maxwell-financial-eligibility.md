---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Loan officers of various mortgage lenders (“Lenders”) subscribe for the Services
    type: business
  - text: Homebuyers or other potential borrowers (collectively “Borrowers”) join the service by clicking on a link from an invitation from their Lender or Realtor
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Services, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Borrowers personal use only
    text: Borrowers agree that the Services are provided for their personal use and not for any commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users are required to register with Maxwell in order to access and use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Maxwell Financial
provenance_date: '2026-11-10'
provider_name: Maxwell Financial
provider_slug: maxwell-financial
slug: maxwell-financial-eligibility
source_date: '2026-11-10'
source_filename: maxwell-financial-eligibility.yml
source_heading: Eligibility
source_page: https://himaxwell.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maxwell Financial\naid: maxwell-financial\nurl: https://himaxwell.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Loan officers of various mortgage lenders (“Lenders”) subscribe for the Services\n- type: individual\n  text: Homebuyers or other potential borrowers (collectively “Borrowers”) join the service by clicking on a link\n    from an invitation from their Lender or Realtor\nrestricted_uses:\n- summary: Borrowers personal use only\n  text: Borrowers agree that the Services are provided for their personal use and not for\
  \ any commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users are required to register with Maxwell in order to access and use the Services.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Services, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/maxwell-financial/eligibility/maxwell-financial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Maxwell Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mortgage
- Lending
- Fintech
- Financial Services
- Loan Origination
---
