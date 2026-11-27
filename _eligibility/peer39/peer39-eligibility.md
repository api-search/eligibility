---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Customer” (or “you,” “yours,” or similar words) means the business organization named in the Sign-Up Form or that otherwise completes the registration process on our Site for access to the Service.
    type: business
  minimum_age:
    text: the Administrative User or Authorized User is over the age of eighteen (18) years
    value: '18'
  restricted_uses:
  - summary: Competitors barred
    text: Customer may not subscribe to, access, permit access by any third party, or use the Service at all if Customer is a competitor of Peer39 in the provision of contextual advertising data and enabling solutions
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
name: Peer39
provenance_date: '2026-11-10'
provider_name: Peer39
provider_slug: peer39
slug: peer39-eligibility
source_date: '2026-11-10'
source_filename: peer39-eligibility.yml
source_heading: Eligibility
source_page: https://www.peer39.com/service-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peer39\naid: peer39\nurl: https://www.peer39.com/service-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Customer” (or “you,” “yours,” or similar words) means the business organization named in the Sign-Up Form\n    or that otherwise completes the registration process on our Site for access to the Service.\nrestricted_uses:\n- summary: Competitors barred\n  text: Customer may not subscribe to, access, permit access by any third party, or use the Service at all if Customer\n    is a competitor of Peer39 in the provision of contextual\
  \ advertising data and enabling solutions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Administrative User or Authorized User is over the age of eighteen (18) years\n"
source_yaml_url: https://artifacts.apis.io/peer39/eligibility/peer39-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Peer39's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contextual Advertising
- AdTech
- Brand Safety
- Programmatic Advertising
- Contextual Targeting
- CTV
- MarTech
- Advertising
- Custom Categories
- DSP
---
