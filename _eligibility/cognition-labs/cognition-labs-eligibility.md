---
api_specs:
- filename: cognition-labs-attachments-api-openapi.yml
  format: yaml
  label: Cognition Labs Attachments API
  slug: cognition-labs-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-attachments-api-openapi.yml
- filename: cognition-labs-consumption-api-openapi.yml
  format: yaml
  label: Cognition Labs Consumption API
  slug: cognition-labs-consumption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-consumption-api-openapi.yml
- filename: cognition-labs-enterprise-v3-api-openapi.yml
  format: yaml
  label: Cognition Labs Enterprise (v3) API
  slug: cognition-labs-enterprise-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-enterprise-v3-api-openapi.yml
- filename: cognition-labs-knowledge-api-openapi.yml
  format: yaml
  label: Cognition Labs Knowledge API
  slug: cognition-labs-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-knowledge-api-openapi.yml
- filename: cognition-labs-messages-api-openapi.yml
  format: yaml
  label: Cognition Labs Messages API
  slug: cognition-labs-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-messages-api-openapi.yml
- filename: cognition-labs-organizations-v3-api-openapi.yml
  format: yaml
  label: Cognition Labs Organizations (v3) API
  slug: cognition-labs-organizations-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-organizations-v3-api-openapi.yml
- filename: cognition-labs-playbooks-api-openapi.yml
  format: yaml
  label: Cognition Labs Playbooks API
  slug: cognition-labs-playbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-playbooks-api-openapi.yml
- filename: cognition-labs-secrets-api-openapi.yml
  format: yaml
  label: Cognition Labs Secrets API
  slug: cognition-labs-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-secrets-api-openapi.yml
- filename: cognition-labs-sessions-api-openapi.yml
  format: yaml
  label: Cognition Labs Sessions API
  slug: cognition-labs-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-sessions-api-openapi.yml
- filename: cognition-labs-enterprise-api-openapi.yml
  format: yaml
  label: Cognition Labs Enterprise API
  slug: cognition-labs-enterprise-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-enterprise-api-openapi.yml
- filename: cognition-labs-audit-logs-api-openapi.yml
  format: yaml
  label: Cognition Labs Audit Logs API
  slug: cognition-labs-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognition-labs/openapi/cognition-labs-audit-logs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals or entities who register for and use our Services by signing up directly through our website
    type: individual
  - text: your internal business purposes only
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical or sensitive personal data
    text: You agree not to process any medical information or sensitive personal data such as social security numbers, birth dates, passport information, bank account, and credit card numbers in using the Services.
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
name: Cognition Labs
provenance_date: '2026-11-09'
provider_name: Cognition Labs
provider_slug: cognition-labs
slug: cognition-labs-eligibility
source_date: '2026-11-09'
source_filename: cognition-labs-eligibility.yml
source_heading: Eligibility
source_page: https://old.cognition.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cognition Labs\naid: cognition-labs\nurl: https://old.cognition.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individuals or entities who register for and use our Services by signing up directly through our website\n- type: business\n  text: your internal business purposes only\nrestricted_uses:\n- summary: No medical or sensitive personal data\n  text: You agree not to process any medical information or sensitive personal data such as social security numbers,\n    birth dates, passport information, bank account,\
  \ and credit card numbers in using the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cognition-labs/eligibility/cognition-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cognition Labs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- AI Agents
- Autonomous Coding
- Software Engineering
- LLM
- Devin
---
