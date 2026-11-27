---
api_specs:
- filename: infor-contents-api-openapi.yml
  format: yaml
  label: Infor Contents API
  slug: infor-contents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-contents-api-openapi.yml
- filename: infor-icua-api-openapi.yml
  format: yaml
  label: Infor ICUA API
  slug: infor-icua-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-icua-api-openapi.yml
- filename: infor-languages-api-openapi.yml
  format: yaml
  label: Infor Languages API
  slug: infor-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-languages-api-openapi.yml
- filename: infor-products-api-openapi.yml
  format: yaml
  label: Infor Products API
  slug: infor-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-products-api-openapi.yml
- filename: infor-recenttopics-api-openapi.yml
  format: yaml
  label: Infor Recent Topics API
  slug: infor-recenttopics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-recenttopics-api-openapi.yml
- filename: infor-s3-docs-api-openapi.yml
  format: yaml
  label: Infor S3 Docs API
  slug: infor-s3-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-s3-docs-api-openapi.yml
- filename: infor-search-api-openapi.yml
  format: yaml
  label: Infor Search API
  slug: infor-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-search-api-openapi.yml
- filename: infor-security-api-openapi.yml
  format: yaml
  label: Infor Security API
  slug: infor-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-security-api-openapi.yml
- filename: infor-solutions-api-openapi.yml
  format: yaml
  label: Infor Solutions API
  slug: infor-solutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-solutions-api-openapi.yml
- filename: infor-userfavorites-api-openapi.yml
  format: yaml
  label: Infor User Favorites API
  slug: infor-userfavorites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-userfavorites-api-openapi.yml
- filename: infor-web-api-openapi.yml
  format: yaml
  label: Infor Web API
  slug: infor-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-web-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, under the control of, or a national or resident of any such country [US trade sanctioned countries].
  minimum_age:
    text: By accessing or using the Company Sites, you certify that you are the age of majority or older.
    value: age of majority
  restricted_uses:
  - summary: Export restrictions
    text: You may not access, download, use or export the Company Sites, or the Resources or Content provided on or through the Company Site, including without limitation technology, technical data and information, in violation of U.S. export laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A username and password will be assigned by us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Infor
provenance_date: '2026-11-09'
provider_name: Infor
provider_slug: infor
slug: infor-eligibility
source_date: '2026-11-09'
source_filename: infor-eligibility.yml
source_heading: Eligibility
source_page: https://www.infor.com/en/about/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infor\naid: infor\nurl: https://www.infor.com/en/about/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, under the control of, or a national or resident of any such country\n    [US trade sanctioned countries].\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not access, download, use or export the Company Sites, or the Resources or Content provided on or\n    through the Company Site, including without limitation technology, technical data and information, in violation\n    of U.S. export laws or\
  \ regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A username and password will be assigned by us.\nminimum_age:\n  value: age of majority\n  text: By accessing or using the Company Sites, you certify that you are the age of majority or older.\n"
source_yaml_url: https://artifacts.apis.io/infor/eligibility/infor-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Infor's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Manufacturing
- Supply Chain
- Cloud
- Integration
---
