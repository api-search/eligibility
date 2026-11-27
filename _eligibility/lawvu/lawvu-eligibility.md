---
api_specs:
- filename: lawvu-contracts-api-openapi.yml
  format: yaml
  label: LawVu Contracts API
  slug: lawvu-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-contracts-api-openapi.yml
- filename: lawvu-fields-api-openapi.yml
  format: yaml
  label: LawVu Fields API
  slug: lawvu-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-fields-api-openapi.yml
- filename: lawvu-files-api-openapi.yml
  format: yaml
  label: LawVu Files API
  slug: lawvu-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-files-api-openapi.yml
- filename: lawvu-invoices-api-openapi.yml
  format: yaml
  label: LawVu Invoices API
  slug: lawvu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-invoices-api-openapi.yml
- filename: lawvu-matters-api-openapi.yml
  format: yaml
  label: LawVu Matters API
  slug: lawvu-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-matters-api-openapi.yml
- filename: lawvu-teams-api-openapi.yml
  format: yaml
  label: LawVu Teams API
  slug: lawvu-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-teams-api-openapi.yml
- filename: lawvu-users-api-openapi.yml
  format: yaml
  label: LawVu Users API
  slug: lawvu-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you have the authority to act on behalf of any entity for whom you are accessing the Website.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: You must not access our Website and use our services in violation of any export laws and regulations that apply to you.
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
name: LawVu
provenance_date: '2026-11-09'
provider_name: LawVu
provider_slug: lawvu
slug: lawvu-eligibility
source_date: '2026-11-09'
source_filename: lawvu-eligibility.yml
source_heading: Eligibility
source_page: https://lawvu.com/website-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawVu\naid: lawvu\nurl: https://lawvu.com/website-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You confirm that you have the authority to act on behalf of any entity for whom you are accessing the Website.\nrestricted_uses:\n- summary: Export law compliance\n  text: You must not access our Website and use our services in violation of any export laws and regulations that\n    apply to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lawvu/eligibility/lawvu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from LawVu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Legal Operations
- Contract Lifecycle Management
- Matter Management
- Document Management
- Spend Management
- Software-as-a-Service
- Workflows
---
