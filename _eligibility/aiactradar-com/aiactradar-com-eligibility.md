---
api_specs:
- filename: aiactradar-com-events-api-openapi.yml
  format: yaml
  label: AI Act Radar Events API
  slug: aiactradar-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-events-api-openapi.yml
- filename: aiactradar-com-health-api-openapi.yml
  format: yaml
  label: AI Act Radar Health API
  slug: aiactradar-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-health-api-openapi.yml
- filename: aiactradar-com-sources-api-openapi.yml
  format: yaml
  label: AI Act Radar Sources API
  slug: aiactradar-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-sources-api-openapi.yml
- filename: aiactradar-com-topics-api-openapi.yml
  format: yaml
  label: AI Act Radar Topics API
  slug: aiactradar-com-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-topics-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For business customers (§ 14 BGB) only.
    type: business
  minimum_age:
    text: null
    value: null
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
name: AI Act Radar
provenance_date: '2026-11-09'
provider_name: AI Act Radar
provider_slug: aiactradar-com
slug: aiactradar-com-eligibility
source_date: '2026-11-09'
source_filename: aiactradar-com-eligibility.yml
source_heading: Eligibility
source_page: https://aiactradar.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Act Radar\naid: aiactradar-com\nurl: https://aiactradar.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For business customers (§ 14 BGB) only.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiactradar-com/eligibility/aiactradar-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from AI Act Radar's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Regulations
- EU
- Webhook
- Compliance
---
