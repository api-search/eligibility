---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited shipped products
    text: you are prohibited to ship through Spaceship
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
name: Spaceship
provenance_date: '2026-11-10'
provider_name: Spaceship
provider_slug: spaceshipapp-com
slug: spaceshipapp-com-eligibility
source_date: '2026-11-10'
source_filename: spaceshipapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.spaceshipapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spaceship\naid: spaceshipapp-com\nurl: https://www.spaceshipapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity,\n    you represent that you have the authority to bind such entity and its affiliates\nrestricted_uses:\n- summary: Prohibited shipped products\n  text: you are prohibited to ship through Spaceship\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/spaceshipapp-com/eligibility/spaceshipapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spaceship's own page on 2026-11-10.
synthetic: false
tags:
- Space
- Travel
- Platform
- Aerospace
---
