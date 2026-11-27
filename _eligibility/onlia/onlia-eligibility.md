---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.
  entity_types:
  - text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.
    type: individual
  minimum_age:
    text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.
    value: age of majority
  restricted_uses:
  - summary: Lawful use only
    text: You agree that your use of the site shall not violate any applicable local, national, provincial/territorial, or international laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: any purchase of insurance products through Us is subject to underwriting eligibility criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Onlia
provenance_date: '2026-11-10'
provider_name: Onlia
provider_slug: onlia
slug: onlia-eligibility
source_date: '2026-11-10'
source_filename: onlia-eligibility.yml
source_heading: Eligibility
source_page: https://www.onlia.ca/about/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onlia\naid: onlia\nurl: https://www.onlia.ca/about/conditions-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.\nentity_types:\n- type: individual\n  text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree that your use of the site shall not violate any applicable local, national, provincial/territorial,\n    or international laws\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: any purchase of insurance products through Us is subject to underwriting eligibility criteria.\nminimum_age:\n  value: age of majority\n  text: The Onlia Agency Website is intended for visitors from Canada only, who have reached the age of majority.\n"
source_yaml_url: https://artifacts.apis.io/onlia/eligibility/onlia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Onlia's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Insurtech
- Brokerage
- Personal Lines
- Auto Insurance
- Home Insurance
- Direct to Consumer
- Ontario
---
