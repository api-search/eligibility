---
api_specs:
- filename: icao-geo-api-openapi.yml
  format: yaml
  label: ICAO GEO API
  slug: icao-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-geo-api-openapi.yml
- filename: icao-icao-api-openapi.yml
  format: yaml
  label: ICAO ICAO API
  slug: icao-icao-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-icao-api-openapi.yml
- filename: icao-infomation-api-openapi.yml
  format: yaml
  label: ICAO Infomation API
  slug: icao-infomation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-infomation-api-openapi.yml
- filename: icao-publication-api-openapi.yml
  format: yaml
  label: ICAO Publication API
  slug: icao-publication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-publication-api-openapi.yml
- filename: icao-safety-api-openapi.yml
  format: yaml
  label: ICAO Safety API
  slug: icao-safety-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-safety-api-openapi.yml
- filename: icao-usoap-api-openapi.yml
  format: yaml
  label: ICAO USOAP API
  slug: icao-usoap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icao/openapi/icao-usoap-api-openapi.yml
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
  - summary: Non-commercial use only
    text: solely for the purpose of non-commercial use and within their organization
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
name: ICAO
provenance_date: '2026-11-09'
provider_name: ICAO
provider_slug: icao
slug: icao-eligibility
source_date: '2026-11-09'
source_filename: icao-eligibility.yml
source_heading: Eligibility
source_page: https://unitingaviation.com/wp-content/uploads/2021/09/User-Terms-and-Condtions-for-ICAO-API-Data-Service-APIs-LEB_FINAL_13.04.21.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ICAO\naid: icao\nurl: https://unitingaviation.com/wp-content/uploads/2021/09/User-Terms-and-Condtions-for-ICAO-API-Data-Service-APIs-LEB_FINAL_13.04.21.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: solely for the purpose of non-commercial use and within their organization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/icao/eligibility/icao-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ICAO's own page on 2026-11-09.
synthetic: false
tags:
- Airlines
- Airports
- Airspace
- Aviation
- Reference Data
- Standards
- United Nations
---
