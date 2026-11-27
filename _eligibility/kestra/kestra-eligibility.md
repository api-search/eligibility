---
api_specs:
- filename: kestra-executions-api-openapi.yml
  format: yaml
  label: Kestra Executions API
  slug: kestra-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-executions-api-openapi.yml
- filename: kestra-files-api-openapi.yml
  format: yaml
  label: Kestra Files API
  slug: kestra-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-files-api-openapi.yml
- filename: kestra-flows-api-openapi.yml
  format: yaml
  label: Kestra Flows API
  slug: kestra-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-flows-api-openapi.yml
- filename: kestra-namespaces-api-openapi.yml
  format: yaml
  label: Kestra Namespaces API
  slug: kestra-namespaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-namespaces-api-openapi.yml
- filename: kestra-triggers-api-openapi.yml
  format: yaml
  label: Kestra Triggers API
  slug: kestra-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-triggers-api-openapi.yml
- filename: kestra-kv-store-api-openapi.yml
  format: yaml
  label: Kestra KV Store API
  slug: kestra-kv-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kestra/openapi/kestra-kv-store-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity identified in the Order (“You”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted content
    text: 'You shall not distribute, in particular and without this list being exhaustive: infringing Content'
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
name: Kestra
provenance_date: '2026-11-09'
provider_name: Kestra
provider_slug: kestra
slug: kestra-eligibility
source_date: '2026-11-09'
source_filename: kestra-eligibility.yml
source_heading: Eligibility
source_page: https://kestra.io/enterprise-license-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kestra\naid: kestra\nurl: https://kestra.io/enterprise-license-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity identified in the Order (“You”)\nrestricted_uses:\n- summary: Restricted content\n  text: 'You shall not distribute, in particular and without this list being exhaustive: infringing Content'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kestra/eligibility/kestra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kestra's own page on 2026-11-09.
synthetic: false
tags:
- Automation
- Data Pipeline
- Event-Driven
- Orchestration
- Workflows
---
