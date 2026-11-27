---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To access or use the Apps, you must be 17 years or older and have the power and authority to enter into these Terms.
    type: individual
  minimum_age:
    text: To access or use the Apps, you must be 17 years or older and have the power and authority to enter into these Terms.
    value: '17'
  restricted_uses:
  - summary: Coins not transferable or redeemable
    text: Coins have no cash value, are not legal tender, are not redeemable for any sum of money or monetary value from us or any third party, and may not be used outside of the Apps.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Redemption may require identity verification (e.g., KYC). If you fail to verify as required, we may delay or deny redemption.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tibles
provenance_date: '2026-11-10'
provider_name: Tibles
provider_slug: tibles
slug: tibles-eligibility
source_date: '2026-11-10'
source_filename: tibles-eligibility.yml
source_heading: Eligibility
source_page: https://www.tibles.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tibles\naid: tibles\nurl: https://www.tibles.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To access or use the Apps, you must be 17 years or older and have the power and authority to enter into\n    these Terms.\nrestricted_uses:\n- summary: Coins not transferable or redeemable\n  text: Coins have no cash value, are not legal tender, are not redeemable for any sum of money or monetary value\n    from us or any third party, and may not be used outside of the Apps.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Redemption may require identity verification (e.g., KYC). If you fail to verify as required, we may delay\n    or deny redemption.\nminimum_age:\n  value: '17'\n  text: To access or use the Apps, you must be 17 years or older and have the power and authority to enter into\n    these Terms.\n"
source_yaml_url: https://artifacts.apis.io/tibles/eligibility/tibles-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Tibles's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Digital Collectibles
- NFT
- Flow Blockchain
- Trading Cards
- Consumer App
---
