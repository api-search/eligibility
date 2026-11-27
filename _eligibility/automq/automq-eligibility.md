---
api_specs:
- filename: automq-ai-info-api-openapi.yml
  format: yaml
  label: AutoMQ Ai Info API
  slug: automq-ai-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automq/openapi/automq-ai-info-api-openapi.yml
- filename: automq-llms-full-txt-api-openapi.yml
  format: yaml
  label: AutoMQ Llms Full.txt API
  slug: automq-llms-full-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automq/openapi/automq-llms-full-txt-api-openapi.yml
- filename: automq-llms-txt-api-openapi.yml
  format: yaml
  label: AutoMQ Llms.txt API
  slug: automq-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automq/openapi/automq-llms-txt-api-openapi.yml
- filename: automq-robots-txt-api-openapi.yml
  format: yaml
  label: AutoMQ Robots.txt API
  slug: automq-robots-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automq/openapi/automq-robots-txt-api-openapi.yml
- filename: automq-well-known-api-openapi.yml
  format: yaml
  label: AutoMQ .well Known API
  slug: automq-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automq/openapi/automq-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using any AutoMQ offerings as an employee, contractor, or agent of a corporation, partnership or similar entity, then you must be authorized to sign for and bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited Data
    text: use the Service with Prohibited Data or for High Risk Activities
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
name: AutoMQ
provenance_date: '2026-11-09'
provider_name: AutoMQ
provider_slug: automq
slug: automq-eligibility
source_date: '2026-11-09'
source_filename: automq-eligibility.yml
source_heading: Eligibility
source_page: https://www.automq.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoMQ\naid: automq\nurl: https://www.automq.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using any AutoMQ offerings as an employee, contractor, or agent of a corporation, partnership\n    or similar entity, then you must be authorized to sign for and bind such entity\nrestricted_uses:\n- summary: Prohibited Data\n  text: use the Service with Prohibited Data or for High Risk Activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/automq/eligibility/automq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AutoMQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Kafka
- Streaming
- Event Streaming
- Object Storage
- Open Source
- Cloud
---
