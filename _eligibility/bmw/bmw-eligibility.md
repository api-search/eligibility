---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if they are domiciled within the European Economic Area (EEA) / Switzerland
  entity_types:
  - text: Users are entitled to a licence if they belong to the category of "independent operators" as defined by the Block Exemption Regulation (EC) 461/2010
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional maintenance and repair only
    text: the user shall only use the content provided for professional performance of maintenance and repair of vehicles and motorcycles manufactured by the operator
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: On receipt of the licence confirmation and activation by the operator, the user can log in to the portal.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BMW
provenance_date: '2026-11-09'
provider_name: BMW
provider_slug: bmw
slug: bmw-eligibility
source_date: '2026-11-09'
source_filename: bmw-eligibility.yml
source_heading: Eligibility
source_page: https://aos.bmwgroup.com/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BMW\naid: bmw\nurl: https://aos.bmwgroup.com/conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if they are domiciled within the European Economic Area (EEA) / Switzerland\nentity_types:\n- type: business\n  text: Users are entitled to a licence if they belong to the category of \"independent operators\" as defined by\n    the Block Exemption Regulation (EC) 461/2010\nrestricted_uses:\n- summary: Professional maintenance and repair only\n  text: the user shall only use the content provided for professional performance of maintenance and repair of vehicles\n    and\
  \ motorcycles manufactured by the operator\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: On receipt of the licence confirmation and activation by the operator, the user can log in to the portal.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bmw/eligibility/bmw-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from BMW's own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Connected Vehicles
---
