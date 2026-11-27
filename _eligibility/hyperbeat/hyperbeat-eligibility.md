---
api_specs:
- filename: hyperbeat-hyperliquid-api-openapi.yml
  format: yaml
  label: Hyperbeat Hyperliquid API
  slug: hyperbeat-hyperliquid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperbeat/openapi/hyperbeat-hyperliquid-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: a citizen of, or located in or ordinarily resident in any of the Restricted Jurisdictions (defined below)
  entity_types:
  - text: an adult of the legal age of majority in your country or state of residence (whichever is higher), and are lawfully able to enter into contracts.
    type: individual
  - text: If you are entering into this Agreement for an entity, such as the company you work for, you represent and warrant that you have legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: an adult of the legal age of majority in your country or state of residence (whichever is higher)
    value: age of majority
  restricted_uses:
  - summary: Illegal use in user's jurisdiction
    text: You shall not access or use our Platform or Services if it would be illegal, or a violation of any applicable laws or regulations, to do so within your jurisdiction.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you must provide current, complete, and accurate information for all required elements on the verification page, including your full legal name and the legal name of your organization.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hyperbeat
provenance_date: '2026-11-09'
provider_name: Hyperbeat
provider_slug: hyperbeat
slug: hyperbeat-eligibility
source_date: '2026-11-09'
source_filename: hyperbeat-eligibility.yml
source_heading: Eligibility
source_page: https://hyperbeat.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hyperbeat\naid: hyperbeat\nurl: https://hyperbeat.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: a citizen of, or located in or ordinarily resident in any of the Restricted Jurisdictions (defined below)\nentity_types:\n- type: individual\n  text: an adult of the legal age of majority in your country or state of residence (whichever is higher), and are\n    lawfully able to enter into contracts.\n- type: business\n  text: If you are entering into this Agreement for an entity, such as the company you work for, you represent and\n    warrant that you have\
  \ legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Illegal use in user's jurisdiction\n  text: You shall not access or use our Platform or Services if it would be illegal, or a violation of any applicable\n    laws or regulations, to do so within your jurisdiction.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you must provide current, complete, and accurate information for all required elements on the verification\n    page, including your full legal name and the legal name of your organization.\nminimum_age:\n  value: age of majority\n  text: an adult of the legal age of majority in your country or state of residence (whichever is higher)\n"
source_yaml_url: https://artifacts.apis.io/hyperbeat/eligibility/hyperbeat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hyperbeat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Staking
- Liquid Staking
- Hyperliquid
- HyperEVM
- Blockchain
- Web3
- Cryptocurrency
- Yield
---
