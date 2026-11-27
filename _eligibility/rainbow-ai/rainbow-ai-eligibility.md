---
api_specs:
- filename: rainbow-ai-nowcast-api-openapi.yml
  format: yaml
  label: Rainbow.AI Nowcast API
  slug: rainbow-ai-nowcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-nowcast-api-openapi.yml
- filename: rainbow-ai-radar-api-openapi.yml
  format: yaml
  label: Rainbow.AI Radar API
  slug: rainbow-ai-radar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-radar-api-openapi.yml
- filename: rainbow-ai-snapshots-api-openapi.yml
  format: yaml
  label: Rainbow.AI Snapshots API
  slug: rainbow-ai-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-snapshots-api-openapi.yml
- filename: rainbow-ai-tiles-api-openapi.yml
  format: yaml
  label: Rainbow.AI Tiles API
  slug: rainbow-ai-tiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-tiles-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any country subject to embargoes, sanctions, or export controls by the EU, US, or UN.
  entity_types:
  - text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to register and use the API.
    type: individual
  - text: If you are using the API on behalf of an organization, you represent that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to register and use the API.
    value: '18'
  restricted_uses:
  - summary: Safety-critical and life-threatening uses
    text: Use the API or API Data in any critical safety or life-threatening contexts where accurate, timely data is vital without our prior written agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account and provide accurate, up-to-date information, including a valid email and payment information during registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rainbow.AI
provenance_date: '2026-11-10'
provider_name: Rainbow.AI
provider_slug: rainbow-ai
slug: rainbow-ai-eligibility
source_date: '2026-11-10'
source_filename: rainbow-ai-eligibility.yml
source_heading: Eligibility
source_page: https://developer.rainbow.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rainbow.AI\naid: rainbow-ai\nurl: https://developer.rainbow.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country subject to embargoes, sanctions, or export controls by the EU, US, or UN.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to register and use\n    the API.\n- type: business\n  text: If you are using the API on behalf of an organization, you represent that\
  \ you have authority to bind that\n    organization to these Terms\nrestricted_uses:\n- summary: Safety-critical and life-threatening uses\n  text: Use the API or API Data in any critical safety or life-threatening contexts where accurate, timely data\n    is vital without our prior written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account and provide accurate, up-to-date information, including a valid email and payment\n    information during registration.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to register and use\n    the API.\n"
source_yaml_url: https://artifacts.apis.io/rainbow-ai/eligibility/rainbow-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Rainbow.AI's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Precipitation
- Forecasting
- Nowcast
- Radar
- Tiles
- Geospatial
---
