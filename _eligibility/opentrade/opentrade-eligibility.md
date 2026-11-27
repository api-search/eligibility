---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SY
    served: []
    text: you are not organized in or operating under the jurisdiction of Iran, Cuba, North Korea, Syria or the Crimean Region of the Ukraine, or any other jurisdiction to which the United States, United Kingdom or European Union embargoes goods or imposes similar sanctions
  entity_types:
  - text: Authorised User acting on behalf of a Borrower or Lender
    type: individual
  - text: you are and shall remain duly organized, validly existing and in good standing under the laws of the jurisdiction in which you are incorporated, registered or established
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and illegal activity prohibited
    text: you shall not undertake any illegal activity or take any actions which may constitute illegal activity or facilitate the illegal activity of a third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide us with complete and accurate information in response to requests made as part of our on-boarding and due diligence process, or as may be otherwise necessary for us to complete the Registration Process or verify the Eligibility Requirements.
excluded_countries:
- IR
- CU
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Opentrade
provenance_date: '2026-11-10'
provider_name: Opentrade
provider_slug: opentrade
slug: opentrade-eligibility
source_date: '2026-11-10'
source_filename: opentrade-eligibility.yml
source_heading: Eligibility
source_page: https://docs.opentrade.io/terms-and-conditions/platform-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opentrade\naid: opentrade\nurl: https://docs.opentrade.io/terms-and-conditions/platform-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SY\n  text: you are not organized in or operating under the jurisdiction of Iran, Cuba, North Korea, Syria or the Crimean\n    Region of the Ukraine, or any other jurisdiction to which the United States, United Kingdom or European Union\n    embargoes goods or imposes similar sanctions\nentity_types:\n- type: individual\n  text: Authorised User acting on behalf of a Borrower or Lender\n- type: business\n  text: you\
  \ are and shall remain duly organized, validly existing and in good standing under the laws of the jurisdiction\n    in which you are incorporated, registered or established\nrestricted_uses:\n- summary: Sanctions and illegal activity prohibited\n  text: you shall not undertake any illegal activity or take any actions which may constitute illegal activity or\n    facilitate the illegal activity of a third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide us with complete and accurate information in response to requests made as part of our on-boarding\n    and due diligence process, or as may be otherwise necessary for us to complete the Registration Process or verify\n    the Eligibility Requirements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opentrade/eligibility/opentrade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Opentrade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Stablecoins
- Yield
- Lending
- Treasury Management
- Embedded Finance
- Tokenization
- Real World Assets
- DeFi
- Fintech Infrastructure
- Blockchain
- Fixed Income
---
