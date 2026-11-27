---
api_specs:
- filename: wayza-com-wayza-openapi.json
  format: json
  label: Wayza API
  slug: wayza-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayza-com/openapi/_original/wayza-com-wayza-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Adults can make an account on wayza.com.
    type: individual
  minimum_age:
    text: People under 18 can't
    value: '18'
  restricted_uses:
  - summary: Under-18 contact limits
    text: Under-18s can only be reached inside their own groups, never from another home, and nobody asks them anything directly
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
name: wayza-com
provenance_date: '2026-11-10'
provider_name: wayza-com
provider_slug: wayza-com
slug: wayza-com-eligibility
source_date: '2026-11-10'
source_filename: wayza-com-eligibility.yml
source_heading: Eligibility
source_page: https://wayza.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wayza-com\naid: wayza-com\nurl: https://wayza.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Adults can make an account on wayza.com.\nrestricted_uses:\n- summary: Under-18 contact limits\n  text: Under-18s can only be reached inside their own groups, never from another home, and nobody asks them anything\n    directly\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: People under 18 can't\n"
source_yaml_url: https://artifacts.apis.io/wayza-com/eligibility/wayza-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from wayza-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Integration
- Protocol
- Open Source
---
