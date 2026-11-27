---
api_specs:
- filename: recal-organization-api-openapi.yml
  format: yaml
  label: Recal Organization API
  slug: recal-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organization-api-openapi.yml
- filename: recal-organization-scheduling-api-openapi.yml
  format: yaml
  label: Recal Organization Scheduling API
  slug: recal-organization-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organization-scheduling-api-openapi.yml
- filename: recal-organizations-calendar-api-openapi.yml
  format: yaml
  label: Recal Organizations Calendar API
  slug: recal-organizations-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organizations-calendar-api-openapi.yml
- filename: recal-user-calendar-api-openapi.yml
  format: yaml
  label: Recal User Calendar API
  slug: recal-user-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-calendar-api-openapi.yml
- filename: recal-user-oauth-api-openapi.yml
  format: yaml
  label: Recal User OAuth API
  slug: recal-user-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-oauth-api-openapi.yml
- filename: recal-user-scheduling-api-openapi.yml
  format: yaml
  label: Recal User Scheduling API
  slug: recal-user-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-scheduling-api-openapi.yml
- filename: recal-users-api-openapi.yml
  format: yaml
  label: Recal Users API
  slug: recal-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-users-api-openapi.yml
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
  - summary: Unlawful or infringing content
    text: It is prohibited to upload content that infringes third-party rights or violates criminal or youth-protection laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Use of the platform requires an account via the Clerk authentication service. Registration data must be complete and correct.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Recal
provenance_date: '2026-11-10'
provider_name: Recal
provider_slug: recal
slug: recal-eligibility
source_date: '2026-11-10'
source_filename: recal-eligibility.yml
source_heading: Eligibility
source_page: https://recal.dev/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recal\naid: recal\nurl: https://recal.dev/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: It is prohibited to upload content that infringes third-party rights or violates criminal or youth-protection\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Use of the platform requires an account via the Clerk authentication service. Registration data must be\n    complete and correct.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recal/eligibility/recal-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Recal's own page on 2026-11-10.
synthetic: false
tags:
- Calendar API
- Scheduling
- SDK
- Multi-Tenant
- Recruiting
- Marketplace
- AI Agents
---
