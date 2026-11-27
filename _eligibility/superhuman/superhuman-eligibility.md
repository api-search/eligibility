---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree that you are not barred from using the Services under the laws of the United States, your place of residence, or any other applicable jurisdiction.
  entity_types:
  - text: If you have opened an Account as an individual (i.e., not on behalf of an Entity)
    type: individual
  - text: If you are accepting these Terms on behalf of a company, organization, or other legal entity (an “ Entity ”)
    type: business
  minimum_age:
    text: you must be at least 13 years old under most United States law, or 16 years old under European Union law.
    value: '13'
  restricted_uses:
  - summary: Internal business use only for entities
    text: If you are an Entity, you must only access and use our Services for internal business purposes.
  - summary: Sanctioned parties and export controls
    text: You represent and warrant that you are not listed on any United States government list of prohibited or restricted parties
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
name: Superhuman
provenance_date: '2026-11-10'
provider_name: Superhuman
provider_slug: superhuman
slug: superhuman-eligibility
source_date: '2026-11-10'
source_filename: superhuman-eligibility.yml
source_heading: Eligibility
source_page: https://superhuman.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Superhuman\naid: superhuman\nurl: https://superhuman.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree that you are not barred from using the Services under the laws of the United States, your place\n    of residence, or any other applicable jurisdiction.\nentity_types:\n- type: individual\n  text: If you have opened an Account as an individual (i.e., not on behalf of an Entity)\n- type: business\n  text: If you are accepting these Terms on behalf of a company, organization, or other legal entity (an “ Entity\n    ”)\nrestricted_uses:\n- summary: Internal\
  \ business use only for entities\n  text: If you are an Entity, you must only access and use our Services for internal business purposes.\n- summary: Sanctioned parties and export controls\n  text: You represent and warrant that you are not listed on any United States government list of prohibited or\n    restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be at least 13 years old under most United States law, or 16 years old under European Union law.\n"
source_yaml_url: https://artifacts.apis.io/superhuman/eligibility/superhuman-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Superhuman's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Productivity
- Artificial Intelligence
- Email Client
- Documents
- MCP
- Agents
- Communications
---
