---
api_specs:
- filename: hacktron-rest-api-cost-estimations-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Cost Estimations API
  slug: hacktron-rest-api-cost-estimations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-cost-estimations-api-openapi.yml
- filename: hacktron-rest-api-findings-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Findings API
  slug: hacktron-rest-api-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-findings-api-openapi.yml
- filename: hacktron-rest-api-hfw-api-openapi.yml
  format: yaml
  label: Hacktron REST API - HFW API
  slug: hacktron-rest-api-hfw-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-hfw-api-openapi.yml
- filename: hacktron-rest-api-repos-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Repos API
  slug: hacktron-rest-api-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-repos-api-openapi.yml
- filename: hacktron-rest-api-scans-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Scans API
  slug: hacktron-rest-api-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-scans-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any company, organization, or other entity on whose behalf you access or use the Hacktron Website
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in violation of law
    text: use the Hacktron Website in violation of applicable law, regulation, contractual duty, or third-party right
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
name: Hacktron
provenance_date: '2026-11-09'
provider_name: Hacktron
provider_slug: hacktron
slug: hacktron-eligibility
source_date: '2026-11-09'
source_filename: hacktron-eligibility.yml
source_heading: Eligibility
source_page: https://www.hacktron.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hacktron\naid: hacktron\nurl: https://www.hacktron.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: any company, organization, or other entity on whose behalf you access or use the Hacktron Website\nrestricted_uses:\n- summary: Use in violation of law\n  text: use the Hacktron Website in violation of applicable law, regulation, contractual duty, or third-party right\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hacktron/eligibility/hacktron-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Hacktron's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Integration
- IoT
- Enterprise
---
