---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: 'You represent and warrant that: You are not subject to economic sanctions or located in a sanctioned jurisdiction (e.g., Crimea, Cuba, Iran, North Korea, Syria)'
  entity_types:
  - text: To use the Platform, you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.
    type: individual
  minimum_age:
    text: you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Adult content
    text: You may not use the Platform to monetize or promote content or services that contain nudity or explicit sexual acts
  - summary: Copyright-infringing content
    text: You may not use the Platform to monetize or distribute content that infringes on copyright or other proprietary rights
  - summary: Violent extremism
    text: You may not use the Platform to monetize or promote content that engages in, encourages, promotes, or celebrates unlawful violence toward any group
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shibuya
provenance_date: '2026-11-10'
provider_name: Shibuya
provider_slug: shibuya
slug: shibuya-eligibility
source_date: '2026-11-10'
source_filename: shibuya-eligibility.yml
source_heading: Eligibility
source_page: https://www.shibuya.film/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shibuya\naid: shibuya\nurl: https://www.shibuya.film/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: 'You represent and warrant that: You are not subject to economic sanctions or located in a sanctioned jurisdiction\n    (e.g., Crimea, Cuba, Iran, North Korea, Syria)'\nentity_types:\n- type: individual\n  text: To use the Platform, you must be at least 18 years old or the age of majority in your jurisdiction, whichever\n    is higher.\nrestricted_uses:\n- summary: Adult content\n  text: You may not use the Platform to monetize or promote\
  \ content or services that contain nudity or explicit\n    sexual acts\n- summary: Copyright-infringing content\n  text: You may not use the Platform to monetize or distribute content that infringes on copyright or other proprietary\n    rights\n- summary: Violent extremism\n  text: You may not use the Platform to monetize or promote content that engages in, encourages, promotes, or celebrates\n    unlawful violence toward any group\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/shibuya/eligibility/shibuya-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Shibuya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Film
- Short Films
- Media
- Entertainment
- Streaming
- Creators
- Web3
---
