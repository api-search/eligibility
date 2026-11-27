---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You shall not use Ramper Services if you are a person barred from receiving Ramper Services under the laws of any applicable jurisdictions, including the country in which you are resident or from which you use Ramper Services.
  entity_types:
  - text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent and warrant that you have the full legal authority to bind your employer or such entity to these Terms.
    type: business
  minimum_age:
    text: Ramper Services available only to entities and/or persons who have reached the age of legal majority and are competent to enter into a legal binding agreement under applicable laws.
    value: null
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
name: Ramper
provenance_date: '2026-11-10'
provider_name: Ramper
provider_slug: ramper
slug: ramper-eligibility
source_date: '2026-11-10'
source_filename: ramper-eligibility.yml
source_heading: Eligibility
source_page: https://docs.ramper.xyz/embedded-wallet-sdk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ramper\naid: ramper\nurl: https://docs.ramper.xyz/embedded-wallet-sdk/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You shall not use Ramper Services if you are a person barred from receiving Ramper Services under the laws\n    of any applicable jurisdictions, including the country in which you are resident or from which you use Ramper\n    Services.\nentity_types:\n- type: business\n  text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent\n    and warrant that you have the full legal authority to bind\
  \ your employer or such entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Ramper Services available only to entities and/or persons who have reached the age of legal majority and\n    are competent to enter into a legal binding agreement under applicable laws.\n"
source_yaml_url: https://artifacts.apis.io/ramper/eligibility/ramper-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ramper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Wallets
- Embedded Wallets
- Blockchain
- Social Login
- Authentication
- SDK
- NFT
- Cryptocurrency
- DeFi
---
