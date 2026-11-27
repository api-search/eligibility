---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, organized under the laws of, or a resident of, any country or region subject to comprehensive U.S. sanctions
  entity_types:
  - text: By using the Vault12 mobile or desktop application, you represent that you are 18 years of age or older
    type: individual
  minimum_age:
    text: you represent that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No sanctions evasion or illegal activity
    text: you will not use the Service to facilitate money laundering, terrorist financing, or any other illegal activity
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
name: Vault12
provenance_date: '2026-11-10'
provider_name: Vault12
provider_slug: vault12
slug: vault12-eligibility
source_date: '2026-11-10'
source_filename: vault12-eligibility.yml
source_heading: Eligibility
source_page: https://vault12.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vault12\naid: vault12\nurl: https://vault12.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, organized under the laws of, or a resident of, any country or region subject to\n    comprehensive U.S. sanctions\nentity_types:\n- type: individual\n  text: By using the Vault12 mobile or desktop application, you represent that you are 18 years of age or older\nrestricted_uses:\n- summary: No sanctions evasion or illegal activity\n  text: you will not use the Service to facilitate money laundering, terrorist financing, or any other illegal activity\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/vault12/eligibility/vault12-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vault12's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Security
- Backup
- Inheritance
- Wallets
- Cryptography
- Secret Sharing
- Key Management
---
