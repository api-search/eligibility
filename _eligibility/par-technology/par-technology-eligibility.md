---
api_specs:
- filename: par-technology-auth-api-openapi.yml
  format: yaml
  label: PAR Technology Auth API
  slug: par-technology-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-auth-api-openapi.yml
- filename: par-technology-discounts-api-openapi.yml
  format: yaml
  label: PAR Technology Discounts API
  slug: par-technology-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-discounts-api-openapi.yml
- filename: par-technology-pos-api-openapi.yml
  format: yaml
  label: PAR Technology Pos API
  slug: par-technology-pos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-pos-api-openapi.yml
- filename: par-technology-redemptions-api-openapi.yml
  format: yaml
  label: PAR Technology Redemptions API
  slug: par-technology-redemptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-redemptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Users under 18 prohibited
    text: use the Site if you are under the age of eighteen (18) years old
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
name: PAR Technology
provenance_date: '2026-11-10'
provider_name: PAR Technology
provider_slug: par-technology
slug: par-technology-eligibility
source_date: '2026-11-10'
source_filename: par-technology-eligibility.yml
source_heading: Eligibility
source_page: https://partech.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PAR Technology\naid: par-technology\nurl: https://partech.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 18 prohibited\n  text: use the Site if you are under the age of eighteen (18) years old\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/par-technology/eligibility/par-technology-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from PAR Technology's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Point-of-Sale
- Loyalty
- Retail
---
