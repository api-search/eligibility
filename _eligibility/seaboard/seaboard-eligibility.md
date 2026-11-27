---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This website is designed for and intended for use by adults. If you are under 18, you may use this Site only with involvement of a parent or guardian.
    type: individual
  minimum_age:
    text: If you are under 18, you may use this Site only with involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Upload or transmit any Content that would constitute or encourage a criminal offense, violate the rights of any party
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
name: Seaboard
provenance_date: '2026-11-10'
provider_name: Seaboard
provider_slug: seaboard
slug: seaboard-eligibility
source_date: '2026-11-10'
source_filename: seaboard-eligibility.yml
source_heading: Eligibility
source_page: https://www.seaboardcorp.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seaboard\naid: seaboard\nurl: https://www.seaboardcorp.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This website is designed for and intended for use by adults. If you are under 18, you may use this Site\n    only with involvement of a parent or guardian.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Upload or transmit any Content that would constitute or encourage a criminal offense, violate the rights\n    of any party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use this Site only with involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/seaboard/eligibility/seaboard-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Seaboard's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
- Agribusiness
- Ocean Transportation
- Container Shipping
- Pork Production
- Commodity Trading
- Grain Milling
- Power Generation
- Logistics
- EDI
---
