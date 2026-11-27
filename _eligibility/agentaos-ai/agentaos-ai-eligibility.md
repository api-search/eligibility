---
api_specs:
- filename: agentaos-ai-bank-accounts-api-openapi.yml
  format: yaml
  label: AgentaOS Bank Accounts API
  slug: agentaos-ai-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-bank-accounts-api-openapi.yml
- filename: agentaos-ai-businesses-api-openapi.yml
  format: yaml
  label: AgentaOS Businesses API
  slug: agentaos-ai-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-businesses-api-openapi.yml
- filename: agentaos-ai-checkouts-api-openapi.yml
  format: yaml
  label: AgentaOS Checkouts API
  slug: agentaos-ai-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-checkouts-api-openapi.yml
- filename: agentaos-ai-customers-api-openapi.yml
  format: yaml
  label: AgentaOS Customers API
  slug: agentaos-ai-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-customers-api-openapi.yml
- filename: agentaos-ai-discount-codes-api-openapi.yml
  format: yaml
  label: AgentaOS Discount Codes API
  slug: agentaos-ai-discount-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-discount-codes-api-openapi.yml
- filename: agentaos-ai-invoices-api-openapi.yml
  format: yaml
  label: AgentaOS Invoices API
  slug: agentaos-ai-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-invoices-api-openapi.yml
- filename: agentaos-ai-payment-links-api-openapi.yml
  format: yaml
  label: AgentaOS Payment Links API
  slug: agentaos-ai-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-payment-links-api-openapi.yml
- filename: agentaos-ai-subscriptions-api-openapi.yml
  format: yaml
  label: AgentaOS Subscriptions API
  slug: agentaos-ai-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-subscriptions-api-openapi.yml
- filename: agentaos-ai-transactions-api-openapi.yml
  format: yaml
  label: AgentaOS Transactions API
  slug: agentaos-ai-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-transactions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18+, able to contract, and authorised to bind your entity.
    type: individual
  - text: The Service is for business use
    type: business
  minimum_age:
    text: You must be 18+
    value: '18'
  restricted_uses:
  - summary: Custom or per-client work not allowed
    text: custom or per-client-scoped work, ever
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: We and our Payment Partners run KYC/KYB before and during your use, and ongoing due diligence.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentaOS
provenance_date: '2026-11-09'
provider_name: AgentaOS
provider_slug: agentaos-ai
slug: agentaos-ai-eligibility
source_date: '2026-11-09'
source_filename: agentaos-ai-eligibility.yml
source_heading: Eligibility
source_page: https://agentaos.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentaOS\naid: agentaos-ai\nurl: https://agentaos.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18+, able to contract, and authorised to bind your entity.\n- type: business\n  text: The Service is for business use\nrestricted_uses:\n- summary: Custom or per-client work not allowed\n  text: custom or per-client-scoped work, ever\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: We and our Payment Partners run KYC/KYB before and during your use, and ongoing due diligence.\nminimum_age:\n\
  \  value: '18'\n  text: You must be 18+\n"
source_yaml_url: https://artifacts.apis.io/agentaos-ai/eligibility/agentaos-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AgentaOS's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Billing
- Software-as-a-Service
- Freelancers
- Artificial Intelligence
---
