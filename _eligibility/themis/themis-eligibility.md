---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individual users who use the Service as part of a paid Themis subscription plan are called “ Subscribers .”
    type: individual
  - text: the organization, such as your employer or another entity or person, that entered into a separate agreement that governs the delivery, access, and use of the Service (the “ Customer ”
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Misuse of the Service
    text: 'You may not utilize the Service and Site to carry out, promote or support: (a) any unlawful or fraudulent activities'
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
name: Themis
provenance_date: '2026-11-10'
provider_name: Themis
provider_slug: themis
slug: themis-eligibility
source_date: '2026-11-10'
source_filename: themis-eligibility.yml
source_heading: Eligibility
source_page: https://themis.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Themis\naid: themis\nurl: https://themis.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individual users who use the Service as part of a paid Themis subscription plan are called “ Subscribers\n    .”\n- type: business\n  text: the organization, such as your employer or another entity or person, that entered into a separate agreement\n    that governs the delivery, access, and use of the Service (the “ Customer ”\nrestricted_uses:\n- summary: Misuse of the Service\n  text: 'You may not utilize the Service and\
  \ Site to carry out, promote or support: (a) any unlawful or fraudulent\n    activities'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/themis/eligibility/themis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Themis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Governance Risk Compliance
- Risk Management
- Vendor Management
- Audit
- Fintech
- Banking
- RegTech
---
