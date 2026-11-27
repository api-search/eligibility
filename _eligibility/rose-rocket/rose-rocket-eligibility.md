---
api_specs:
- filename: rose-rocket-boards-api-openapi.yml
  format: yaml
  label: Rose Rocket Boards API
  slug: rose-rocket-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rose-rocket/openapi/rose-rocket-boards-api-openapi.yml
- filename: rose-rocket-events-api-openapi.yml
  format: yaml
  label: Rose Rocket Events API
  slug: rose-rocket-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rose-rocket/openapi/rose-rocket-events-api-openapi.yml
- filename: rose-rocket-object-records-api-openapi.yml
  format: yaml
  label: Rose Rocket Object Records API
  slug: rose-rocket-object-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rose-rocket/openapi/rose-rocket-object-records-api-openapi.yml
- filename: rose-rocket-user-groups-api-openapi.yml
  format: yaml
  label: Rose Rocket User Groups API
  slug: rose-rocket-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rose-rocket/openapi/rose-rocket-user-groups-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Rose Rocket Inc., a Delaware corporation, in connection with US-based Customers, and to 2490408 Ontario Inc., doing business as Rose Rocket and TMS.ai, for Canadian Customers.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or reputation-harming use
    text: use the RR Platform for illegal purposes or purposes which will negatively impact Rose Rocket’s reputation
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
name: Rose Rocket
provenance_date: '2026-11-10'
provider_name: Rose Rocket
provider_slug: rose-rocket
slug: rose-rocket-eligibility
source_date: '2026-11-10'
source_filename: rose-rocket-eligibility.yml
source_heading: Eligibility
source_page: https://www.roserocket.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rose Rocket\naid: rose-rocket\nurl: https://www.roserocket.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Rose Rocket Inc., a Delaware corporation, in connection with US-based Customers, and to 2490408 Ontario\n    Inc., doing business as Rose Rocket and TMS.ai, for Canadian Customers.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or reputation-harming use\n  text: use the RR Platform for illegal purposes or purposes which will negatively impact Rose Rocket’s reputation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rose-rocket/eligibility/rose-rocket-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Rose Rocket's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Logistics
- Freight
- Trucking
- Transportation Management System
- Supply Chain
- Dispatch
- Webhook
- OAuth
- Canada
- Authentication
---
