---
api_specs:
- filename: albertsons-audiences-api-openapi.yml
  format: yaml
  label: albertsons Audiences API
  slug: albertsons-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-audiences-api-openapi.yml
- filename: albertsons-campaigns-api-openapi.yml
  format: yaml
  label: albertsons Campaigns API
  slug: albertsons-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-campaigns-api-openapi.yml
- filename: albertsons-performance-api-openapi.yml
  format: yaml
  label: albertsons Performance API
  slug: albertsons-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-performance-api-openapi.yml
- filename: albertsons-reporting-api-openapi.yml
  format: yaml
  label: albertsons Reporting API
  slug: albertsons-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-reporting-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Safeway controls and operates the Site from the USA and makes no representation that the Site is appropriate or available for use in all locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use restricted
    text: You further agree not to use the Site for any commercial uses other than management of your personal account with us, for personal, family, or home delivery of groceries by Safeway or to supply your business with groceries delivered by Safeway, unless you obtain Safeway's prior written approval.
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
name: Albertsons
provenance_date: '2026-11-09'
provider_name: Albertsons
provider_slug: albertsons
slug: albertsons-eligibility
source_date: '2026-11-09'
source_filename: albertsons-eligibility.yml
source_heading: Eligibility
source_page: https://www.albertsons.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albertsons\naid: albertsons\nurl: https://www.albertsons.com/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Safeway controls and operates the Site from the USA and makes no representation that the Site is appropriate\n    or available for use in all locations.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use restricted\n  text: You further agree not to use the Site for any commercial uses other than management of your personal account\n    with us, for personal, family, or home delivery of groceries by Safeway or to supply your business with groceries\n\
  \    delivered by Safeway, unless you obtain Safeway's prior written approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/albertsons/eligibility/albertsons-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Albertsons's own page on 2026-11-09.
synthetic: false
tags:
- Grocery
- Retail
- Retail Media
- Advertising
- Campaigns
- Analytics
- Consumer Goods
- Food
- Pharmacy
---
