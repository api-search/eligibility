---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Services are intended for users who are 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Purchases and online interactions age-restricted
    text: Some features may be restricted to users aged 18 and above (e.g., purchases, online interactions).
  - summary: Gambling excluded
    text: Engage in gambling or betting using our Services unless explicitly authorised by us.
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
name: mojiworks
provenance_date: '2026-11-10'
provider_name: mojiworks
provider_slug: mojiworks
slug: mojiworks-eligibility
source_date: '2026-11-10'
source_filename: mojiworks-eligibility.yml
source_heading: Eligibility
source_page: https://mojiworks.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mojiworks\naid: mojiworks\nurl: https://mojiworks.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Purchases and online interactions age-restricted\n  text: Some features may be restricted to users aged 18 and above (e.g., purchases, online interactions).\n- summary: Gambling excluded\n  text: Engage in gambling or betting using our Services unless explicitly authorised by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Services\
  \ are intended for users who are 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/mojiworks/eligibility/mojiworks-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from mojiworks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Games
- Gaming
- Social Games
- Artificial Intelligence
- Generative AI
- Entertainment
- Consumer
---
