---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: 'Dealers: Create listings only for vehicles which are currently available for sale, within the United Arab Emirates.'
  entity_types:
  - text: Users must be over 18 years old.
    type: individual
  minimum_age:
    text: By accessing our platform, you confirm that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: OFAC-sanctioned entities
    text: CarSwitch does not engage with OFAC-sanctioned entities. Users must ensure compliance with international sanctions and trade restrictions.
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
name: CarSwitch
provenance_date: '2026-11-09'
provider_name: CarSwitch
provider_slug: carswitch
slug: carswitch-eligibility
source_date: '2026-11-09'
source_filename: carswitch-eligibility.yml
source_heading: Eligibility
source_page: https://carswitch.com/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarSwitch\naid: carswitch\nurl: https://carswitch.com/termsandconditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: 'Dealers: Create listings only for vehicles which are currently available for sale, within the United Arab\n    Emirates.'\nentity_types:\n- type: individual\n  text: Users must be over 18 years old.\nrestricted_uses:\n- summary: OFAC-sanctioned entities\n  text: CarSwitch does not engage with OFAC-sanctioned entities. Users must ensure compliance with international\n    sanctions and trade restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing our platform, you confirm that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/carswitch/eligibility/carswitch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CarSwitch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Used Cars
- Marketplace
- Automotive Marketplace
- E-Commerce
- Car Financing
- Vehicle Inspection
- United Arab Emirates
- Saudi Arabia
---
