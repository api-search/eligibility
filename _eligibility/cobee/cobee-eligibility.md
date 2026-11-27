---
api_specs:
- filename: cobee-companies-api-openapi.yml
  format: yaml
  label: Cobee by Pluxee Companies API
  slug: cobee-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cobee/openapi/cobee-companies-api-openapi.yml
- filename: cobee-oauth-api-openapi.yml
  format: yaml
  label: Cobee by Pluxee OAUTH API
  slug: cobee-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cobee/openapi/cobee-oauth-api-openapi.yml
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
  - summary: Contrary to terms, law or public order
    text: The use of information, services and data contrary to the provisions of these conditions, the Law, morality, good customs, or public order
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
name: Cobee by Pluxee
provenance_date: '2026-11-09'
provider_name: Cobee by Pluxee
provider_slug: cobee
slug: cobee-eligibility
source_date: '2026-11-09'
source_filename: cobee-eligibility.yml
source_heading: Eligibility
source_page: https://cobee.io/en/terms-condition/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cobee by Pluxee\naid: cobee\nurl: https://cobee.io/en/terms-condition/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Contrary to terms, law or public order\n  text: The use of information, services and data contrary to the provisions of these conditions, the Law, morality,\n    good customs, or public order\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cobee/eligibility/cobee-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cobee by Pluxee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employee Benefits
- Compensation
- Human Resources
- Payroll
- Fintech
- Spain
- Flexible Benefits
---
