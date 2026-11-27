---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For natural persons intending to register on the Coinmetro Platform as a private user, by signing up to the Coinmetro Platform, client certify that client are 18 years of age or older
    type: individual
  - text: For legal persons intending to register on the Coinmetro Platform as an institutional user, client must demonstrate that the legal person is registered in a business registry in a country or region accepted by Coinmetro
    type: business
  minimum_age:
    text: client certify that client are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: AML/sanctions violations
    text: The Client warrants that he/she will not use the Coinmetro Platform to hold or trade in funds or digital assets which client knows or suspect to be in violation of anti-money laundering laws, sanctions, or other relevant related regulations.
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
name: Coinmetro
provenance_date: '2026-11-09'
provider_name: Coinmetro
provider_slug: coinmetro
slug: coinmetro-eligibility
source_date: '2026-11-09'
source_filename: coinmetro-eligibility.yml
source_heading: Eligibility
source_page: https://coinmetro.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coinmetro\naid: coinmetro\nurl: https://coinmetro.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: For natural persons intending to register on the Coinmetro Platform as a private user, by signing up to\n    the Coinmetro Platform, client certify that client are 18 years of age or older\n- type: business\n  text: For legal persons intending to register on the Coinmetro Platform as an institutional user, client must\n    demonstrate that the legal person is registered in a business registry in a country or region accepted\
  \ by Coinmetro\nrestricted_uses:\n- summary: AML/sanctions violations\n  text: The Client warrants that he/she will not use the Coinmetro Platform to hold or trade in funds or digital\n    assets which client knows or suspect to be in violation of anti-money laundering laws, sanctions, or other relevant\n    related regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: client certify that client are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/coinmetro/eligibility/coinmetro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Coinmetro's own page on 2026-11-09.
synthetic: false
tags:
- Spot Trading
- Margin Trading
- Staking
- Auto-Invest
---
