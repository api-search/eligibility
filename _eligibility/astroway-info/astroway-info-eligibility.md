---
api_specs:
- filename: astroway-info-v1-openapi.json
  format: json
  label: AstroWay Calculation API V1 API
  slug: astroway-calculation-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astroway-info/openapi/_original/astroway-info-v1-openapi.json
- filename: astroway-info-openapi-openapi.json
  format: json
  label: astroway-info Openapi API
  slug: astroway-info-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astroway-info/openapi/_original/astroway-info-openapi-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    - IR
    - KP
    - SY
    - CU
    served: []
    text: 'The Service is not available to, and may not be used by: residents of or persons located in the Russian Federation, Republic of Belarus, Islamic Republic of Iran, Democratic People’s Republic of Korea (North Korea), Syrian Arab Republic, Republic of Cuba'
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons and jurisdictions
    text: Registration from listed jurisdictions or with use of geo-blocking circumvention tools (VPN, proxy, Tor) constitutes a breach of these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- BY
- IR
- KP
- SY
- CU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: astroway-info
provenance_date: '2026-11-09'
provider_name: astroway-info
provider_slug: astroway-info
slug: astroway-info-eligibility
source_date: '2026-11-09'
source_filename: astroway-info-eligibility.yml
source_heading: Eligibility
source_page: https://astroway.info/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: astroway-info\naid: astroway-info\nurl: https://astroway.info/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  - IR\n  - KP\n  - SY\n  - CU\n  text: 'The Service is not available to, and may not be used by: residents of or persons located in the Russian\n    Federation, Republic of Belarus, Islamic Republic of Iran, Democratic People’s Republic of Korea (North Korea),\n    Syrian Arab Republic, Republic of Cuba'\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons and jurisdictions\n  text: Registration from listed jurisdictions or with use\
  \ of geo-blocking circumvention tools (VPN, proxy, Tor)\n    constitutes a breach of these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/astroway-info/eligibility/astroway-info-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from astroway-info's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Horoscope
- Natal Chart
- Ukrainian
- OnlinePortal
---
