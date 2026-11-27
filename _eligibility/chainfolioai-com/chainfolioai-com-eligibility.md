---
api_specs:
- filename: chainfolioai-com-openapi-generated.yml
  format: yaml
  label: ChainFolioAI API
  slug: chainfolioai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainfolioai-com/openapi/_ae-authored/chainfolioai-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18.
    type: individual
  minimum_age:
    text: You must be at least 18.
    value: '18'
  restricted_uses:
  - summary: AI answers not advice
    text: AI assistant answers are generated automatically, may contain errors and never constitute financial, tax or investment advice.
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
name: ChainFolioAI
provenance_date: '2026-11-09'
provider_name: ChainFolioAI
provider_slug: chainfolioai-com
slug: chainfolioai-com-eligibility
source_date: '2026-11-09'
source_filename: chainfolioai-com-eligibility.yml
source_heading: Eligibility
source_page: https://chainfolioai.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChainFolioAI\naid: chainfolioai-com\nurl: https://chainfolioai.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18.\nrestricted_uses:\n- summary: AI answers not advice\n  text: AI assistant answers are generated automatically, may contain errors and never constitute financial, tax\n    or investment advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/chainfolioai-com/eligibility/chainfolioai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ChainFolioAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Portfolio
- Finance
- Artificial Intelligence
- Non-Custodial
---
