---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The warranties and remedies herein apply only to the Growcer Product Offerings delivered to customers in the United States
  entity_types:
  - text: the individual accepting these Terms by executing a sales contract, purchase order or similar document
    type: individual
  - text: if the individual accepting these Terms is accepting on behalf of a legal entity, such individual represents that they have the authority to bind such entity and its affiliates to these Terms
    type: business
  - text: being licensed to U.S. Government end users (a) only as Commercial Items
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Customer certifies that it will not export or re-export any of the Growcer Product Offerings
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
name: Freight Farms
provenance_date: '2026-11-09'
provider_name: Freight Farms
provider_slug: freight-farms
slug: freight-farms-eligibility
source_date: '2026-11-09'
source_filename: freight-farms-eligibility.yml
source_heading: Eligibility
source_page: https://www.freightfarms.com/terms-conditions-of-sale-growcer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freight Farms\naid: freight-farms\nurl: https://www.freightfarms.com/terms-conditions-of-sale-growcer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The warranties and remedies herein apply only to the Growcer Product Offerings delivered to customers in\n    the United States\nentity_types:\n- type: individual\n  text: the individual accepting these Terms by executing a sales contract, purchase order or similar document\n- type: business\n  text: if the individual accepting these Terms is accepting on behalf of a legal entity, such individual represents\n    that they have\
  \ the authority to bind such entity and its affiliates to these Terms\n- type: government\n  text: being licensed to U.S. Government end users (a) only as Commercial Items\nrestricted_uses:\n- summary: Export control compliance\n  text: Customer certifies that it will not export or re-export any of the Growcer Product Offerings\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/freight-farms/eligibility/freight-farms-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Freight Farms's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Farming
- Agriculture
- AgTech
- Hydroponics
- Controlled Environment Agriculture
- Container Farming
- Farm Automation
- IoT
- Food Technology
---
