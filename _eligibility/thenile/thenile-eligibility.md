---
api_specs:
- filename: thenile-auth-api-openapi.yml
  format: yaml
  label: Nile Auth API
  slug: thenile-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-auth-api-openapi.yml
- filename: thenile-authentication-api-openapi.yml
  format: yaml
  label: Nile Authentication API
  slug: thenile-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-authentication-api-openapi.yml
- filename: thenile-compute-api-openapi.yml
  format: yaml
  label: Nile Compute API
  slug: thenile-compute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-compute-api-openapi.yml
- filename: thenile-credentials-api-openapi.yml
  format: yaml
  label: Nile Credentials API
  slug: thenile-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-credentials-api-openapi.yml
- filename: thenile-databases-api-openapi.yml
  format: yaml
  label: Nile Databases API
  slug: thenile-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-databases-api-openapi.yml
- filename: thenile-developers-api-openapi.yml
  format: yaml
  label: Nile Developers API
  slug: thenile-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-developers-api-openapi.yml
- filename: thenile-internal-api-openapi.yml
  format: yaml
  label: Nile Internal API
  slug: thenile-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-internal-api-openapi.yml
- filename: thenile-tenants-api-openapi.yml
  format: yaml
  label: Nile Tenants API
  slug: thenile-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-tenants-api-openapi.yml
- filename: thenile-users-api-openapi.yml
  format: yaml
  label: Nile Users API
  slug: thenile-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-users-api-openapi.yml
- filename: thenile-workspaces-api-openapi.yml
  format: yaml
  label: Nile Workspaces API
  slug: thenile-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thenile/openapi/thenile-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
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
name: Nile
provenance_date: '2026-11-10'
provider_name: Nile
provider_slug: thenile
slug: thenile-eligibility
source_date: '2026-11-10'
source_filename: thenile-eligibility.yml
source_heading: Eligibility
source_page: https://www.thenile.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nile\naid: thenile\nurl: https://www.thenile.dev/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Site or accept the Terms if you\
  \ are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/thenile/eligibility/thenile-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nile's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Database
- PostgreSQL
- Serverless
- Multi-Tenant
- Authentication
- B2B SaaS
---
