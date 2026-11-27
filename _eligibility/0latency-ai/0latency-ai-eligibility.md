---
api_specs:
- filename: 0latency-ai-admin-api-openapi.yml
  format: yaml
  label: 0latency-ai Admin API
  slug: 0latency-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-admin-api-openapi.yml
- filename: 0latency-ai-api-keys-api-openapi.yml
  format: yaml
  label: 0latency-ai Api Keys API
  slug: 0latency-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-api-keys-api-openapi.yml
- filename: 0latency-ai-auth-api-openapi.yml
  format: yaml
  label: 0latency-ai Auth API
  slug: 0latency-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-auth-api-openapi.yml
- filename: 0latency-ai-billing-api-openapi.yml
  format: yaml
  label: 0latency-ai Billing API
  slug: 0latency-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-billing-api-openapi.yml
- filename: 0latency-ai-criteria-api-openapi.yml
  format: yaml
  label: 0latency-ai Criteria API
  slug: 0latency-ai-criteria-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-criteria-api-openapi.yml
- filename: 0latency-ai-dashboard-api-openapi.yml
  format: yaml
  label: 0latency-ai Dashboard API
  slug: 0latency-ai-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-dashboard-api-openapi.yml
- filename: 0latency-ai-extract-api-openapi.yml
  format: yaml
  label: 0latency-ai Extract API
  slug: 0latency-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-extract-api-openapi.yml
- filename: 0latency-ai-graph-api-openapi.yml
  format: yaml
  label: 0latency-ai Graph API
  slug: 0latency-ai-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-graph-api-openapi.yml
- filename: 0latency-ai-health-api-openapi.yml
  format: yaml
  label: 0latency-ai Health API
  slug: 0latency-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-health-api-openapi.yml
- filename: 0latency-ai-memories-api-openapi.yml
  format: yaml
  label: 0latency-ai Memories API
  slug: 0latency-ai-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-memories-api-openapi.yml
- filename: 0latency-ai-org-api-openapi.yml
  format: yaml
  label: 0latency-ai Org API
  slug: 0latency-ai-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-org-api-openapi.yml
- filename: 0latency-ai-recall-api-openapi.yml
  format: yaml
  label: 0latency-ai Recall API
  slug: 0latency-ai-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-recall-api-openapi.yml
- filename: 0latency-ai-schemas-api-openapi.yml
  format: yaml
  label: 0latency-ai Schemas API
  slug: 0latency-ai-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-schemas-api-openapi.yml
- filename: 0latency-ai-tenant-info-api-openapi.yml
  format: yaml
  label: 0latency-ai Tenant Info API
  slug: 0latency-ai-tenant-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-tenant-info-api-openapi.yml
- filename: 0latency-ai-usage-api-openapi.yml
  format: yaml
  label: 0latency-ai Usage API
  slug: 0latency-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-usage-api-openapi.yml
- filename: 0latency-ai-webhooks-api-openapi.yml
  format: yaml
  label: 0latency-ai Webhooks API
  slug: 0latency-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Storing third-party PII without consent
    text: Use the Service to store personally identifiable information (PII) of third parties without their consent
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 0latency-ai
provenance_date: '2026-11-09'
provider_name: 0latency-ai
provider_slug: 0latency-ai
slug: 0latency-ai-eligibility
source_date: '2026-11-09'
source_filename: 0latency-ai-eligibility.yml
source_heading: Eligibility
source_page: https://0latency.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 0latency-ai\naid: 0latency-ai\nurl: https://0latency.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Storing third-party PII without consent\n  text: Use the Service to store personally identifiable information (PII) of third parties without their consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account to use the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/0latency-ai/eligibility/0latency-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from 0latency-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Agents
- Platform
---
