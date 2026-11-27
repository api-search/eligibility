---
api_specs:
- filename: simpplr-alerts-api-openapi.yml
  format: yaml
  label: Simpplr Alerts API
  slug: simpplr-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-alerts-api-openapi.yml
- filename: simpplr-analytics-api-openapi.yml
  format: yaml
  label: Simpplr Analytics API
  slug: simpplr-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-analytics-api-openapi.yml
- filename: simpplr-audience-api-openapi.yml
  format: yaml
  label: Simpplr Audience API
  slug: simpplr-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-audience-api-openapi.yml
- filename: simpplr-blogs-api-openapi.yml
  format: yaml
  label: Simpplr Blogs API
  slug: simpplr-blogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-blogs-api-openapi.yml
- filename: simpplr-carousels-api-openapi.yml
  format: yaml
  label: Simpplr Carousels API
  slug: simpplr-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-carousels-api-openapi.yml
- filename: simpplr-contents-api-openapi.yml
  format: yaml
  label: Simpplr Contents API
  slug: simpplr-contents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-contents-api-openapi.yml
- filename: simpplr-notifications-api-openapi.yml
  format: yaml
  label: Simpplr Notifications API
  slug: simpplr-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-notifications-api-openapi.yml
- filename: simpplr-people-api-openapi.yml
  format: yaml
  label: Simpplr People API
  slug: simpplr-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-people-api-openapi.yml
- filename: simpplr-search-api-openapi.yml
  format: yaml
  label: Simpplr Search API
  slug: simpplr-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-search-api-openapi.yml
- filename: simpplr-simpplr-api-gw-search-people-by-id-api-openapi.yml
  format: yaml
  label: Simpplr Simpplr Api Gw Search People By Id API
  slug: simpplr-simpplr-api-gw-search-people-by-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-simpplr-api-gw-search-people-by-id-api-openapi.yml
- filename: simpplr-sites-api-openapi.yml
  format: yaml
  label: Simpplr Sites API
  slug: simpplr-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-sites-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You shall not permit Users to access or use any Service or Content in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: You may not access the Services if You are Our direct competitor, except with Our prior written consent.
  - summary: Monitoring or benchmarking access
    text: You may not access the Services for purposes of monitoring their availability, performance or functionality, or for any other benchmarking or competitive purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Simpplr
provenance_date: '2026-11-10'
provider_name: Simpplr
provider_slug: simpplr
slug: simpplr-eligibility
source_date: '2026-11-10'
source_filename: simpplr-eligibility.yml
source_heading: Eligibility
source_page: https://www.simpplr.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simpplr\naid: simpplr\nurl: https://www.simpplr.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You shall not permit Users to access or use any Service or Content in a U.S. embargoed country (currently\n    Cuba, Iran, North Korea, Sudan, Syria or Crimea)\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Direct competitors barred\n  text: You may not access the Services\
  \ if You are Our direct competitor, except with Our prior written consent.\n- summary: Monitoring or benchmarking access\n  text: You may not access the Services for purposes of monitoring their availability, performance or functionality,\n    or for any other benchmarking or competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/simpplr/eligibility/simpplr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Simpplr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Experience
- Intranet
- Employee Communications
- Digital Workplace
- Internal Communications
- Human Resources
- Collaboration
- Enterprise Software
- Salesforce
---
