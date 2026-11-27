---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are only available to legal residents of the UnitedStates.
  entity_types:
  - text: You must be 18 years of age or older to receive messages.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to receive messages.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You agree that you will only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to require you to prove that you are at least 18 years of age if so requested.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WeStock
provenance_date: '2026-11-10'
provider_name: WeStock
provider_slug: westock
slug: westock-eligibility
source_date: '2026-11-10'
source_filename: westock-eligibility.yml
source_heading: Eligibility
source_page: https://www.westock.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeStock\naid: westock\nurl: https://www.westock.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are only available to legal residents of the UnitedStates.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to receive messages.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You agree that you will only use the Services for your own internal, personal, non-commercial use, and not\n    on behalf of or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: We reserve the right to require you to prove that you are at least 18 years of age if so requested.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to receive messages.\n"
source_yaml_url: https://artifacts.apis.io/westock/eligibility/westock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from WeStock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shopper Marketing
- Consumer Packaged Goods
- Retail Media
- Marketing
- Rebates
- Audience Building
- Trade Promotion
- First-Party Data
- Retail
- Advertising
---
