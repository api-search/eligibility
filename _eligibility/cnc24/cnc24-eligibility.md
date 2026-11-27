---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The GTC shall only apply if the Customer is an entrepreneur (§ 14 BGB), a legal entity under public law or a special fund under public law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No weapons use
    text: is not used by the Customer as or for weapons, weapons of war within the meaning of the War Weapons Control Act or commissioned for this purpose
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
name: CNC24
provenance_date: '2026-11-09'
provider_name: CNC24
provider_slug: cnc24
slug: cnc24-eligibility
source_date: '2026-11-09'
source_filename: cnc24-eligibility.yml
source_heading: Eligibility
source_page: https://www.cnc24.com/gtc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CNC24\naid: cnc24\nurl: https://www.cnc24.com/gtc/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The GTC shall only apply if the Customer is an entrepreneur (§ 14 BGB), a legal entity under public law\n    or a special fund under public law.\nrestricted_uses:\n- summary: No weapons use\n  text: is not used by the Customer as or for weapons, weapons of war within the meaning of the War Weapons Control\n    Act or commissioned for this purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cnc24/eligibility/cnc24-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CNC24's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- CNC Machining
- On-Demand Manufacturing
- Custom Parts
- Procurement
- Supply Chain
- Prototyping
- Germany
---
