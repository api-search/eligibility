---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - ZA
    text: Access to the Website and Software from territories or countries where the content or purchase of the Services sold on the Website is illegal is prohibited.
  entity_types:
  - text: you represent and warrant that you are at least 18 years old and otherwise capable of entering into binding contracts.
    type: individual
  minimum_age:
    text: the Service and Software is not available to children (persons under the age of 18) or others who are not capable of entering into binding contracts.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You will only use the Service or Software for lawful purposes; you will not use the Service for sending or storing any unlawful material or for fraudulent purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will provide us with whatever proof of identity the Company may reasonably request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ShiftSouth
provenance_date: '2026-11-10'
provider_name: ShiftSouth
provider_slug: shiftsouth
slug: shiftsouth-eligibility
source_date: '2026-11-10'
source_filename: shiftsouth-eligibility.yml
source_heading: Eligibility
source_page: https://sweepsouth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShiftSouth\naid: shiftsouth\nurl: https://sweepsouth.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ZA\n  excluded: []\n  text: Access to the Website and Software from territories or countries where the content or purchase of the Services\n    sold on the Website is illegal is prohibited.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least 18 years old and otherwise capable of entering into binding\n    contracts.\nrestricted_uses:\n- summary: Lawful use only\n  text: You will only use the Service or Software for lawful purposes; you\
  \ will not use the Service for sending\n    or storing any unlawful material or for fraudulent purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will provide us with whatever proof of identity the Company may reasonably request.\nminimum_age:\n  value: '18'\n  text: the Service and Software is not available to children (persons under the age of 18) or others who are not\n    capable of entering into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/shiftsouth/eligibility/shiftsouth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ShiftSouth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- On-Demand
- Cleaning
- South Africa
- Consumer
- Gig Economy
---
