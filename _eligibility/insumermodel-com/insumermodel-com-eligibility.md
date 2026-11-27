---
api_specs:
- filename: insumermodel-com-agent-commerce-protocols-api-openapi.yml
  format: yaml
  label: insumermodel-com Agent Commerce Protocols API
  slug: insumermodel-com-agent-commerce-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-agent-commerce-protocols-api-openapi.yml
- filename: insumermodel-com-agent-onboarding-api-openapi.yml
  format: yaml
  label: insumermodel-com Agent Onboarding API
  slug: insumermodel-com-agent-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-agent-onboarding-api-openapi.yml
- filename: insumermodel-com-discounts-codes-api-openapi.yml
  format: yaml
  label: insumermodel-com Discounts & Codes API
  slug: insumermodel-com-discounts-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-discounts-codes-api-openapi.yml
- filename: insumermodel-com-discovery-api-openapi.yml
  format: yaml
  label: insumermodel-com Discovery API
  slug: insumermodel-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-discovery-api-openapi.yml
- filename: insumermodel-com-keys-billing-api-openapi.yml
  format: yaml
  label: insumermodel-com Keys & Billing API
  slug: insumermodel-com-keys-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-keys-billing-api-openapi.yml
- filename: insumermodel-com-merchant-setup-api-openapi.yml
  format: yaml
  label: insumermodel-com Merchant Setup API
  slug: insumermodel-com-merchant-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-merchant-setup-api-openapi.yml
- filename: insumermodel-com-platform-api-openapi.yml
  format: yaml
  label: insumermodel-com Platform API
  slug: insumermodel-com-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-platform-api-openapi.yml
- filename: insumermodel-com-point-of-sale-api-openapi.yml
  format: yaml
  label: insumermodel-com Point of Sale API
  slug: insumermodel-com-point-of-sale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-point-of-sale-api-openapi.yml
- filename: insumermodel-com-trust-fact-profiles-api-openapi.yml
  format: yaml
  label: insumermodel-com Trust Fact Profiles API
  slug: insumermodel-com-trust-fact-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-trust-fact-profiles-api-openapi.yml
- filename: insumermodel-com-wallet-auth-api-openapi.yml
  format: yaml
  label: insumermodel-com Wallet Auth API
  slug: insumermodel-com-wallet-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-wallet-auth-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Platform.
    type: individual
  - text: 'Businesses that create a store through the merchant API agree to: Provide accurate business information'
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Reverse-engineering balances
    text: Not reverse-engineer individual wallet balances from standard (boolean) API responses.
  - summary: Illegal activity
    text: Use the Platform to launder money or finance illegal activities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Developers can create a free API key with an email address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: insumermodel-com
provenance_date: '2026-11-09'
provider_name: insumermodel-com
provider_slug: insumermodel-com
slug: insumermodel-com-eligibility
source_date: '2026-11-09'
source_filename: insumermodel-com-eligibility.yml
source_heading: Eligibility
source_page: https://insumermodel.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: insumermodel-com\naid: insumermodel-com\nurl: https://insumermodel.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Platform.\n- type: business\n  text: 'Businesses that create a store through the merchant API agree to: Provide accurate business information'\nrestricted_uses:\n- summary: Reverse-engineering balances\n  text: Not reverse-engineer individual wallet balances from standard (boolean) API responses.\n- summary: Illegal\
  \ activity\n  text: Use the Platform to launder money or finance illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Developers can create a free API key with an email address\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/insumermodel-com/eligibility/insumermodel-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from insumermodel-com's own page on 2026-11-09.
synthetic: false
tags:
- Wallet Auth
- Blockchain
- AI Agents
- Condition-Based Access
- Cryptocurrency
- Developer Tools
---
