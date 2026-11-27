---
api_specs:
- filename: voltcast-com-prices-api-openapi.yml
  format: yaml
  label: voltcast-com Prices API
  slug: voltcast-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-prices-api-openapi.yml
- filename: voltcast-com-public-api-openapi.yml
  format: yaml
  label: voltcast-com Public API
  slug: voltcast-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-public-api-openapi.yml
- filename: voltcast-com-zones-api-openapi.yml
  format: yaml
  label: voltcast-com Zones API
  slug: voltcast-com-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-zones-api-openapi.yml
claim_count: 2
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
  - summary: Free accounts limited to non-commercial use
    text: Existing Free accounts are grandfathered, remain active, and are limited to non-commercial use
  - summary: No competing raw-data redistribution
    text: use the Service to build a competing raw-data redistribution product
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
name: voltcast-com
provenance_date: '2026-11-10'
provider_name: voltcast-com
provider_slug: voltcast-com
slug: voltcast-com-eligibility
source_date: '2026-11-10'
source_filename: voltcast-com-eligibility.yml
source_heading: Eligibility
source_page: https://voltcast.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: voltcast-com\naid: voltcast-com\nurl: https://voltcast.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Free accounts limited to non-commercial use\n  text: Existing Free accounts are grandfathered, remain active, and are limited to non-commercial use\n- summary: No competing raw-data redistribution\n  text: use the Service to build a competing raw-data redistribution product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voltcast-com/eligibility/voltcast-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from voltcast-com's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Streaming
- Media
- Platform
---
