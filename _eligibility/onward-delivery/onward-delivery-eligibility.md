---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Onward Platform is directed to those individuals and entities located in the United States
  entity_types:
  - text: you must be eighteen (18) years or older and have the requisite power and authority to enter into this Terms of Service
    type: individual
  - text: If you are accepting this Terms of Service on behalf of a company, entity, or organization, you represent and warrant that you have the right, authority, and capacity to enter into this Terms of Service
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited shipped items
    text: you will not use the Onward Platform and/or Services to transport or move weapons, prescription drugs, illegal drugs, alcohol, tobacco, hazardous materials, food, animals, people, or other items prohibited by law
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
name: Onward Delivery
provenance_date: '2026-11-10'
provider_name: Onward Delivery
provider_slug: onward-delivery
slug: onward-delivery-eligibility
source_date: '2026-11-10'
source_filename: onward-delivery-eligibility.yml
source_heading: Eligibility
source_page: https://www.onwarddelivery.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onward Delivery\naid: onward-delivery\nurl: https://www.onwarddelivery.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Onward Platform is directed to those individuals and entities located in the United States\nentity_types:\n- type: individual\n  text: you must be eighteen (18) years or older and have the requisite power and authority to enter into this Terms\n    of Service\n- type: business\n  text: If you are accepting this Terms of Service on behalf of a company, entity, or organization, you represent\n    and warrant that\
  \ you have the right, authority, and capacity to enter into this Terms of Service\nrestricted_uses:\n- summary: Prohibited shipped items\n  text: you will not use the Onward Platform and/or Services to transport or move weapons, prescription drugs, illegal\n    drugs, alcohol, tobacco, hazardous materials, food, animals, people, or other items prohibited by law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/onward-delivery/eligibility/onward-delivery-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Onward Delivery's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Final Mile
- Last Mile Delivery
- Freight
- Shipping
- Transportation
- Supply Chain
- Carrier
---
