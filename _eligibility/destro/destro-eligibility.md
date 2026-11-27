---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, and will not use the Services in, a jurisdiction subject to comprehensive sanctions, and that you are not a restricted or denied party.
  entity_types:
  - text: The Services are intended for businesses
    type: business
  - text: individuals who are at least 18 years old and able to form a legally binding contract
    type: individual
  minimum_age:
    text: individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctions and export controls
    text: You will not export or re-export the Services in violation of applicable law.
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
name: Destro
provenance_date: '2026-11-09'
provider_name: Destro
provider_slug: destro
slug: destro-eligibility
source_date: '2026-11-09'
source_filename: destro-eligibility.yml
source_heading: Eligibility
source_page: https://www.destroai.com/terms-and-conditions/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Destro\naid: destro\nurl: https://www.destroai.com/terms-and-conditions/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, and will not use the Services in, a jurisdiction subject to comprehensive\n    sanctions, and that you are not a restricted or denied party.\nentity_types:\n- type: business\n  text: The Services are intended for businesses\n- type: individual\n  text: individuals who are at least 18 years old and able to form a legally binding contract\nrestricted_uses:\n- summary: Sanctions and export controls\n \
  \ text: You will not export or re-export the Services in violation of applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/destro/eligibility/destro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Destro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Robotics
- Automation
- Warehouse
---
