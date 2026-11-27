---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services in the United States, and the Services are not intended for use outside of the United States.
  entity_types:
  - text: you are an individual (whether a Consumer or business representative) who is at least the age of majority in your state of residence
    type: individual
  - text: If you are using the Services on behalf of a business entity, you represent that you have authority to bind that business entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer purchase restrictions
    text: 'If you are a Consumer, you will not use the Services to: Make payment(s) on existing loan(s) or other credit obligations other than Credit obtained through the Services; Accomplish a cash advance, wire or money transfer;'
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
name: Wisetack
provenance_date: '2026-11-10'
provider_name: Wisetack
provider_slug: wisetack
slug: wisetack-eligibility
source_date: '2026-11-10'
source_filename: wisetack-eligibility.yml
source_heading: Eligibility
source_page: https://wisetack.us/#/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wisetack\naid: wisetack\nurl: https://wisetack.us/#/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services in the United States, and the Services are not intended for use outside of the United\n    States.\nentity_types:\n- type: individual\n  text: you are an individual (whether a Consumer or business representative) who is at least the age of majority\n    in your state of residence\n- type: business\n  text: If you are using the Services on behalf of a business entity, you represent that you have authority to bind\n    that business entity to these\
  \ Terms\nrestricted_uses:\n- summary: Consumer purchase restrictions\n  text: 'If you are a Consumer, you will not use the Services to: Make payment(s) on existing loan(s) or other credit\n    obligations other than Credit obtained through the Services; Accomplish a cash advance, wire or money transfer;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wisetack/eligibility/wisetack-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Wisetack's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Consumer Financing
- Embedded Finance
- Payments
- Home Services
---
