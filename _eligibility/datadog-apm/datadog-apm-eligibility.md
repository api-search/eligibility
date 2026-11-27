---
api_specs:
- filename: datadog-apm-spans-api-openapi.yml
  format: yaml
  label: Datadog APM Spans API
  slug: datadog-apm-spans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-spans-api-openapi.yml
- filename: datadog-apm-spans-metrics-api-openapi.yml
  format: yaml
  label: Datadog APM Spans Metrics API
  slug: datadog-apm-spans-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-spans-metrics-api-openapi.yml
- filename: datadog-apm-apm-api-openapi.yml
  format: yaml
  label: Datadog APM API
  slug: datadog-apm-apm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-apm-api-openapi.yml
- filename: datadog-apm-apm-retention-filters-api-openapi.yml
  format: yaml
  label: Datadog APM Retention Filters API
  slug: datadog-apm-apm-retention-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-apm-retention-filters-api-openapi.yml
- filename: datadog-apm-service-definition-api-openapi.yml
  format: yaml
  label: Datadog APM Service Definition API
  slug: datadog-apm-service-definition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-service-definition-api-openapi.yml
- filename: datadog-apm-service-level-objective-corrections-api-openapi.yml
  format: yaml
  label: Datadog APM Service Level Objective Corrections API
  slug: datadog-apm-service-level-objective-corrections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-service-level-objective-corrections-api-openapi.yml
- filename: datadog-apm-service-level-objectives-api-openapi.yml
  format: yaml
  label: Datadog APM Service Level Objectives API
  slug: datadog-apm-service-level-objectives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datadog-apm/openapi/datadog-apm-service-level-objectives-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Datadog makes no representation that the products and services referenced herein are appropriate, or available, worldwide.
  entity_types:
  - text: You represent to Datadog that you are lawfully able to enter into contracts (e.g., you are not a minor).
    type: individual
  - text: If you are entering into these Terms for an entity, such as the company you work for, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You represent to Datadog that you are lawfully able to enter into contracts (e.g., you are not a minor).
    value: null
  restricted_uses:
  - summary: Sanctions and export restrictions
    text: You represent that you are not a Sanctions Target or prohibited from receiving Datadog software, content or services pursuant to these Terms under Applicable Laws, including Export Laws.
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
name: Datadog APM
provenance_date: '2026-11-09'
provider_name: Datadog APM
provider_slug: datadog-apm
slug: datadog-apm-eligibility
source_date: '2026-11-09'
source_filename: datadog-apm-eligibility.yml
source_heading: Eligibility
source_page: https://www.datadoghq.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datadog APM\naid: datadog-apm\nurl: https://www.datadoghq.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Datadog makes no representation that the products and services referenced herein are appropriate, or available,\n    worldwide.\nentity_types:\n- type: individual\n  text: You represent to Datadog that you are lawfully able to enter into contracts (e.g., you are not a minor).\n- type: business\n  text: If you are entering into these Terms for an entity, such as the company you work for, you represent that\n    you have authority to bind that entity\nrestricted_uses:\n\
  - summary: Sanctions and export restrictions\n  text: You represent that you are not a Sanctions Target or prohibited from receiving Datadog software, content\n    or services pursuant to these Terms under Applicable Laws, including Export Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent to Datadog that you are lawfully able to enter into contracts (e.g., you are not a minor).\n"
source_yaml_url: https://artifacts.apis.io/datadog-apm/eligibility/datadog-apm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Datadog APM's own page on 2026-11-09.
synthetic: false
tags:
- APM
- Distributed Tracing
- Microservices
- Observability
- Performance Monitoring
- Spans
- SLO
- Service Catalog
- OpenTelemetry
- MCP
---
