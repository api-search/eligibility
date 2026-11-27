---
api_specs:
- filename: coldleads-app-activity-api-openapi.yml
  format: yaml
  label: Cold Leads Activity API
  slug: coldleads-app-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-activity-api-openapi.yml
- filename: coldleads-app-credits-api-openapi.yml
  format: yaml
  label: Cold Leads Credits API
  slug: coldleads-app-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-credits-api-openapi.yml
- filename: coldleads-app-find-api-openapi.yml
  format: yaml
  label: Cold Leads Find API
  slug: coldleads-app-find-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-find-api-openapi.yml
- filename: coldleads-app-follow-ups-api-openapi.yml
  format: yaml
  label: Cold Leads Follow Ups API
  slug: coldleads-app-follow-ups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-follow-ups-api-openapi.yml
- filename: coldleads-app-leads-api-openapi.yml
  format: yaml
  label: Cold Leads Leads API
  slug: coldleads-app-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-leads-api-openapi.yml
- filename: coldleads-app-next-actions-api-openapi.yml
  format: yaml
  label: Cold Leads Next Actions API
  slug: coldleads-app-next-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-next-actions-api-openapi.yml
- filename: coldleads-app-social-api-openapi.yml
  format: yaml
  label: Cold Leads Social API
  slug: coldleads-app-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-social-api-openapi.yml
- filename: coldleads-app-verify-api-openapi.yml
  format: yaml
  label: Cold Leads Verify API
  slug: coldleads-app-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-verify-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: no export or shipping restrictions apply
  entity_types:
  - text: The Service is intended for businesses and entrepreneurs (B2B)
    type: business
  - text: consumers may use it as well and enjoy the statutory consumer rights described below
    type: individual
  minimum_age:
    text: no age confirmation is required
    value: null
  restricted_uses:
  - summary: Adult-restricted products
    text: The Service is not intended for products restricted to adults
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
name: Cold Leads
provenance_date: '2026-11-09'
provider_name: Cold Leads
provider_slug: coldleads-app
slug: coldleads-app-eligibility
source_date: '2026-11-09'
source_filename: coldleads-app-eligibility.yml
source_heading: Eligibility
source_page: https://coldleads.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cold Leads\naid: coldleads-app\nurl: https://coldleads.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: no export or shipping restrictions apply\nentity_types:\n- type: business\n  text: The Service is intended for businesses and entrepreneurs (B2B)\n- type: individual\n  text: consumers may use it as well and enjoy the statutory consumer rights described below\nrestricted_uses:\n- summary: Adult-restricted products\n  text: The Service is not intended for products restricted to adults\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: no age confirmation is required\n"
source_yaml_url: https://artifacts.apis.io/coldleads-app/eligibility/coldleads-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cold Leads's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Software-as-a-Service
- Small Business
- Lead Management
- Cold Leads
---
