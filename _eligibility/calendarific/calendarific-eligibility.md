---
api_specs:
- filename: calendarific-countries-api-openapi.yml
  format: yaml
  label: Calendarific Countries API
  slug: calendarific-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-countries-api-openapi.yml
- filename: calendarific-holidays-api-openapi.yml
  format: yaml
  label: Calendarific Holidays API
  slug: calendarific-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-holidays-api-openapi.yml
- filename: calendarific-languages-api-openapi.yml
  format: yaml
  label: Calendarific Languages API
  slug: calendarific-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-languages-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to this Agreement not as an individual but on behalf of your company, then a reference to “you” or “Customer” in this Agreement is a reference to the company
    type: business
  - text: If you are agreeing to this Agreement not as an individual but on behalf of your company
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Use the Product or Services for any unlawful purpose or in violation of any applicable laws, regulations, or third-party rights; or
  - summary: Protected health information
    text: You will not submit to us any patient, medical or other protected health information regulated by any relevant laws in any country.
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
name: Calendarific
provenance_date: '2026-11-09'
provider_name: Calendarific
provider_slug: calendarific
slug: calendarific-eligibility
source_date: '2026-11-09'
source_filename: calendarific-eligibility.yml
source_heading: Eligibility
source_page: https://calendarific.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calendarific\naid: calendarific\nurl: https://calendarific.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing to this Agreement not as an individual but on behalf of your company, then a reference\n    to “you” or “Customer” in this Agreement is a reference to the company\n- type: individual\n  text: If you are agreeing to this Agreement not as an individual but on behalf of your company\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Product or Services for any unlawful purpose or in violation\
  \ of any applicable laws, regulations,\n    or third-party rights; or\n- summary: Protected health information\n  text: You will not submit to us any patient, medical or other protected health information regulated by any relevant\n    laws in any country.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calendarific/eligibility/calendarific-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Calendarific's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Public APIs
- Holidays
- Worldwide
- Localization
---
