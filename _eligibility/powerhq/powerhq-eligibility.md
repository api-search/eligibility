---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: maintains licenses and required regulatory approvals to provide Services in the states in which it operates
  entity_types:
  - text: you must register for and maintain an active personal user Services account
    type: individual
  - text: allows businesses and consumers to buy electricity
    type: business
  minimum_age:
    text: null
    value: null
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
name: PowerHQ
provenance_date: '2026-11-10'
provider_name: PowerHQ
provider_slug: powerhq
slug: powerhq-eligibility
source_date: '2026-11-10'
source_filename: powerhq-eligibility.yml
source_heading: Eligibility
source_page: https://www.powerhq.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PowerHQ\naid: powerhq\nurl: https://www.powerhq.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: maintains licenses and required regulatory approvals to provide Services in the states in which it operates\nentity_types:\n- type: individual\n  text: you must register for and maintain an active personal user Services account\n- type: business\n  text: allows businesses and consumers to buy electricity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/powerhq/eligibility/powerhq-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from PowerHQ's own page on 2026-11-10.
synthetic: false
tags:
- Energy Commerce
- Retail Electricity
- Marketplace
- Energy Providers
- Developers
- Partners
---
