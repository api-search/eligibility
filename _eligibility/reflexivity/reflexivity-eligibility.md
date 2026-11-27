---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Authorized users of Services are natural persons (not corporations or any entity of any type whatsoever)
    type: individual
  - text: If you are an entity or organization interested in a Reflexivity license for multiple users, please contact partnerships@reflexivity.com for pricing and license information.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No bank or lending employees
    text: you are not an employee of any bank or similar lending entity
  - summary: No wealth or asset management employees
    text: you are not an employee of a wealth management or asset management entity except a solo practice
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
name: Reflexivity
provenance_date: '2026-11-10'
provider_name: Reflexivity
provider_slug: reflexivity
slug: reflexivity-eligibility
source_date: '2026-11-10'
source_filename: reflexivity-eligibility.yml
source_heading: Eligibility
source_page: https://reflexivity.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reflexivity\naid: reflexivity\nurl: https://reflexivity.com/en/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Authorized users of Services are natural persons (not corporations or any entity of any type whatsoever)\n- type: business\n  text: If you are an entity or organization interested in a Reflexivity license for multiple users, please contact\n    partnerships@reflexivity.com for pricing and license information.\nrestricted_uses:\n- summary: No bank or lending employees\n  text: you are not an employee of any\
  \ bank or similar lending entity\n- summary: No wealth or asset management employees\n  text: you are not an employee of a wealth management or asset management entity except a solo practice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reflexivity/eligibility/reflexivity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Reflexivity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Investment Analysis
- Market Data
- Artificial Intelligence
- Machine Learning
- Fintech
- Research
- Knowledge Graph
- Agents
---
