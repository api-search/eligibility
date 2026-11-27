---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Using the Service may be prohibited or restricted in certain countries.
  entity_types:
  - text: You must be at least 18, or older if your jurisdiction requires.
    type: individual
  minimum_age:
    text: You must be at least 18 to use the Services.
    value: '18'
  restricted_uses:
  - summary: Felony conviction or sex offender registration
    text: You may not use the Services if you have been convicted of a felony, are required to register as a sex offender with any government entity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not routinely verify the identity of our Users. But we may verify the User identity as part of our fraud detection and prevention process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coffee Meets Bagel
provenance_date: '2026-11-09'
provider_name: Coffee Meets Bagel
provider_slug: coffee-meets-bagel
slug: coffee-meets-bagel-eligibility
source_date: '2026-11-09'
source_filename: coffee-meets-bagel-eligibility.yml
source_heading: Eligibility
source_page: https://www.coffeemeetsbagel.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coffee Meets Bagel\naid: coffee-meets-bagel\nurl: https://www.coffeemeetsbagel.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Using the Service may be prohibited or restricted in certain countries.\nentity_types:\n- type: individual\n  text: You must be at least 18, or older if your jurisdiction requires.\nrestricted_uses:\n- summary: Felony conviction or sex offender registration\n  text: You may not use the Services if you have been convicted of a felony, are required to register as a sex offender\n    with any government entity\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: We do not routinely verify the identity of our Users. But we may verify the User identity as part of our\n    fraud detection and prevention process.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/coffee-meets-bagel/eligibility/coffee-meets-bagel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Coffee Meets Bagel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Dating
- Dating App
- Social
- Relationships
- Mobile App
---
