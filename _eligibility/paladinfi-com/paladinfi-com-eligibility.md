---
api_specs:
- filename: paladinfi-com-health-api-openapi.yml
  format: yaml
  label: paladinfi-com Health API
  slug: paladinfi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paladinfi-com/openapi/paladinfi-com-health-api-openapi.yml
- filename: paladinfi-com-trust-check-api-openapi.yml
  format: yaml
  label: paladinfi-com Trust Check API
  slug: paladinfi-com-trust-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paladinfi-com/openapi/paladinfi-com-trust-check-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - EEA
    - GB
    - CH
    served: []
    text: (e) are not located in the European Economic Area, the United Kingdom, or Switzerland. The Service is not offered to users in those jurisdictions
  entity_types:
  - text: (a) are at least 18 years of age, (b) have the legal capacity to enter into a binding contract
    type: individual
  minimum_age:
    text: (a) are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Money laundering, sanctions evasion, fraud
    text: Engage in money laundering, terrorist financing, sanctions evasion, fraud, or any illegal activity
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: does not perform Know-Your-Customer (KYC) verification
excluded_countries:
- EEA
- GB
- CH
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: paladinfi-com
provenance_date: '2026-11-10'
provider_name: paladinfi-com
provider_slug: paladinfi-com
slug: paladinfi-com-eligibility
source_date: '2026-11-10'
source_filename: paladinfi-com-eligibility.yml
source_heading: Eligibility
source_page: https://paladinfi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: paladinfi-com\naid: paladinfi-com\nurl: https://paladinfi.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - EEA\n  - GB\n  - CH\n  text: (e) are not located in the European Economic Area, the United Kingdom, or Switzerland. The Service is not\n    offered to users in those jurisdictions\nentity_types:\n- type: individual\n  text: (a) are at least 18 years of age, (b) have the legal capacity to enter into a binding contract\nrestricted_uses:\n- summary: Money laundering, sanctions evasion, fraud\n  text: Engage in money laundering, terrorist financing, sanctions evasion, fraud,\
  \ or any illegal activity\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: does not perform Know-Your-Customer (KYC) verification\nminimum_age:\n  value: '18'\n  text: (a) are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/paladinfi-com/eligibility/paladinfi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from paladinfi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeFi
- Artificial Intelligence
- Infrastructure
- Finance
- Base
---
