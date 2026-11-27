---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer is at least (18) years of age, if an individual
    type: individual
  - text: if a business, Customer is legally authorized to do business in its state and/or country of operation
    type: business
  minimum_age:
    text: Customer is at least (18) years of age, if an individual
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: Customer expressly agrees not to re-export and shall not directly or indirectly release or make available any Fuel to any Restricted Country
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
name: AEG Fuels
provenance_date: '2026-11-09'
provider_name: AEG Fuels
provider_slug: aegfuels
slug: aegfuels-eligibility
source_date: '2026-11-09'
source_filename: aegfuels-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/67a659f9b80c35040b4d08ae/6813f3821e59ec07be1c4e8f_AEG%20General%20Terms%20and%20Conditions%20-%20May%202025.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AEG Fuels\naid: aegfuels\nurl: https://cdn.prod.website-files.com/67a659f9b80c35040b4d08ae/6813f3821e59ec07be1c4e8f_AEG%20General%20Terms%20and%20Conditions%20-%20May%202025.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customer is at least (18) years of age, if an individual\n- type: business\n  text: if a business, Customer is legally authorized to do business in its state and/or country of operation\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Customer expressly agrees not to re-export and shall not\
  \ directly or indirectly release or make available\n    any Fuel to any Restricted Country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer is at least (18) years of age, if an individual\n"
source_yaml_url: https://artifacts.apis.io/aegfuels/eligibility/aegfuels-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AEG Fuels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Aviation
- Aviation Fuel
- Fuel
- Energy
- Logistics
- Supply Chain
- Flight Support
- Sustainable Aviation Fuel
- Marine Fuel
- Transportation
- Business Aviation
---
