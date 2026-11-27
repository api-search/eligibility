---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer is not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: on behalf of the entity entering into this agreement, and to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Crypto mining
    text: use the Services for crypto mining
  - summary: Deepfakes / manipulated media
    text: create or disseminate any synthetic and/or manipulated media (e.g., deepfakes)
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
name: RapidFire AI
provenance_date: '2026-11-10'
provider_name: RapidFire AI
provider_slug: rapidfire
slug: rapidfire-eligibility
source_date: '2026-11-10'
source_filename: rapidfire-eligibility.yml
source_heading: Eligibility
source_page: https://www.rapidfire.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RapidFire AI\naid: rapidfire\nurl: https://www.rapidfire.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer is not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: business\n  text: on behalf of the entity entering into this agreement, and to bind that entity\nrestricted_uses:\n- summary: Crypto mining\n  text: use the Services for crypto mining\n- summary: Deepfakes / manipulated media\n  text: create or disseminate any synthetic and/or manipulated media (e.g., deepfakes)\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rapidfire/eligibility/rapidfire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from RapidFire AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Experimentation
- Scalability
---
