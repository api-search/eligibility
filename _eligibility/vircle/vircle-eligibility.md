---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    text: You must have a mailing address in Malaysia to enable Fasspay to process and approve your application.
  entity_types:
  - text: You must be an Adult, 18 years and above to register for a Primary Account.
    type: individual
  minimum_age:
    text: You must be an Adult, 18 years and above to register for a Primary Account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or criminal purposes
    text: use the Service and/or the Platform for any unlawful purposes including but not limited to vice, gambling, money laundering, terrorism financing or other criminal purposes whatsoever
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
name: Vircle
provenance_date: '2026-11-10'
provider_name: Vircle
provider_slug: vircle
slug: vircle-eligibility
source_date: '2026-11-10'
source_filename: vircle-eligibility.yml
source_heading: Eligibility
source_page: https://www.vircle.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vircle\naid: vircle\nurl: https://www.vircle.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MY\n  excluded: []\n  text: You must have a mailing address in Malaysia to enable Fasspay to process and approve your application.\nentity_types:\n- type: individual\n  text: You must be an Adult, 18 years and above to register for a Primary Account.\nrestricted_uses:\n- summary: Unlawful or criminal purposes\n  text: use the Service and/or the Platform for any unlawful purposes including but not limited to vice, gambling,\n    money laundering, terrorism financing or other criminal purposes whatsoever\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be an Adult, 18 years and above to register for a Primary Account.\n"
source_yaml_url: https://artifacts.apis.io/vircle/eligibility/vircle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vircle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Prepaid Cards
- Financial Literacy
- Family
- Kids
- Malaysia
---
