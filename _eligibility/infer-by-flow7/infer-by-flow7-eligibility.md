---
api_specs:
- filename: infer-by-flow7-catalog-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Catalog API
  slug: infer-by-flow7-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-catalog-api-openapi.yml
- filename: infer-by-flow7-inference-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Inference API
  slug: infer-by-flow7-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-inference-api-openapi.yml
- filename: infer-by-flow7-status-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Status API
  slug: infer-by-flow7-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-status-api-openapi.yml
- filename: infer-by-flow7-generation-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Generation API
  slug: infer-by-flow7-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-generation-api-openapi.yml
- filename: infer-by-flow7-messages-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Messages API
  slug: infer-by-flow7-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-messages-api-openapi.yml
- filename: infer-by-flow7-usage-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Usage API
  slug: infer-by-flow7-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-usage-api-openapi.yml
- filename: infer-by-flow7-chat-completions-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Chat Completions API
  slug: infer-by-flow7-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-chat-completions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Infer is intended to be available internationally where lawful and technically supported.
  entity_types:
  - text: You must be at least 18 years old, legally capable of entering a contract, and permitted to use the Service under applicable law.
    type: individual
  - text: If you use Infer for an organization, you represent that you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old, legally capable of entering a contract, and permitted to use the Service under applicable law.
    value: '18'
  restricted_uses:
  - summary: Sensitive data submission
    text: Do not submit payment-card authentication data, passwords, private keys, API secrets, protected health information subject to HIPAA, children’s data, biometric templates, government authentication credentials, or other highly sensitive data unless Infer has expressly approved the use and the selected route and agreement are suitable.
  - summary: Sole basis for consequential decisions
    text: You may not use output as the sole basis for a decision that materially affects a person’s rights, safety, health, credit, employment, housing, education, insurance, legal status, or access to essential services where law or the AUP requires qualified human review or prohibits the use.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Infer may request identity, age, business, ownership, tax, sanctions, payment-risk, or authority verification when reasonably needed. A request for verification does not change the Service’s public-access status or subject every account to manual review.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Infer by Flow7
provenance_date: '2026-11-09'
provider_name: Infer by Flow7
provider_slug: infer-by-flow7
slug: infer-by-flow7-eligibility
source_date: '2026-11-09'
source_filename: infer-by-flow7-eligibility.yml
source_heading: Eligibility
source_page: https://infer.flow7.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infer by Flow7\naid: infer-by-flow7\nurl: https://infer.flow7.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Infer is intended to be available internationally where lawful and technically supported.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, legally capable of entering a contract, and permitted to use the Service\n    under applicable law.\n- type: business\n  text: If you use Infer for an organization, you represent that you are authorized to bind it.\nrestricted_uses:\n- summary: Sensitive data submission\n  text: Do not submit payment-card\
  \ authentication data, passwords, private keys, API secrets, protected health information\n    subject to HIPAA, children’s data, biometric templates, government authentication credentials, or other highly\n    sensitive data unless Infer has expressly approved the use and the selected route and agreement are suitable.\n- summary: Sole basis for consequential decisions\n  text: You may not use output as the sole basis for a decision that materially affects a person’s rights, safety,\n    health, credit, employment, housing, education, insurance, legal status, or access to essential services where\n    law or the AUP requires qualified human review or prohibits the use.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Infer may request identity, age, business, ownership, tax, sanctions, payment-risk, or authority verification\n    when reasonably needed. A request for verification does not change the Service’s public-access status or subject\n    every account\
  \ to manual review.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, legally capable of entering a contract, and permitted to use the Service\n    under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/infer-by-flow7/eligibility/infer-by-flow7-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Infer by Flow7's own page on 2026-11-09.
synthetic: false
tags:
- AI/ML inference
- LLM API gateway
- Responses-compatible API
- Coding-agent tooling
- Developer Tools
- Usage-Based Billing
- Prepaid billing
- Agent-Native
- Agent Skills
- Model Routing
---
