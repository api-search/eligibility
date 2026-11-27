---
api_specs:
- filename: fintary-agents-api-openapi.yml
  format: yaml
  label: Fintary Agents API
  slug: fintary-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-agents-api-openapi.yml
- filename: fintary-ams-agents-api-openapi.yml
  format: yaml
  label: Fintary AMS - Agents API
  slug: fintary-ams-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-agents-api-openapi.yml
- filename: fintary-ams-configs-api-openapi.yml
  format: yaml
  label: Fintary AMS - Configs API
  slug: fintary-ams-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-configs-api-openapi.yml
- filename: fintary-ams-customers-api-openapi.yml
  format: yaml
  label: Fintary AMS - Customers API
  slug: fintary-ams-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-customers-api-openapi.yml
- filename: fintary-ams-policies-api-openapi.yml
  format: yaml
  label: Fintary AMS - Policies API
  slug: fintary-ams-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-policies-api-openapi.yml
- filename: fintary-ams-registry-api-openapi.yml
  format: yaml
  label: Fintary AMS - Registry API
  slug: fintary-ams-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-registry-api-openapi.yml
- filename: fintary-ams-tasks-api-openapi.yml
  format: yaml
  label: Fintary AMS - Tasks API
  slug: fintary-ams-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-tasks-api-openapi.yml
- filename: fintary-analytics-api-openapi.yml
  format: yaml
  label: Fintary Analytics API
  slug: fintary-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-analytics-api-openapi.yml
- filename: fintary-commission-reports-api-openapi.yml
  format: yaml
  label: Fintary Commission Reports API
  slug: fintary-commission-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-commission-reports-api-openapi.yml
- filename: fintary-documents-api-openapi.yml
  format: yaml
  label: Fintary Documents API
  slug: fintary-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-documents-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Fintary's Services are intended solely for ... (ii) that are domiciled in the United States
  minimum_age:
    text: whose Authorized Users are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not use or otherwise export or re-export Fintary Materials except as authorized by Applicable Laws.
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
name: Fintary
provenance_date: '2026-11-09'
provider_name: Fintary
provider_slug: fintary
slug: fintary-eligibility
source_date: '2026-11-09'
source_filename: fintary-eligibility.yml
source_heading: Eligibility
source_page: https://www.fintary.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fintary\naid: fintary\nurl: https://www.fintary.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Fintary's Services are intended solely for ... (ii) that are domiciled in the United States\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not use or otherwise export or re-export Fintary Materials except as authorized by Applicable\n    Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: whose Authorized Users are at least eighteen\
  \ (18) years old\n"
source_yaml_url: https://artifacts.apis.io/fintary/eligibility/fintary-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fintary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Insurtech
- Commissions
- Revenue Operations
- Analytics
- Agency Management
- Policy Management
- Payouts
- Reconciliation
- OpenAPI
---
