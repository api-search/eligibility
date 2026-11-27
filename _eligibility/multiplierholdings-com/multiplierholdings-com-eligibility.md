---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Consumer” means an individual acting wholly or mainly outside that individual’s trade, business, craft or profession.
    type: individual
  - text: “Business User” means a User acting wholly or mainly for purposes relating to a trade, business, craft or profession.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or any higher minimum age required to enter these Terms under the law applicable to you.
    value: '18'
  restricted_uses:
  - summary: Only for relevant Professional Services and lawful purposes
    text: You may use the Platform only in connection with the relevant Professional Services and for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The relevant Portfolio Company invites you to use the Platform and creates and/or initiates your access. There is no separate public registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Multiplier
provenance_date: '2026-11-10'
provider_name: Multiplier
provider_slug: multiplierholdings-com
slug: multiplierholdings-com-eligibility
source_date: '2026-11-10'
source_filename: multiplierholdings-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.multiplierholdings.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Multiplier\naid: multiplierholdings-com\nurl: https://www.multiplierholdings.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “Consumer” means an individual acting wholly or mainly outside that individual’s trade, business, craft\n    or profession.\n- type: business\n  text: “Business User” means a User acting wholly or mainly for purposes relating to a trade, business, craft or\n    profession.\nrestricted_uses:\n- summary: Only for relevant Professional Services and lawful purposes\n  text: You may use the Platform only\
  \ in connection with the relevant Professional Services and for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The relevant Portfolio Company invites you to use the Platform and creates and/or initiates your access.\n    There is no separate public registration process.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or any higher minimum age required to enter these Terms under the law\n    applicable to you.\n"
source_yaml_url: https://artifacts.apis.io/multiplierholdings-com/eligibility/multiplierholdings-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Multiplier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Professional Services
- Technology
- Acquisition
---
