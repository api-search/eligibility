---
api_specs:
- filename: agentcard-authentication-api-openapi.yml
  format: yaml
  label: Agentcard Authentication API
  slug: agentcard-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-authentication-api-openapi.yml
- filename: agentcard-connect-api-openapi.yml
  format: yaml
  label: Agentcard Connect API
  slug: agentcard-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-connect-api-openapi.yml
- filename: agentcard-identity-verification-api-openapi.yml
  format: yaml
  label: Agentcard Identity verification API
  slug: agentcard-identity-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-identity-verification-api-openapi.yml
- filename: agentcard-member-cards-api-openapi.yml
  format: yaml
  label: Agentcard Member cards API
  slug: agentcard-member-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-member-cards-api-openapi.yml
- filename: agentcard-purchase-api-openapi.yml
  format: yaml
  label: Agentcard Purchase API
  slug: agentcard-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-purchase-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Wallet funding is currently available in the United States only.
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract.
    type: individual
  - text: organization subscriptions are processed through Stripe.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Fraud, money laundering, terrorist financing
    text: Facilitate fraud, money laundering, or terrorist financing
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account and provide accurate information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agentcard
provenance_date: '2026-11-09'
provider_name: Agentcard
provider_slug: agentcard
slug: agentcard-eligibility
source_date: '2026-11-09'
source_filename: agentcard-eligibility.yml
source_heading: Eligibility
source_page: https://agentcard.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentcard\naid: agentcard\nurl: https://agentcard.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Wallet funding is currently available in the United States only.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract.\n- type: business\n  text: organization subscriptions are processed through Stripe.\nrestricted_uses:\n- summary: Fraud, money laundering, terrorist financing\n  text: Facilitate fraud, money laundering, or terrorist financing\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You must create an account and provide accurate information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/agentcard/eligibility/agentcard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Agentcard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Virtual Cards
- Card Issuing
- AI Agents
- Agentic Commerce
- MCP
- Fintech
- Wallets
- Visa
- A2A
---
