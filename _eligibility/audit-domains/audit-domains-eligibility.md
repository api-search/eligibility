---
api_specs:
- filename: audit-domains-account-api-openapi.yml
  format: yaml
  label: audit.domains Account API
  slug: audit-domains-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-account-api-openapi.yml
- filename: audit-domains-appraisals-api-openapi.yml
  format: yaml
  label: audit.domains Appraisals API
  slug: audit-domains-appraisals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-appraisals-api-openapi.yml
- filename: audit-domains-bulk-api-openapi.yml
  format: yaml
  label: audit.domains Bulk API
  slug: audit-domains-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-bulk-api-openapi.yml
- filename: audit-domains-machine-api-openapi.yml
  format: yaml
  label: audit.domains Machine API
  slug: audit-domains-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-machine-api-openapi.yml
- filename: audit-domains-sales-api-openapi.yml
  format: yaml
  label: audit.domains Sales API
  slug: audit-domains-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-sales-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to create an account or buy a plan.
    value: '18'
  restricted_uses:
  - summary: Illegal use
    text: Use the Service for any illegal purpose or in violation of any laws
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
name: audit.domains
provenance_date: '2026-11-09'
provider_name: audit.domains
provider_slug: audit-domains
slug: audit-domains-eligibility
source_date: '2026-11-09'
source_filename: audit-domains-eligibility.yml
source_heading: Eligibility
source_page: https://audit.domains/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: audit.domains\naid: audit-domains\nurl: https://audit.domains/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use\n  text: Use the Service for any illegal purpose or in violation of any laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account or buy a plan.\n"
source_yaml_url: https://artifacts.apis.io/audit-domains/eligibility/audit-domains-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from audit.domains's own page on 2026-11-09.
synthetic: false
tags:
- Domain
- Valuation
- Analytics
- Portfolio
---
