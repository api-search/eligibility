---
api_specs:
- filename: holidays-countries-api-openapi.yml
  format: yaml
  label: Holiday API Countries API
  slug: holidays-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holidays/openapi/holidays-countries-api-openapi.yml
- filename: holidays-holidays-api-openapi.yml
  format: yaml
  label: Holiday API Holidays API
  slug: holidays-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holidays/openapi/holidays-holidays-api-openapi.yml
- filename: holidays-languages-api-openapi.yml
  format: yaml
  label: Holiday API Languages API
  slug: holidays-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holidays/openapi/holidays-languages-api-openapi.yml
- filename: holidays-workdays-api-openapi.yml
  format: yaml
  label: Holiday API Workdays API
  slug: holidays-workdays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holidays/openapi/holidays-workdays-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We develop our Site and Services for the United States and makes no representation that the Site, Services or Content are appropriate or available for use outside the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the Website or its Content: (a) for any unlawful purpose'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, but have no obligation to, monitor and review new accounts before you may sign in and use our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Holiday API
provenance_date: '2026-11-09'
provider_name: Holiday API
provider_slug: holidays
slug: holidays-eligibility
source_date: '2026-11-09'
source_filename: holidays-eligibility.yml
source_heading: Eligibility
source_page: https://holidayapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Holiday API\naid: holidays\nurl: https://holidayapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We develop our Site and Services for the United States and makes no representation that the Site, Services\n    or Content are appropriate or available for use outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the Website or its Content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, but have no obligation to, monitor and\
  \ review new accounts before you may sign in and use our Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/holidays/eligibility/holidays-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Holiday API's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Holidays
- Public Holidays
- Observances
- Reference Data
- Countries
- Language
- Workdays
- Business Days
- Localization
---
