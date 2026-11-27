---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: You may not use the service if you are on a U.S. sanctions list or in a country under comprehensive U.S. sanctions, or to send anything that U.S. export law forbids.
  entity_types:
  - text: You must be 18 or older and able to enter a binding contract where you live.
    type: individual
  - text: If you accept these terms for a company or other organization, you confirm you have authority to bind it, and "you" means that organization.
    type: business
  minimum_age:
    text: You must be 18 or older and able to enter a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: Sanctioned or export-controlled use
    text: You may not use the service if you are on a U.S. sanctions list or in a country under comprehensive U.S. sanctions, or to send anything that U.S. export law forbids.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UplinkSwitch
provenance_date: '2026-11-10'
provider_name: UplinkSwitch
provider_slug: uplinkswitch
slug: uplinkswitch-eligibility
source_date: '2026-11-10'
source_filename: uplinkswitch-eligibility.yml
source_heading: Eligibility
source_page: https://uplinkswitch.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UplinkSwitch\naid: uplinkswitch\nurl: https://uplinkswitch.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: You may not use the service if you are on a U.S. sanctions list or in a country under comprehensive U.S.\n    sanctions, or to send anything that U.S. export law forbids.\nentity_types:\n- type: individual\n  text: You must be 18 or older and able to enter a binding contract where you live.\n- type: business\n  text: If you accept these terms for a company or other organization, you confirm you have authority to bind it,\n    and \"you\" means that organization.\n\
  restricted_uses:\n- summary: Sanctioned or export-controlled use\n  text: You may not use the service if you are on a U.S. sanctions list or in a country under comprehensive U.S.\n    sanctions, or to send anything that U.S. export law forbids.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and able to enter a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/uplinkswitch/eligibility/uplinkswitch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from UplinkSwitch's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Gateways
- Reseller
- Platform
---
