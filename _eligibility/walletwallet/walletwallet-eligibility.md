---
api_specs:
- filename: walletwallet-openapi-generated.yml
  format: yaml
  label: WalletWallet API
  slug: walletwallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/walletwallet/openapi/_ae-authored/walletwallet-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for businesses and developers, not consumers.
    type: business
  - text: WalletWallet is a developer tool for creating and updating Apple Wallet and Google Wallet passes.
    type: developer
  - text: The Free plan is for personal, non-commercial use only.
    type: individual
  minimum_age:
    text: You must provide accurate information and be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No special-category, payment card or government ID data
    text: You must not submit to the Service, or place in any Pass, any special-category personal data under Article 9 GDPR
  - summary: Free plan limited to personal use
    text: The Free plan is for personal, non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You register with an email address (via a one-time code or Google sign-in).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WalletWallet
provenance_date: '2026-11-10'
provider_name: WalletWallet
provider_slug: walletwallet
slug: walletwallet-eligibility
source_date: '2026-11-10'
source_filename: walletwallet-eligibility.yml
source_heading: Eligibility
source_page: https://www.walletwallet.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WalletWallet\naid: walletwallet\nurl: https://www.walletwallet.dev/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for businesses and developers, not consumers.\n- type: developer\n  text: WalletWallet is a developer tool for creating and updating Apple Wallet and Google Wallet passes.\n- type: individual\n  text: The Free plan is for personal, non-commercial use only.\nrestricted_uses:\n- summary: No special-category, payment card or government ID data\n  text: You must not submit to the Service, or place\
  \ in any Pass, any special-category personal data under Article\n    9 GDPR\n- summary: Free plan limited to personal use\n  text: The Free plan is for personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You register with an email address (via a one-time code or Google sign-in).\nminimum_age:\n  value: '18'\n  text: You must provide accurate information and be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/walletwallet/eligibility/walletwallet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from WalletWallet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wallets
- Passes
- Digital
---
