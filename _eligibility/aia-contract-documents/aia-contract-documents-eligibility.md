---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are authorized to enter into this Agreement on behalf of yourself or the business using the Service
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Copying text into non-ACD documents
    text: Copy the text of any AIA Contract Document®, in whole or in part, into a non-ACD document.
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
name: AIA Contract Documents
provenance_date: '2026-11-09'
provider_name: AIA Contract Documents
provider_slug: aia-contract-documents
slug: aia-contract-documents-eligibility
source_date: '2026-11-09'
source_filename: aia-contract-documents-eligibility.yml
source_heading: Eligibility
source_page: https://aiacontracts.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIA Contract Documents\naid: aia-contract-documents\nurl: https://aiacontracts.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you are authorized to enter into this Agreement on behalf of yourself or the business using the Service\nrestricted_uses:\n- summary: Copying text into non-ACD documents\n  text: Copy the text of any AIA Contract Document®, in whole or in part, into a non-ACD document.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are\
  \ at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/aia-contract-documents/eligibility/aia-contract-documents-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AIA Contract Documents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Contracts
- Architecture
- Software
---
