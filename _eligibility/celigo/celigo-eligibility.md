---
api_specs:
- filename: celigo-webhook-listeners-asyncapi.yml
  format: yaml
  label: Celigo integrator.io Webhook Listeners
  slug: celigo-webhook-listeners
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/celigo/asyncapi/celigo-webhook-listeners-asyncapi.yml
- filename: celigo-connections-api-openapi.yml
  format: yaml
  label: Celigo Connections API
  slug: celigo-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-connections-api-openapi.yml
- filename: celigo-exports-api-openapi.yml
  format: yaml
  label: Celigo Exports API
  slug: celigo-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-exports-api-openapi.yml
- filename: celigo-flows-api-openapi.yml
  format: yaml
  label: Celigo Flows API
  slug: celigo-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-flows-api-openapi.yml
- filename: celigo-iclients-api-openapi.yml
  format: yaml
  label: Celigo iClients API
  slug: celigo-iclients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-iclients-api-openapi.yml
- filename: celigo-imports-api-openapi.yml
  format: yaml
  label: Celigo Imports API
  slug: celigo-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-imports-api-openapi.yml
- filename: celigo-integrations-api-openapi.yml
  format: yaml
  label: Celigo Integrations API
  slug: celigo-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-integrations-api-openapi.yml
- filename: celigo-jobs-api-openapi.yml
  format: yaml
  label: Celigo Jobs API
  slug: celigo-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-jobs-api-openapi.yml
- filename: celigo-licenses-api-openapi.yml
  format: yaml
  label: Celigo Licenses API
  slug: celigo-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-licenses-api-openapi.yml
- filename: celigo-state-api-openapi.yml
  format: yaml
  label: Celigo State API
  slug: celigo-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celigo/openapi/celigo-state-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using Products on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: PHI requires a business associate agreement
    text: to ensure that it has entered into a business associate agreement with Celigo, as required by The Health Insurance Portability and Accountability Act of 1996, before submitting any patient, medical or other protected health information
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
name: Celigo
provenance_date: '2026-11-09'
provider_name: Celigo
provider_slug: celigo
slug: celigo-eligibility
source_date: '2026-11-09'
source_filename: celigo-eligibility.yml
source_heading: Eligibility
source_page: https://www.celigo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celigo\naid: celigo\nurl: https://www.celigo.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using Products on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\nrestricted_uses:\n- summary: PHI requires a business associate agreement\n  text: to ensure that it has entered into a business associate agreement with Celigo, as required by The Health\n    Insurance Portability and Accountability Act of 1996, before submitting\
  \ any patient, medical or other protected\n    health information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/celigo/eligibility/celigo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Celigo's own page on 2026-11-09.
synthetic: false
tags:
- API Management
- Automation
- Data Integration
- Integration
- iPaaS
- Workflows
---
