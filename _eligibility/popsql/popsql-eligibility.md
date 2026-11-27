---
api_specs:
- filename: popsql-data-catalog-api-openapi.yml
  format: yaml
  label: PopSQL Data Catalog API
  slug: popsql-data-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popsql/openapi/popsql-data-catalog-api-openapi.yml
- filename: popsql-query-runs-api-openapi.yml
  format: yaml
  label: PopSQL Query Runs API
  slug: popsql-query-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popsql/openapi/popsql-query-runs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering an Account on behalf of an organization under an agreement between us and another organization, that organization may have administrator rights to access your account
    type: business
  minimum_age:
    text: If you are under 13 years old, you may not use the Services.
    value: '13'
  restricted_uses:
  - summary: Databases you control
    text: You may only use the Services to develop, manage, and support Databases that you control or which you have been legally granted access to.
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
name: PopSQL
provenance_date: '2026-11-10'
provider_name: PopSQL
provider_slug: popsql
slug: popsql-eligibility
source_date: '2026-11-10'
source_filename: popsql-eligibility.yml
source_heading: Eligibility
source_page: https://popsql.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PopSQL\naid: popsql\nurl: https://popsql.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering an Account on behalf of an organization under an agreement between us and another\n    organization, that organization may have administrator rights to access your account\nrestricted_uses:\n- summary: Databases you control\n  text: You may only use the Services to develop, manage, and support Databases that you control or which you have\n    been legally granted access to.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years old, you may not use the Services.\n"
source_yaml_url: https://artifacts.apis.io/popsql/eligibility/popsql-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PopSQL's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SQL
- Collaboration
- Data Analytics
- Cloud
---
