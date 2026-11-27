---
api_specs:
- filename: mansaapi-com-api-openapi.json
  format: json
  label: Mansa API API
  slug: mansa-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mansaapi-com/openapi/_original/mansaapi-com-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Keys are issued per person or organization and may not be shared publicly or embedded in client-side code where they can be extracted.
    type: individual
  - text: Keys are issued per person or organization and may not be shared publicly or embedded in client-side code where they can be extracted.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the service for unlawful purposes or to harm others.
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
name: mansaapi-com
provenance_date: '2026-11-10'
provider_name: mansaapi-com
provider_slug: mansaapi-com
slug: mansaapi-com-eligibility
source_date: '2026-11-10'
source_filename: mansaapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://mansaapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mansaapi-com\naid: mansaapi-com\nurl: https://mansaapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Keys are issued per person or organization and may not be shared publicly or embedded in client-side code\n    where they can be extracted.\n- type: business\n  text: Keys are issued per person or organization and may not be shared publicly or embedded in client-side code\n    where they can be extracted.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the service for unlawful purposes or to harm others.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mansaapi-com/eligibility/mansaapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from mansaapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- African Data
- Markets
- Location
---
