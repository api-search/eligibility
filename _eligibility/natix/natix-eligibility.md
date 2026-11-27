---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services may not be available or appropriate for use in your jurisdiction.
  entity_types:
  - text: Registration and conclusion of the Agreement is only permitted for natural persons and legal entities with unlimited legal capacity and only in their own name and for their own account.
    type: individual
  - text: Registration and conclusion of the Agreement for legal entities is only permitted for persons who act as legal representatives or other authorized persons of the respective legal entity or on its behalf and at its interest.
    type: business
  minimum_age:
    text: Users must have reached 18 at the time of conclusion of the Agreement.
    value: '18'
  restricted_uses:
  - summary: No data mining or scraping
    text: Data Mining or Scraping. Activity that involves data mining, robots, scraping, or similar data gathering or extraction methods of content or information from our Services.
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
name: NATIX
provenance_date: '2026-11-10'
provider_name: NATIX
provider_slug: natix
slug: natix-eligibility
source_date: '2026-11-10'
source_filename: natix-eligibility.yml
source_heading: Eligibility
source_page: https://docs.natix.network/policies/staking-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NATIX\naid: natix\nurl: https://docs.natix.network/policies/staking-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services may not be available or appropriate for use in your jurisdiction.\nentity_types:\n- type: individual\n  text: Registration and conclusion of the Agreement is only permitted for natural persons and legal entities with\n    unlimited legal capacity and only in their own name and for their own account.\n- type: business\n  text: Registration and conclusion of the Agreement for legal entities is only permitted for persons who act as\n    legal representatives\
  \ or other authorized persons of the respective legal entity or on its behalf and at its\n    interest.\nrestricted_uses:\n- summary: No data mining or scraping\n  text: Data Mining or Scraping. Activity that involves data mining, robots, scraping, or similar data gathering\n    or extraction methods of content or information from our Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must have reached 18 at the time of conclusion of the Agreement.\n"
source_yaml_url: https://artifacts.apis.io/natix/eligibility/natix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from NATIX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DePIN
- Mapping
- Autonomous Driving
- Physical AI
- Geospatial
- Computer Vision
- Web3
- Data
---
