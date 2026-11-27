---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - SY
    - KP
    - IQ
    served: []
    text: You may not use the Services if you reside in any embargoed countries, e.g., Iran, Cuba, Syria, North Korea, or Iraq.
  entity_types:
  - text: You may create an Account if you are of legal age to agree to form a binding contract with Baobab
    type: individual
  - text: If you are an entity, the individual agreeing to this Agreement must have the legal authority to bind the entity.
    type: business
  minimum_age:
    text: If you are an individual, you must be 18 years of age or older if the age of legal capacity of forming binding contracts is older in the relevant jurisdiction.
    value: '18'
  restricted_uses:
  - summary: No commercial use of Services or Content
    text: solely for personal and non-commercial entertainment uses
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- SY
- KP
- IQ
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Baobab Studios
provenance_date: '2026-11-09'
provider_name: Baobab Studios
provider_slug: baobab-studios
slug: baobab-studios-eligibility
source_date: '2026-11-09'
source_filename: baobab-studios-eligibility.yml
source_heading: Eligibility
source_page: https://www.baobabstudios.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baobab Studios\naid: baobab-studios\nurl: https://www.baobabstudios.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - SY\n  - KP\n  - IQ\n  text: You may not use the Services if you reside in any embargoed countries, e.g., Iran, Cuba, Syria, North Korea,\n    or Iraq.\nentity_types:\n- type: individual\n  text: You may create an Account if you are of legal age to agree to form a binding contract with Baobab\n- type: business\n  text: If you are an entity, the individual agreeing to this Agreement must have the legal authority to\
  \ bind the\n    entity.\nrestricted_uses:\n- summary: No commercial use of Services or Content\n  text: solely for personal and non-commercial entertainment uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are an individual, you must be 18 years of age or older if the age of legal capacity of forming binding\n    contracts is older in the relevant jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/baobab-studios/eligibility/baobab-studios-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Baobab Studios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Animation
- Virtual Reality
- Augmented Reality
- Interactive Media
- Entertainment
---
