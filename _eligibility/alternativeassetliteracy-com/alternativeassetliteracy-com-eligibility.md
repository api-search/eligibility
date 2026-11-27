---
api_specs:
- filename: original.json
  format: json
  label: Alternative Asset Literacy API
  slug: alternative-asset-literacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alternativeassetliteracy-com/openapi/original.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not financial, investment, tax or legal advice
    text: Nothing in this application constitutes financial advice, investment advice, tax advice, legal advice, or any other form of professional advisory service.
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
name: alternativeassetliteracy-com
provenance_date: '2026-11-09'
provider_name: alternativeassetliteracy-com
provider_slug: alternativeassetliteracy-com
slug: alternativeassetliteracy-com-eligibility
source_date: '2026-11-09'
source_filename: alternativeassetliteracy-com-eligibility.yml
source_heading: Eligibility
source_page: https://alternativeassetliteracy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: alternativeassetliteracy-com\naid: alternativeassetliteracy-com\nurl: https://alternativeassetliteracy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not financial, investment, tax or legal advice\n  text: Nothing in this application constitutes financial advice, investment advice, tax advice, legal advice, or\n    any other form of professional advisory service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alternativeassetliteracy-com/eligibility/alternativeassetliteracy-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from alternativeassetliteracy-com's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Finance
- Alternative Assets
- DeFi
- Behavioral Economics
---
