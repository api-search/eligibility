---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: For properties in England and Wales, the laws of England and Wales apply to this contract. For properties in Scotland, the laws of Scotland apply.
  entity_types:
  - text: 'Your contract is between: – you, the person (or people) responsible for use of the electricity and gas (we call that energy) we supply to the domestic property'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Domestic use only
    text: Tell us if you change your premises from domestic to business use so we can make sure you are on the correct tariff.
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
name: E.ON Next
provenance_date: '2026-11-09'
provider_name: E.ON Next
provider_slug: eon-next
slug: eon-next-eligibility
source_date: '2026-11-09'
source_filename: eon-next-eligibility.yml
source_heading: Eligibility
source_page: https://www.eonnext.com/policies/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: E.ON Next\naid: eon-next\nurl: https://www.eonnext.com/policies/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: For properties in England and Wales, the laws of England and Wales apply to this contract. For properties\n    in Scotland, the laws of Scotland apply.\nentity_types:\n- type: individual\n  text: 'Your contract is between: – you, the person (or people) responsible for use of the electricity and gas\n    (we call that energy) we supply to the domestic property'\nrestricted_uses:\n- summary: Domestic use only\n  text: Tell us if\
  \ you change your premises from domestic to business use so we can make sure you are on the correct\n    tariff.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eon-next/eligibility/eon-next-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from E.ON Next's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Smart Metering
- Energy Retail
- Kraken
- Solar
- EV Charging
- Identity
---
