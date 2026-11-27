---
api_specs:
- filename: decide-fyi-action-execution-api-openapi.yml
  format: yaml
  label: decide-fyi Action Execution API
  slug: decide-fyi-action-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-action-execution-api-openapi.yml
- filename: decide-fyi-anomalies-api-openapi.yml
  format: yaml
  label: decide-fyi Anomalies API
  slug: decide-fyi-anomalies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-anomalies-api-openapi.yml
- filename: decide-fyi-audit-chain-api-openapi.yml
  format: yaml
  label: decide-fyi Audit Chain API
  slug: decide-fyi-audit-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-audit-chain-api-openapi.yml
- filename: decide-fyi-benchmarks-api-openapi.yml
  format: yaml
  label: decide-fyi Benchmarks API
  slug: decide-fyi-benchmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-benchmarks-api-openapi.yml
- filename: decide-fyi-confidence-api-openapi.yml
  format: yaml
  label: decide-fyi Confidence API
  slug: decide-fyi-confidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-confidence-api-openapi.yml
- filename: decide-fyi-counterfactuals-api-openapi.yml
  format: yaml
  label: decide-fyi Counterfactuals API
  slug: decide-fyi-counterfactuals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-counterfactuals-api-openapi.yml
- filename: decide-fyi-crm-sync-api-openapi.yml
  format: yaml
  label: decide-fyi CRM Sync API
  slug: decide-fyi-crm-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-crm-sync-api-openapi.yml
- filename: decide-fyi-decision-packets-api-openapi.yml
  format: yaml
  label: decide-fyi Decision Packets API
  slug: decide-fyi-decision-packets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-decision-packets-api-openapi.yml
- filename: decide-fyi-decision-protocol-api-openapi.yml
  format: yaml
  label: decide-fyi Decision Protocol API
  slug: decide-fyi-decision-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-decision-protocol-api-openapi.yml
- filename: decide-fyi-effectiveness-api-openapi.yml
  format: yaml
  label: decide-fyi Effectiveness API
  slug: decide-fyi-effectiveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-effectiveness-api-openapi.yml
- filename: decide-fyi-outcome-tracking-api-openapi.yml
  format: yaml
  label: decide-fyi Outcome Tracking API
  slug: decide-fyi-outcome-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-outcome-tracking-api-openapi.yml
- filename: decide-fyi-policy-patterns-api-openapi.yml
  format: yaml
  label: decide-fyi Policy Patterns API
  slug: decide-fyi-policy-patterns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-policy-patterns-api-openapi.yml
- filename: decide-fyi-registries-api-openapi.yml
  format: yaml
  label: decide-fyi Registries API
  slug: decide-fyi-registries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-registries-api-openapi.yml
- filename: decide-fyi-verification-api-openapi.yml
  format: yaml
  label: decide-fyi Verification API
  slug: decide-fyi-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-verification-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business customers only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated or unauthorized data
    text: Do not submit unnecessary personal data, regulated data, secrets, credentials, or content you are not authorized to process.
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
name: decide-fyi
provenance_date: '2026-11-09'
provider_name: decide-fyi
provider_slug: decide-fyi
slug: decide-fyi-eligibility
source_date: '2026-11-09'
source_filename: decide-fyi-eligibility.yml
source_heading: Eligibility
source_page: https://www.decide.fyi/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: decide-fyi\naid: decide-fyi\nurl: https://www.decide.fyi/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business customers only.\nrestricted_uses:\n- summary: Regulated or unauthorized data\n  text: Do not submit unnecessary personal data, regulated data, secrets, credentials, or content you are not authorized\n    to process.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/decide-fyi/eligibility/decide-fyi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from decide-fyi's own page on 2026-11-09.
synthetic: false
tags:
- Decision API
- Rule Engine
- Software-as-a-Service
- Automation
- Runtime
---
