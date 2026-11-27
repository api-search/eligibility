---
api_specs:
- filename: arkolith-com-funds-api-openapi.yml
  format: yaml
  label: Arkolith Funds API
  slug: arkolith-com-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkolith-com/openapi/arkolith-com-funds-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept on behalf of an organization, you represent that you are authorized to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Market manipulation, fraud, unlawful use
    text: Use the Service for market manipulation, insider dealing, fraud, harassment, or any unlawful purpose.
  - summary: Congressional data commercial use
    text: you may not obtain or use this data, or any report underlying it, for any commercial purpose, except by news and communications media for dissemination to the general public.
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
name: Arkolith
provenance_date: '2026-11-09'
provider_name: Arkolith
provider_slug: arkolith-com
slug: arkolith-com-eligibility
source_date: '2026-11-09'
source_filename: arkolith-com-eligibility.yml
source_heading: Eligibility
source_page: https://arkolith.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arkolith\naid: arkolith-com\nurl: https://arkolith.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept on behalf of an organization, you represent that you are authorized to bind it.\nrestricted_uses:\n- summary: Market manipulation, fraud, unlawful use\n  text: Use the Service for market manipulation, insider dealing, fraud, harassment, or any unlawful purpose.\n- summary: Congressional data commercial use\n  text: you may not obtain or use this data, or any report underlying it, for any commercial purpose, except\
  \ by\n    news and communications media for dissemination to the general public.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arkolith-com/eligibility/arkolith-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Arkolith's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- SEC
- MCP
---
