---
api_specs:
- filename: base167-com-check-api-openapi.yml
  format: yaml
  label: BASE167 Check API
  slug: base167-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/base167-com/openapi/base167-com-check-api-openapi.yml
- filename: base167-com-games-api-openapi.yml
  format: yaml
  label: BASE167 Games API
  slug: base167-com-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/base167-com/openapi/base167-com-games-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This site is not directed at persons in jurisdictions where participation in token claims, crypto assets, or related activities is prohibited or restricted by law.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Jurisdictional restriction
    text: This site is not directed at persons in jurisdictions where participation in token claims, crypto assets, or related activities is prohibited or restricted by law.
  - summary: Minimum on-chain activity
    text: Eligibility to claim $BASE167 requires a minimum of 167 confirmed transactions on Base mainnet as verified at the time of the eligibility check.
  - summary: Gas allowance disqualification
    text: Holding more than the published gas allowance at the opening bell is an automatic disqualification.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are responsible for verifying your own eligibility.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BASE167
provenance_date: '2026-11-09'
provider_name: BASE167
provider_slug: base167-com
slug: base167-com-eligibility
source_date: '2026-11-09'
source_filename: base167-com-eligibility.yml
source_heading: Eligibility
source_page: https://base167.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BASE167\naid: base167-com\nurl: https://base167.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This site is not directed at persons in jurisdictions where participation in token claims, crypto assets,\n    or related activities is prohibited or restricted by law.\nentity_types: []\nrestricted_uses:\n- summary: Jurisdictional restriction\n  text: This site is not directed at persons in jurisdictions where participation in token claims, crypto assets,\n    or related activities is prohibited or restricted by law.\n- summary: Minimum on-chain activity\n  text: Eligibility\
  \ to claim $BASE167 requires a minimum of 167 confirmed transactions on Base mainnet as verified\n    at the time of the eligibility check.\n- summary: Gas allowance disqualification\n  text: Holding more than the published gas allowance at the opening bell is an automatic disqualification.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are responsible for verifying your own eligibility.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/base167-com/eligibility/base167-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 5 quoted statements, read from BASE167's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Gaming
- Cryptocurrency
- Tokens
- DegenGames
---
