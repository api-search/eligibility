---
api_specs:
- filename: sex-offenders-api-sex-offenders-api-openapi.yml
  format: yaml
  label: Sex Offenders API Sex Offenders API
  slug: sex-offenders-api-sex-offenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sex-offenders-api/openapi/sex-offenders-api-sex-offenders-api-openapi.yml
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
  - summary: Sex offender data use must follow law
    text: Any access to, or use of, this data is the responsibility of the service user, and shall be done only in accordance with all applicable laws and ordinances.
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
name: Sex Offenders API
provenance_date: '2026-11-10'
provider_name: Sex Offenders API
provider_slug: sex-offenders-api
slug: sex-offenders-api-eligibility
source_date: '2026-11-10'
source_filename: sex-offenders-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.crimeometer.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sex Offenders API\naid: sex-offenders-api\nurl: https://www.crimeometer.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sex offender data use must follow law\n  text: Any access to, or use of, this data is the responsibility of the service user, and shall be done only in\n    accordance with all applicable laws and ordinances.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sex-offenders-api/eligibility/sex-offenders-api-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sex Offenders API's own page on 2026-11-10.
synthetic: false
tags:
- Sex Offenders
- Public Safety
- Crime
- Background Checks
- Criminal Justice
- Government Data
- Geospatial
- Real Estate
- Risk Management
- People Data
---
