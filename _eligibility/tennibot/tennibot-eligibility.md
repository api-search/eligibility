---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
  - summary: Illegal or harassing use
    text: use the Services for illegal, harassing, unethical, or disruptive purposes
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
name: Tennibot
provenance_date: '2026-11-10'
provider_name: Tennibot
provider_slug: tennibot
slug: tennibot-eligibility
source_date: '2026-11-10'
source_filename: tennibot-eligibility.yml
source_heading: Eligibility
source_page: https://www.tennibot.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tennibot\naid: tennibot\nurl: https://www.tennibot.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly,\
  \ the Services and/or other information or materials\n    provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction\n    requires any export license\n- summary: Illegal or harassing use\n  text: use the Services for illegal, harassing, unethical, or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/tennibot/eligibility/tennibot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tennibot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Computer Vision
- Sports Technology
- Tennis
- Pickleball
- Padel
- Consumer Hardware
- Mobile App
---
