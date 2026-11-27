---
api_specs:
- filename: ex-libris-almaws-api-openapi.yml
  format: yaml
  label: Ex Libris Almaws API
  slug: ex-libris-almaws-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-libris/openapi/ex-libris-almaws-api-openapi.yml
- filename: ex-libris-rapido-api-openapi.yml
  format: yaml
  label: Ex Libris Rapido API
  slug: ex-libris-rapido-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-libris/openapi/ex-libris-rapido-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Members that are customers of the relevant Ex Libris programs and services
    type: other
  - text: other developers that can certify that they will not, on their own or on another party’s behalf, use or access such APIs or API Materials for any commercial purpose
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of APIs
    text: Any use or access of the APIs or API Materials for commercial purposes or by or on behalf of third parties that are marketing, developing or distributing commercially available products or services is strictly prohibited without a separate license agreement signed by Ex Libris.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Ex Libris reserves the right to refuse a registration request or to terminate a Member account for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ex Libris
provenance_date: '2026-11-09'
provider_name: Ex Libris
provider_slug: ex-libris
slug: ex-libris-eligibility
source_date: '2026-11-09'
source_filename: ex-libris-eligibility.yml
source_heading: Eligibility
source_page: https://developers.exlibrisgroup.com/about/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ex Libris\naid: ex-libris\nurl: https://developers.exlibrisgroup.com/about/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Members that are customers of the relevant Ex Libris programs and services\n- type: developer\n  text: other developers that can certify that they will not, on their own or on another party’s behalf, use or\n    access such APIs or API Materials for any commercial purpose\nrestricted_uses:\n- summary: Commercial use of APIs\n  text: Any use or access of the APIs or API Materials for commercial purposes or by\
  \ or on behalf of third parties\n    that are marketing, developing or distributing commercially available products or services is strictly prohibited\n    without a separate license agreement signed by Ex Libris.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Ex Libris reserves the right to refuse a registration request or to terminate a Member account for any reason.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ex-libris/eligibility/ex-libris-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Ex Libris's own page on 2026-11-09.
synthetic: false
tags:
- Library
- Software
- Academic
- Cloud
- Solutions
---
