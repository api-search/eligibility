---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account or using Servd, you agree to these Terms of Service on behalf of your business.
    type: business
  - text: You must be authorized to bind your business and be of legal age to enter a contract.
    type: individual
  minimum_age:
    text: be of legal age to enter a contract
    value: legal age
  restricted_uses:
  - summary: Unlawful goods, fraud, money laundering
    text: Use Servd for unlawful goods, fraud, or money laundering.
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
name: getservd-me
provenance_date: '2026-11-09'
provider_name: getservd-me
provider_slug: getservd-me
slug: getservd-me-eligibility
source_date: '2026-11-09'
source_filename: getservd-me-eligibility.yml
source_heading: Eligibility
source_page: https://getservd.me/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: getservd-me\naid: getservd-me\nurl: https://getservd.me/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By creating an account or using Servd, you agree to these Terms of Service on behalf of your business.\n- type: individual\n  text: You must be authorized to bind your business and be of legal age to enter a contract.\nrestricted_uses:\n- summary: Unlawful goods, fraud, money laundering\n  text: Use Servd for unlawful goods, fraud, or money laundering.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: legal age\n  text: be of legal age to enter a contract\n"
source_yaml_url: https://artifacts.apis.io/getservd-me/eligibility/getservd-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from getservd-me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Tech
- Commerce
- Software-as-a-Service
- Restaurant
---
