---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer warrants that it and its Authorized Users are not (a) not located in or under the control of the government of a country subject to U.S. sanctions
  entity_types:
  - text: you represent that you are at least eighteen (18) years of age and are eligible to register and use the Platform for commercial purposes.
    type: individual
  - text: you are duly organized, validly existing, and in good standing as a corporation or other entity under the laws of the jurisdiction of your incorporation or other organization
    type: business
  minimum_age:
    text: you represent that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Vehicle shipments
    text: The use of the Platform for any shipments that contain Vehicles (as defined below) is strictly prohibited.
  - summary: Sanctioned parties
    text: Customer represents and warrants that the Platform will not be used, directly or indirectly, to facilitate payments to OFAC sanctioned countries or to SDNs in contravention of Sanctions Laws.
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: conduct screening and background checks of the Customer, including a criminal background check of any director, manager, officer, principal, partner, or owner of such Customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PayCargo
provenance_date: '2026-11-10'
provider_name: PayCargo
provider_slug: paycargo-llc
slug: paycargo-llc-eligibility
source_date: '2026-11-10'
source_filename: paycargo-llc-eligibility.yml
source_heading: Eligibility
source_page: https://paycargo.com/platform-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayCargo\naid: paycargo-llc\nurl: https://paycargo.com/platform-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer warrants that it and its Authorized Users are not (a) not located in or under the control of the\n    government of a country subject to U.S. sanctions\nentity_types:\n- type: individual\n  text: you represent that you are at least eighteen (18) years of age and are eligible to register and use the\n    Platform for commercial purposes.\n- type: business\n  text: you are duly organized, validly existing, and in good standing as\
  \ a corporation or other entity under the\n    laws of the jurisdiction of your incorporation or other organization\nrestricted_uses:\n- summary: Vehicle shipments\n  text: The use of the Platform for any shipments that contain Vehicles (as defined below) is strictly prohibited.\n- summary: Sanctioned parties\n  text: Customer represents and warrants that the Platform will not be used, directly or indirectly, to facilitate\n    payments to OFAC sanctioned countries or to SDNs in contravention of Sanctions Laws.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: conduct screening and background checks of the Customer, including a criminal background check of any director,\n    manager, officer, principal, partner, or owner of such Customer.\nminimum_age:\n  value: '18'\n  text: you represent that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/paycargo-llc/eligibility/paycargo-llc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from PayCargo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Freight
- Logistics
- Supply Chain
- Fintech
- Accounts Payable
- Shipping
---
