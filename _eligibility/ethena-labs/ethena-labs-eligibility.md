---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Users in the United States are not eligible to become a Mint User.
  entity_types:
  - text: In registering to use the Company Services as a Mint User on behalf of an entity, you represent and warrant that (i) such legal entity is duly organized and validly existing under the applicable laws of the jurisdiction of its organization
    type: business
  minimum_age:
    text: you are at least 18 years old and are not a Restricted Person
    value: '18'
  restricted_uses:
  - summary: Illegal activity and sanctions
    text: you will not be using your status as a Mint User and Services for any illegal activity, including, but not limited to, illegal gambling, money laundering, fraud
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ethena Labs
provenance_date: '2026-11-09'
provider_name: Ethena Labs
provider_slug: ethena-labs
slug: ethena-labs-eligibility
source_date: '2026-11-09'
source_filename: ethena-labs-eligibility.yml
source_heading: Eligibility
source_page: https://docs.ethena.fi/resources/usde-mint-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ethena Labs\naid: ethena-labs\nurl: https://docs.ethena.fi/resources/usde-mint-user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Users in the United States are not eligible to become a Mint User.\nentity_types:\n- type: business\n  text: In registering to use the Company Services as a Mint User on behalf of an entity, you represent and warrant\n    that (i) such legal entity is duly organized and validly existing under the applicable laws of the jurisdiction\n    of its organization\nrestricted_uses:\n- summary: Illegal activity and sanctions\n  text: you will not\
  \ be using your status as a Mint User and Services for any illegal activity, including, but not\n    limited to, illegal gambling, money laundering, fraud\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old and are not a Restricted Person\n"
source_yaml_url: https://artifacts.apis.io/ethena-labs/eligibility/ethena-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ethena Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Stablecoins
- DeFi
- Synthetic Dollar
- Minting
- Blockchain
- Ethereum
---
