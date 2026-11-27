---
api_specs:
- filename: evidentagents-com-demands-api-openapi.yml
  format: yaml
  label: Evident Demands API
  slug: evidentagents-com-demands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-demands-api-openapi.yml
- filename: evidentagents-com-personal-api-openapi.yml
  format: yaml
  label: Evident Personal API
  slug: evidentagents-com-personal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-personal-api-openapi.yml
- filename: evidentagents-com-quality-api-openapi.yml
  format: yaml
  label: Evident Quality API
  slug: evidentagents-com-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-quality-api-openapi.yml
- filename: evidentagents-com-service-config-api-openapi.yml
  format: yaml
  label: Evident Service Config API
  slug: evidentagents-com-service-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-service-config-api-openapi.yml
- filename: evidentagents-com-service-feedback-api-openapi.yml
  format: yaml
  label: Evident Service Feedback API
  slug: evidentagents-com-service-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-service-feedback-api-openapi.yml
- filename: evidentagents-com-services-api-openapi.yml
  format: yaml
  label: Evident Services API
  slug: evidentagents-com-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-services-api-openapi.yml
- filename: evidentagents-com-task-benchmarks-api-openapi.yml
  format: yaml
  label: Evident Task Benchmarks API
  slug: evidentagents-com-task-benchmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-benchmarks-api-openapi.yml
- filename: evidentagents-com-task-canaries-api-openapi.yml
  format: yaml
  label: Evident Task Canaries API
  slug: evidentagents-com-task-canaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-canaries-api-openapi.yml
- filename: evidentagents-com-task-candidates-api-openapi.yml
  format: yaml
  label: Evident Task Candidates API
  slug: evidentagents-com-task-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-candidates-api-openapi.yml
- filename: evidentagents-com-task-contract-api-openapi.yml
  format: yaml
  label: Evident Task Contract API
  slug: evidentagents-com-task-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-contract-api-openapi.yml
- filename: evidentagents-com-task-execute-api-openapi.yml
  format: yaml
  label: Evident Task Execute API
  slug: evidentagents-com-task-execute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-execute-api-openapi.yml
- filename: evidentagents-com-task-match-api-openapi.yml
  format: yaml
  label: Evident Task Match API
  slug: evidentagents-com-task-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-match-api-openapi.yml
- filename: evidentagents-com-task-plan-api-openapi.yml
  format: yaml
  label: Evident Task Plan API
  slug: evidentagents-com-task-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-plan-api-openapi.yml
- filename: evidentagents-com-task-schema-api-openapi.yml
  format: yaml
  label: Evident Task Schema API
  slug: evidentagents-com-task-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-task-schema-api-openapi.yml
- filename: evidentagents-com-workspace-api-openapi.yml
  format: yaml
  label: Evident Workspace API
  slug: evidentagents-com-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidentagents-com/openapi/evidentagents-com-workspace-api-openapi.yml
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
  - summary: Prohibited review conduct
    text: Do not fabricate transactions, impersonate people or businesses, post personal information or coordinate misleading reviews.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Listing approval requires a separate reviewer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evident
provenance_date: '2026-11-09'
provider_name: Evident
provider_slug: evidentagents-com
slug: evidentagents-com-eligibility
source_date: '2026-11-09'
source_filename: evidentagents-com-eligibility.yml
source_heading: Eligibility
source_page: https://evidentagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evident\naid: evidentagents-com\nurl: https://evidentagents.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited review conduct\n  text: Do not fabricate transactions, impersonate people or businesses, post personal information or coordinate\n    misleading reviews.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Listing approval requires a separate reviewer.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/evidentagents-com/eligibility/evidentagents-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Evident's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Tools
- Marketplace
- Search
---
