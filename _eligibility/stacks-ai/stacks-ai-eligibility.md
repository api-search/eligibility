---
api_specs:
- filename: stacks-ai-analytics-api-openapi.yml
  format: yaml
  label: Stacks Ai Analytics API
  slug: stacks-ai-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stacks-ai/openapi/stacks-ai-analytics-api-openapi.yml
- filename: stacks-ai-knowledge-base-resources-api-openapi.yml
  format: yaml
  label: Stacks Ai Knowledge Base Resources API
  slug: stacks-ai-knowledge-base-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stacks-ai/openapi/stacks-ai-knowledge-base-resources-api-openapi.yml
- filename: stacks-ai-knowledge-base-sync-api-openapi.yml
  format: yaml
  label: Stacks Ai Knowledge Base Sync API
  slug: stacks-ai-knowledge-base-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stacks-ai/openapi/stacks-ai-knowledge-base-sync-api-openapi.yml
- filename: stacks-ai-knowledge-bases-api-openapi.yml
  format: yaml
  label: Stacks Ai Knowledge Bases API
  slug: stacks-ai-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stacks-ai/openapi/stacks-ai-knowledge-bases-api-openapi.yml
- filename: stacks-ai-run-flow-api-openapi.yml
  format: yaml
  label: Stacks Ai Run Flow API
  slug: stacks-ai-run-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stacks-ai/openapi/stacks-ai-run-flow-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You will need to register with Stack AI to become a Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive regulated data
    text: 'you shall not upload or provide to Stack AI any sensitive data including, without limitation: (1) protected health information regulated under HIPAA or HITECH; (2) cardholder data as defined under PCI DSS; or (3) nonpublic personal information'
  - summary: No high risk activities
    text: The Product and Services are not designed or intended for use or resale in hazardous environments requiring fail-safe performance, such as in the operation of nuclear facilities, air traffic control, or direct life support machines
  - summary: Export restrictions
    text: You shall not transfer, export or re-export, directly or indirectly, the Product or Services to any Prohibited Entity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stacks Ai
provenance_date: '2026-11-10'
provider_name: Stacks Ai
provider_slug: stacks-ai
slug: stacks-ai-eligibility
source_date: '2026-11-10'
source_filename: stacks-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.stackai.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stacks Ai\naid: stacks-ai\nurl: https://www.stackai.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You will need to register with Stack AI to become a Customer.\nrestricted_uses:\n- summary: No sensitive regulated data\n  text: 'you shall not upload or provide to Stack AI any sensitive data including, without limitation: (1) protected\n    health information regulated under HIPAA or HITECH; (2) cardholder data as defined under PCI DSS; or (3) nonpublic\n    personal information'\n- summary: No high risk activities\n\
  \  text: The Product and Services are not designed or intended for use or resale in hazardous environments requiring\n    fail-safe performance, such as in the operation of nuclear facilities, air traffic control, or direct life support\n    machines\n- summary: Export restrictions\n  text: You shall not transfer, export or re-export, directly or indirectly, the Product or Services to any Prohibited\n    Entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stacks-ai/eligibility/stacks-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Stacks Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- LLM
- No-Code
- Automation
- Workflows
- RAG
- Knowledge Base
- Enterprise
---
