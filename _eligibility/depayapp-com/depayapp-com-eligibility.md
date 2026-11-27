---
api_specs:
- filename: depayapp-com-openapi-generated.yml
  format: yaml
  label: Depay API
  slug: depayapp-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depayapp-com/openapi/_ae-authored/depayapp-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or sole proprietor on whose behalf a DePay account is created
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-transactional payment requests
    text: DePay strictly prohibits non-transactional payment requests.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: DePay shall unilaterally accept or reject potential Clients without giving reasons in accordance with its own internal rules, as well as international Anti-Money Laundering and Countering of Terrorism Financing regulations and guidelines
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Depay
provenance_date: '2026-11-09'
provider_name: Depay
provider_slug: depayapp-com
slug: depayapp-com-eligibility
source_date: '2026-11-09'
source_filename: depayapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://depay.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Depay\naid: depayapp-com\nurl: https://depay.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity or sole proprietor on whose behalf a DePay account is created\nrestricted_uses:\n- summary: Non-transactional payment requests\n  text: DePay strictly prohibits non-transactional payment requests.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: DePay shall unilaterally accept or reject potential Clients without giving reasons in accordance with its\n    own internal rules, as well as international\
  \ Anti-Money Laundering and Countering of Terrorism Financing regulations\n    and guidelines\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/depayapp-com/eligibility/depayapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Depay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Web3
- Fintech
---
