---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old and/or otherwise be authorized and have legal power to accept these Terms with binding effect
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: You also agree not to use the Services for any fraudulent purposes, or in connection with a criminal offense or other unlawful activity
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
name: Instabee
provenance_date: '2026-11-09'
provider_name: Instabee
provider_slug: instabee
slug: instabee-eligibility
source_date: '2026-11-09'
source_filename: instabee-eligibility.yml
source_heading: Eligibility
source_page: https://www.instabee.com/legal/general-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instabee\naid: instabee\nurl: https://www.instabee.com/legal/general-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old and/or otherwise be authorized and have legal power to accept\n    these Terms with binding effect\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: You also agree not to use the Services for any fraudulent purposes, or in connection with a criminal offense\n    or other unlawful activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/instabee/eligibility/instabee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Instabee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Logistics
- Last Mile Delivery
- Shipping
- E-Commerce
- Parcel Lockers
- Returns
- Nordic
---
