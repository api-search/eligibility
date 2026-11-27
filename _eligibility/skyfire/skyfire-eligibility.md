---
api_specs:
- filename: skyfire-agents-api-openapi.yml
  format: yaml
  label: Skyfire Agents API
  slug: skyfire-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyfire/openapi/skyfire-agents-api-openapi.yml
- filename: skyfire-auth-api-openapi.yml
  format: yaml
  label: Skyfire Auth API
  slug: skyfire-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyfire/openapi/skyfire-auth-api-openapi.yml
- filename: skyfire-directory-api-openapi.yml
  format: yaml
  label: Skyfire Directory API
  slug: skyfire-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyfire/openapi/skyfire-directory-api-openapi.yml
- filename: skyfire-organizations-api-openapi.yml
  format: yaml
  label: Skyfire Organizations API
  slug: skyfire-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyfire/openapi/skyfire-organizations-api-openapi.yml
- filename: skyfire-tokens-api-openapi.yml
  format: yaml
  label: Skyfire Tokens API
  slug: skyfire-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyfire/openapi/skyfire-tokens-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: High-Risk Jurisdiction means ... Cuba, Iran, North Korea, and Syria, and the Crimea, Donetsk, and Luhansk regions.
  entity_types:
  - text: You must be 13 years of age or older to use the Skyfire Services.
    type: individual
  - text: If you are an individual using the Skyfire Services on behalf of a business entity or non-profit organization, then you represent to Skyfire that (a) you are authorized to provide User Information
    type: business
  minimum_age:
    text: You must be 13 years of age or older to use the Skyfire Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited or restricted businesses
    text: you do not use the Skyfire Services to conduct a Prohibited or Restricted Business
  - summary: Missile, nuclear, chemical or biological weapons
    text: You must not use the Skyfire Technology for any purposes prohibited by Law, including the development, design, manufacture or production of missiles, nuclear, chemical or biological weapons.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Skyfire may require you to provide additional information or documentation demonstrating your authority.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skyfire
provenance_date: '2026-11-10'
provider_name: Skyfire
provider_slug: skyfire
slug: skyfire-eligibility
source_date: '2026-11-10'
source_filename: skyfire-eligibility.yml
source_heading: Eligibility
source_page: https://skyfire.xyz/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skyfire\naid: skyfire\nurl: https://skyfire.xyz/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: High-Risk Jurisdiction means ... Cuba, Iran, North Korea, and Syria, and the Crimea, Donetsk, and Luhansk\n    regions.\nentity_types:\n- type: individual\n  text: You must be 13 years of age or older to use the Skyfire Services.\n- type: business\n  text: If you are an individual using the Skyfire Services on behalf of a business entity or non-profit organization,\n    then you represent to Skyfire that (a) you are authorized to provide User\
  \ Information\nrestricted_uses:\n- summary: Prohibited or restricted businesses\n  text: you do not use the Skyfire Services to conduct a Prohibited or Restricted Business\n- summary: Missile, nuclear, chemical or biological weapons\n  text: You must not use the Skyfire Technology for any purposes prohibited by Law, including the development, design,\n    manufacture or production of missiles, nuclear, chemical or biological weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Skyfire may require you to provide additional information or documentation demonstrating your authority.\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to use the Skyfire Services.\n"
source_yaml_url: https://artifacts.apis.io/skyfire/eligibility/skyfire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Skyfire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Agentic Payments
- Identity
- Payments
- Authentication
- Stablecoins
- MCP
- Agentic Commerce
- Know Your Agent
---
