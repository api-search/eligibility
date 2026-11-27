---
api_specs:
- filename: weatherai-io-openapi.json
  format: json
  label: Decision API
  slug: decision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherai-io/openapi/weatherai-io-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual using the Service wholly or mainly outside their trade, business, craft or profession
    type: individual
  minimum_age:
    text: You must be at least 18 and give us accurate details
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or sanctioned use
    text: use the Service unlawfully, fraudulently or in breach of anyone's rights, or in breach of sanctions or export control laws
  - summary: Safety-critical decisions
    text: Do not use the Service as the only basis for any decision that could affect anyone's safety
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
name: weatherAI.io
provenance_date: '2026-11-10'
provider_name: weatherAI.io
provider_slug: weatherai-io
slug: weatherai-io-eligibility
source_date: '2026-11-10'
source_filename: weatherai-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.weatherai.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: weatherAI.io\naid: weatherai-io\nurl: https://www.weatherai.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual using the Service wholly or mainly outside their trade, business, craft or profession\nrestricted_uses:\n- summary: Unlawful, fraudulent or sanctioned use\n  text: use the Service unlawfully, fraudulently or in breach of anyone's rights, or in breach of sanctions or export\n    control laws\n- summary: Safety-critical decisions\n  text: Do not use the Service as the only basis for any decision that could\
  \ affect anyone's safety\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and give us accurate details\n"
source_yaml_url: https://artifacts.apis.io/weatherai-io/eligibility/weatherai-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from weatherAI.io's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Artificial Intelligence
- Decisions
- Forecast
---
