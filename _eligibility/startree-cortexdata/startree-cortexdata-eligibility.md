---
api_specs:
- filename: startree-cortexdata-query-api-api-openapi.yml
  format: yaml
  label: StarTree (Cortexdata) Query API
  slug: startree-cortexdata-query-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/startree-cortexdata/openapi/startree-cortexdata-query-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old or the age of majority, whichever is older, to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or the age of majority, whichever is older, to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal access
    text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
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
name: StarTree (Cortexdata)
provenance_date: '2026-11-10'
provider_name: StarTree (Cortexdata)
provider_slug: startree-cortexdata
slug: startree-cortexdata-eligibility
source_date: '2026-11-10'
source_filename: startree-cortexdata-eligibility.yml
source_heading: Eligibility
source_page: https://startree.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StarTree (Cortexdata)\naid: startree-cortexdata\nurl: https://startree.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority, whichever is older, to use the Site.\nrestricted_uses:\n- summary: Illegal access\n  text: Access to the Site from countries or territories or by individuals where such access\
  \ is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority, whichever is older, to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/startree-cortexdata/eligibility/startree-cortexdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from StarTree (Cortexdata)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Infrastructure
- Real-Time Analytics
- Apache Pinot
- OLAP
- Analytics
- Streaming Data
- Database
---
