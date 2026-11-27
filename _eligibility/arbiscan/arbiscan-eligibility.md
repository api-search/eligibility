---
api_specs:
- filename: arbiscan-accounts-api-openapi.yml
  format: yaml
  label: Arbiscan Accounts API
  slug: arbiscan-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbiscan/openapi/arbiscan-accounts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Your access to the API Services is at your own risk and you are responsible for compliance with jurisdictions as may be applicable to you.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal, money laundering or corruption use
    text: You are prohibited from using our API Services for any illegal activities or purposes, including but not limited to money laundering, corruption, or any actions that facilitate or promote such activities.
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
name: Arbiscan
provenance_date: '2026-11-09'
provider_name: Arbiscan
provider_slug: arbiscan
slug: arbiscan-eligibility
source_date: '2026-11-09'
source_filename: arbiscan-eligibility.yml
source_heading: Eligibility
source_page: https://arbiscan.io/apiterms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arbiscan\naid: arbiscan\nurl: https://arbiscan.io/apiterms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Your access to the API Services is at your own risk and you are responsible for compliance with jurisdictions\n    as may be applicable to you.\nentity_types: []\nrestricted_uses:\n- summary: No illegal, money laundering or corruption use\n  text: You are prohibited from using our API Services for any illegal activities or purposes, including but not\n    limited to money laundering, corruption, or any actions that facilitate or promote such activities.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arbiscan/eligibility/arbiscan-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Arbiscan's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Cryptocurrency
- Arbitrum
- Layer 2
- EVM
- Web3
---
