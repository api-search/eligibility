---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Services are available only to those individuals, firms or companies who can form legally binding contracts under the Indian laws.
  entity_types:
  - text: Services are available only to those individuals, firms or companies who can form legally binding contracts under the Indian laws.
    type: individual
  - text: firms or companies who can form legally binding contracts under the Indian laws
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: The User shall not use the Service for any unlawful purpose including without limitation criminal purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: HouseEazy shall verify the Account by requesting for the one-time password from the User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HouseEazy
provenance_date: '2026-11-09'
provider_name: HouseEazy
provider_slug: houseeazy
slug: houseeazy-eligibility
source_date: '2026-11-09'
source_filename: houseeazy-eligibility.yml
source_heading: Eligibility
source_page: https://www.houseeazy.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HouseEazy\naid: houseeazy\nurl: https://www.houseeazy.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Services are available only to those individuals, firms or companies who can form legally binding contracts\n    under the Indian laws.\nentity_types:\n- type: individual\n  text: Services are available only to those individuals, firms or companies who can form legally binding contracts\n    under the Indian laws.\n- type: business\n  text: firms or companies who can form legally binding contracts under the Indian laws\nrestricted_uses:\n- summary: Unlawful\
  \ or prohibited use\n  text: The User shall not use the Service for any unlawful purpose including without limitation criminal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: HouseEazy shall verify the Account by requesting for the one-time password from the User.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/houseeazy/eligibility/houseeazy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from HouseEazy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Real Estate
- PropTech
- Property
- Resale
- India
- Housing
---
