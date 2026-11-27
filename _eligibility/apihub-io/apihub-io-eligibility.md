---
api_specs:
- filename: apihub-io-openapi-generated.yml
  format: yaml
  label: APIHub API
  slug: apihub-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihub-io/openapi/_ae-authored/apihub-io-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not be a resident of, or located in, any jurisdiction where use of cryptocurrency or the Service is prohibited by applicable law.
  entity_types:
  - text: Be at least 18 years of age, or the age of legal majority in your jurisdiction.
    type: individual
  minimum_age:
    text: Be at least 18 years of age, or the age of legal majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Sanctions evasion and illegal activity
    text: Engage in fraud, money laundering, terrorist financing, or sanctions evasion.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Not be listed on any government sanctions list or otherwise prohibited from engaging in financial transactions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: APIHub
provenance_date: '2026-11-09'
provider_name: APIHub
provider_slug: apihub-io
slug: apihub-io-eligibility
source_date: '2026-11-09'
source_filename: apihub-io-eligibility.yml
source_heading: Eligibility
source_page: https://apihub.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIHub\naid: apihub-io\nurl: https://apihub.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not be a resident of, or located in, any jurisdiction where use of cryptocurrency or the Service is prohibited\n    by applicable law.\nentity_types:\n- type: individual\n  text: Be at least 18 years of age, or the age of legal majority in your jurisdiction.\nrestricted_uses:\n- summary: Sanctions evasion and illegal activity\n  text: Engage in fraud, money laundering, terrorist financing, or sanctions evasion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Not be listed on any government sanctions list or otherwise prohibited from engaging in financial transactions.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age, or the age of legal majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/apihub-io/eligibility/apihub-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from APIHub's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- MCP
- Artificial Intelligence
- Payments
---
