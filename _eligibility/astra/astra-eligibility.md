---
api_specs:
- filename: astra-accounts-api-openapi.yml
  format: yaml
  label: Astra Accounts API
  slug: astra-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-accounts-api-openapi.yml
- filename: astra-authorization-api-openapi.yml
  format: yaml
  label: Astra Authorization API
  slug: astra-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-authorization-api-openapi.yml
- filename: astra-cards-api-openapi.yml
  format: yaml
  label: Astra Cards API
  slug: astra-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-cards-api-openapi.yml
- filename: astra-instant-payment-eligibility-api-openapi.yml
  format: yaml
  label: Astra Instant Payment Eligibility API
  slug: astra-instant-payment-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-instant-payment-eligibility-api-openapi.yml
- filename: astra-payment-instruments-api-openapi.yml
  format: yaml
  label: Astra Payment Instruments API
  slug: astra-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-payment-instruments-api-openapi.yml
- filename: astra-routines-api-openapi.yml
  format: yaml
  label: Astra Routines API
  slug: astra-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-routines-api-openapi.yml
- filename: astra-transfers-api-openapi.yml
  format: yaml
  label: Astra Transfers API
  slug: astra-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-transfers-api-openapi.yml
- filename: astra-user-api-openapi.yml
  format: yaml
  label: Astra User API
  slug: astra-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-user-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we currently only support Third-Party Financial Institutions based in the United States.
  entity_types:
  - text: solely for your own personal or your own commercial use
    type: individual
  - text: both on behalf of yourself and the entity that you represent (if any).
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen years old.
    value: '18'
  restricted_uses:
  - summary: Firearm and ammunition sales
    text: firearm or ammunition sales;
  - summary: Marijuana-related businesses
    text: marijuana-related businesses (including but not limited to manufacturers, dispensaries, and those engaged in the business of marketing, buying, growing, selling, or otherwise promoting medical or recreational marijuana)
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we may request additional information or documentation. We may also be required to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Astra
provenance_date: '2026-11-09'
provider_name: Astra
provider_slug: astra
slug: astra-eligibility
source_date: '2026-11-09'
source_filename: astra-eligibility.yml
source_heading: Eligibility
source_page: https://astrafi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astra\naid: astra\nurl: https://astrafi.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we currently only support Third-Party Financial Institutions based in the United States.\nentity_types:\n- type: individual\n  text: solely for your own personal or your own commercial use\n- type: business\n  text: both on behalf of yourself and the entity that you represent (if any).\nrestricted_uses:\n- summary: Firearm and ammunition sales\n  text: firearm or ammunition sales;\n- summary: Marijuana-related businesses\n  text: marijuana-related businesses (including but not limited\
  \ to manufacturers, dispensaries, and those engaged\n    in the business of marketing, buying, growing, selling, or otherwise promoting medical or recreational marijuana)\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we may request additional information or documentation. We may also be required to verify your identity.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen years old.\n"
source_yaml_url: https://artifacts.apis.io/astra/eligibility/astra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Astra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Money Movement
- ACH
- Instant Payments
- Bank Transfers
- Disbursements
---
