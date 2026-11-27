---
api_specs:
- filename: fama-public-endpoints-api-openapi.yml
  format: yaml
  label: Fama Public Endpoints API
  slug: fama-public-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-public-endpoints-api-openapi.yml
- filename: fama-publicapi-api-openapi.yml
  format: yaml
  label: Fama Public API
  slug: fama-publicapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-publicapi-api-openapi.yml
- filename: fama-report-api-openapi.yml
  format: yaml
  label: Fama Report API
  slug: fama-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-report-api-openapi.yml
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
  - summary: FCRA permissible purpose required
    text: Customer shall request Consumer Reports from Company for a permissible purpose for obtaining Consumer Reports as defined by FCRA §604 and applicable state and local law.
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
name: Fama
provenance_date: '2026-11-09'
provider_name: Fama
provider_slug: fama
slug: fama-eligibility
source_date: '2026-11-09'
source_filename: fama-eligibility.yml
source_heading: Eligibility
source_page: https://fama.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fama\naid: fama\nurl: https://fama.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: FCRA permissible purpose required\n  text: Customer shall request Consumer Reports from Company for a permissible purpose for obtaining Consumer Reports\n    as defined by FCRA §604 and applicable state and local law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fama/eligibility/fama-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Fama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employment Screening
- Background Checks
- Human Resources
- Social Media
- Risk Management
- Compliance
- Artificial Intelligence
---
