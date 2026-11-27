---
api_specs:
- filename: weld-connection-bridge-api-openapi.yml
  format: yaml
  label: Weld Connection Bridge API
  slug: weld-connection-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-connection-bridge-api-openapi.yml
- filename: weld-connections-api-openapi.yml
  format: yaml
  label: Weld Connections API
  slug: weld-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-connections-api-openapi.yml
- filename: weld-custom-reports-api-openapi.yml
  format: yaml
  label: Weld Custom Reports API
  slug: weld-custom-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-custom-reports-api-openapi.yml
- filename: weld-elt-stream-runs-api-openapi.yml
  format: yaml
  label: Weld ELT Stream Runs API
  slug: weld-elt-stream-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-stream-runs-api-openapi.yml
- filename: weld-elt-streams-api-openapi.yml
  format: yaml
  label: Weld ELT Streams API
  slug: weld-elt-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-streams-api-openapi.yml
- filename: weld-elt-syncs-api-openapi.yml
  format: yaml
  label: Weld ELT Syncs API
  slug: weld-elt-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-syncs-api-openapi.yml
- filename: weld-integrations-api-openapi.yml
  format: yaml
  label: Weld Integrations API
  slug: weld-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-integrations-api-openapi.yml
- filename: weld-orchestration-runs-api-openapi.yml
  format: yaml
  label: Weld Orchestration Runs API
  slug: weld-orchestration-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-orchestration-runs-api-openapi.yml
- filename: weld-orchestrations-api-openapi.yml
  format: yaml
  label: Weld Orchestrations API
  slug: weld-orchestrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-orchestrations-api-openapi.yml
- filename: weld-reverse-etl-failed-records-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Failed Records API
  slug: weld-reverse-etl-failed-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-failed-records-api-openapi.yml
- filename: weld-reverse-etl-sync-runs-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Sync Runs API
  slug: weld-reverse-etl-sync-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-sync-runs-api-openapi.yml
- filename: weld-reverse-etl-syncs-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Syncs API
  slug: weld-reverse-etl-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-syncs-api-openapi.yml
- filename: weld-transforms-api-openapi.yml
  format: yaml
  label: Weld Transforms API
  slug: weld-transforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-transforms-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are provided to businesses only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No HIPAA protected health information without agreement
    text: Unless agreed with Us in writing, You may not use the Services to process protected health information under the US Health Insurance Portability and Accountability Act (HIPAA)
  - summary: No PCI DSS payment card data without agreement
    text: or payment card data covered by the Payment Card Industry Data Security Standard (PCI DSS).
  - summary: Export control and sanctions compliance
    text: You confirm that You are not, and are not owned or controlled by, a person subject to such sanctions, and that You will not use the Services, or give access to them, in breach of those laws.
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
name: Weld
provenance_date: '2026-11-10'
provider_name: Weld
provider_slug: weld
slug: weld-eligibility
source_date: '2026-11-10'
source_filename: weld-eligibility.yml
source_heading: Eligibility
source_page: https://weld.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Weld\naid: weld\nurl: https://weld.app/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are provided to businesses only.\nrestricted_uses:\n- summary: No HIPAA protected health information without agreement\n  text: Unless agreed with Us in writing, You may not use the Services to process protected health information under\n    the US Health Insurance Portability and Accountability Act (HIPAA)\n- summary: No PCI DSS payment card data without agreement\n  text: or payment card data covered by the Payment Card\
  \ Industry Data Security Standard (PCI DSS).\n- summary: Export control and sanctions compliance\n  text: You confirm that You are not, and are not owned or controlled by, a person subject to such sanctions, and\n    that You will not use the Services, or give access to them, in breach of those laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weld/eligibility/weld-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Weld's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- ETL
- ELT
- Reverse ETL
- Data Pipeline
- Data Integration
- Change Data Capture
- Transformation
- Analytics
- MCP
- AI Agents
---
