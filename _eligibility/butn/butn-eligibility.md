---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website and the content are provided for business purposes and to facilitate business transactions.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No residential property investment
    text: you have entered into this Agreement solely for business or investment purposes and that those investment purposes do not include the purchase, renovation or improvement of residential property
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 'We may in our absolute discretion: (i). approve or reject your Request'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Butn
provenance_date: '2026-11-09'
provider_name: Butn
provider_slug: butn
slug: butn-eligibility
source_date: '2026-11-09'
source_filename: butn-eligibility.yml
source_heading: Eligibility
source_page: https://www.butn.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Butn\naid: butn\nurl: https://www.butn.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This Website and the content are provided for business purposes and to facilitate business transactions.\nrestricted_uses:\n- summary: No residential property investment\n  text: you have entered into this Agreement solely for business or investment purposes and that those investment\n    purposes do not include the purchase, renovation or improvement of residential property\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: true\n  text: 'We may in our absolute discretion: (i). approve or reject your Request'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/butn/eligibility/butn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Butn's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Australia
- Embedded Finance
- Invoice Finance
- Accounts Receivable
- Accounts Payable
- B2B BNPL
- Business Lending
- Cash Flow
- Working Capital
---
