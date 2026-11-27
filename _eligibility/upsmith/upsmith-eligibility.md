---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Site for use only by persons located in the United States.
  entity_types:
  - text: This Site is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  minimum_age:
    text: This Site is offered and available to users who are 18 years of age or older
    value: '18'
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
name: UpSmith
provenance_date: '2026-11-10'
provider_name: UpSmith
provider_slug: upsmith
slug: upsmith-eligibility
source_date: '2026-11-10'
source_filename: upsmith-eligibility.yml
source_heading: Eligibility
source_page: https://www.upsmith.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UpSmith\naid: upsmith\nurl: https://www.upsmith.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Site for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Site is offered and available to users who are 18 years of age or older and reside in the United States\n    or any of its territories or possessions.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is offered and available to users who are 18 years\
  \ of age or older\n"
source_yaml_url: https://artifacts.apis.io/upsmith/eligibility/upsmith-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from UpSmith's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Services
- Skilled Trades
- AI Agents
- SMS
- HVAC
- Plumbing
- Field Service Management
---
