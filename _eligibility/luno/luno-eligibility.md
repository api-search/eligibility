---
api_specs:
- filename: luno-streaming-asyncapi.yml
  format: yaml
  label: Luno API
  slug: luno-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/luno/asyncapi/luno-streaming-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - ZA
    text: Luno (Pty) Ltd is a company incorporated under the laws of South Africa. Depending on your country of residence, you may not be able to use all the functions of the Luno Site.
  entity_types:
  - text: You are 18 years of age or over and have full capacity to accept the Terms
    type: individual
  - text: You will follow the Luno Business account application process if you seek to open and use a Luno Account for a non-individual legal entity (e.g. a company, trust or partnership);
    type: business
  minimum_age:
    text: You are 18 years of age or over and have full capacity to accept the Terms
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited activity
    text: You will not use your Luno Account for or in relation to any illegal activity, any Prohibited Activity, in violation of any laws, statutes, ordinances or regulations, or in breach of Luno’s Export Controls and Sanctions requirements.
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
name: Luno
provenance_date: '2026-11-10'
provider_name: Luno
provider_slug: luno
slug: luno-eligibility
source_date: '2026-11-10'
source_filename: luno-eligibility.yml
source_heading: Eligibility
source_page: https://www.luno.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luno\naid: luno\nurl: https://www.luno.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ZA\n  excluded: []\n  text: Luno (Pty) Ltd is a company incorporated under the laws of South Africa. Depending on your country of residence,\n    you may not be able to use all the functions of the Luno Site.\nentity_types:\n- type: individual\n  text: You are 18 years of age or over and have full capacity to accept the Terms\n- type: business\n  text: You will follow the Luno Business account application process if you seek to open and use a Luno Account\n    for a non-individual\
  \ legal entity (e.g. a company, trust or partnership);\nrestricted_uses:\n- summary: Illegal or prohibited activity\n  text: You will not use your Luno Account for or in relation to any illegal activity, any Prohibited Activity,\n    in violation of any laws, statutes, ordinances or regulations, or in breach of Luno’s Export Controls and Sanctions\n    requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are 18 years of age or over and have full capacity to accept the Terms\n"
source_yaml_url: https://artifacts.apis.io/luno/eligibility/luno-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Luno's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Bitcoin
- Ethereum
- Trading
- Fintech
- Wallets
- Blockchain
- Financial Services
- Real-Time
---
