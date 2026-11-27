---
api_specs:
- filename: bind-policies-api-openapi.yml
  format: yaml
  label: Bind Policies API
  slug: bind-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-policies-api-openapi.yml
- filename: bind-quotes-api-openapi.yml
  format: yaml
  label: Bind Quotes API
  slug: bind-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-quotes-api-openapi.yml
- filename: bind-reports-api-openapi.yml
  format: yaml
  label: Bind Reports API
  slug: bind-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-reports-api-openapi.yml
claim_count: 1
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
  - summary: Personal non-commercial use only
    text: The Terms permit you to use the Website for your personal, non-commercial use only.
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
name: Bind
provenance_date: '2026-11-09'
provider_name: Bind
provider_slug: bind
slug: bind-eligibility
source_date: '2026-11-09'
source_filename: bind-eligibility.yml
source_heading: Eligibility
source_page: https://www.bindhq.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bind\naid: bind\nurl: https://www.bindhq.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: The Terms permit you to use the Website for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bind/eligibility/bind-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Bind's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Platform
- Composable
- Specialty
---
