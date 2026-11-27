---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Block Party makes no representations that the Service is appropriate or available for use in other locations. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: You may use the Service only if you can form a binding contract with Block Party
    type: individual
  - text: If you open a User Account on behalf of a company, organization, or other entity, then (i) “you” includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under eighteen (18) years of age is strictly prohibited and in violation of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use
    text: you are hereby granted a non-exclusive, limited, non-transferable, freely revocable license to use the Service for your personal, noncommercial use only
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
name: Blockpartyapp
provenance_date: '2026-11-09'
provider_name: Blockpartyapp
provider_slug: blockpartyapp
slug: blockpartyapp-eligibility
source_date: '2026-11-09'
source_filename: blockpartyapp-eligibility.yml
source_heading: Eligibility
source_page: https://www.blockpartyapp.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blockpartyapp\naid: blockpartyapp\nurl: https://www.blockpartyapp.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Block Party makes no representations that the Service is appropriate or available for use in other locations.\n    You may not use the Service if you are a resident of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding contract with Block Party\n- type: business\n  text: If you open a User Account on behalf of a company, organization, or other entity, then (i) “you” includes\n\
  \    you and that entity\nrestricted_uses:\n- summary: Personal noncommercial use\n  text: you are hereby granted a non-exclusive, limited, non-transferable, freely revocable license to use the Service\n    for your personal, noncommercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Service by anyone under eighteen (18) years of age is strictly prohibited and in\n    violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/blockpartyapp/eligibility/blockpartyapp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Blockpartyapp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Social Media
- Security
- Browser Extension
- Consumer
---
