---
api_specs:
- filename: evervault-core-api-openapi.yml
  format: yaml
  label: Evervault Core API
  slug: evervault-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-core-api-openapi.yml
- filename: evervault-payments-api-openapi.yml
  format: yaml
  label: Evervault Payments API
  slug: evervault-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-payments-api-openapi.yml
- filename: evervault-webhooks-api-openapi.yml
  format: yaml
  label: Evervault Webhooks API
  slug: evervault-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-webhooks-api-openapi.yml
- filename: evervault-evervault-api-api-openapi.yml
  format: yaml
  label: Evervault API
  slug: evervault-evervault-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-evervault-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual or sole proprietor, and you are not at least 18 years old, but you are 13 years old or older, your Representative must be your parent or legal guardian.
    type: individual
  - text: If you are a legal entity that is owned, directly or indirectly, by an individual who is not at least 18 years old
    type: business
  minimum_age:
    text: You may not use the Services if you are under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Fraudulent or illegal use
    text: for an unauthorised, fraudulent or illegal purpose
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: we may require additional information from you to verify beneficial ownership or control of the business, validate information you provided, verify you or your Representative’s identity, and assess the risk associated with your business.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evervault
provenance_date: '2026-11-09'
provider_name: Evervault
provider_slug: evervault
slug: evervault-eligibility
source_date: '2026-11-09'
source_filename: evervault-eligibility.yml
source_heading: Eligibility
source_page: https://evervault.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evervault\naid: evervault\nurl: https://evervault.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual or sole proprietor, and you are not at least 18 years old, but you are 13 years\n    old or older, your Representative must be your parent or legal guardian.\n- type: business\n  text: If you are a legal entity that is owned, directly or indirectly, by an individual who is not at least 18\n    years old\nrestricted_uses:\n- summary: Fraudulent or illegal use\n  text: for an unauthorised,\
  \ fraudulent or illegal purpose\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: we may require additional information from you to verify beneficial ownership or control of the business,\n    validate information you provided, verify you or your Representative’s identity, and assess the risk associated\n    with your business.\nminimum_age:\n  value: '13'\n  text: You may not use the Services if you are under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/evervault/eligibility/evervault-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Evervault's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Security
- Encryption
- Payments
- PCI Compliance
- Tokenization
- Cards
- Developer Tools
---
