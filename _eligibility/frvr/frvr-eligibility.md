---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent that your legal guardian has reviewed and agrees to the Terms.
    type: individual
  minimum_age:
    text: You represent that you are 13 years old or older.
    value: '13'
  restricted_uses:
  - summary: Virtual currency cannot be cashed out
    text: Virtual Currency can never be redeemed for real money, goods, or any other item of monetary value from FRVR or any other party.
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
name: FRVR
provenance_date: '2026-11-09'
provider_name: FRVR
provider_slug: frvr
slug: frvr-eligibility
source_date: '2026-11-09'
source_filename: frvr-eligibility.yml
source_heading: Eligibility
source_page: https://frvr.com/legal/#TermsofService
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FRVR\naid: frvr\nurl: https://frvr.com/legal/#TermsofService\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent\n    that your legal guardian has reviewed and agrees to the Terms.\nrestricted_uses:\n- summary: Virtual currency cannot be cashed out\n  text: Virtual Currency can never be redeemed for real money, goods, or any other item of monetary value from FRVR\n    or any other party.\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are 13 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/frvr/eligibility/frvr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FRVR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Games
- Game Development
- SDK
- HTML5
- Instant Games
- Monetization
- Ads
- In-App Purchases
---
