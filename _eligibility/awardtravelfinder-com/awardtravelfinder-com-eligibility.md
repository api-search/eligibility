---
api_specs:
- filename: awardtravelfinder-com-agent-api-openapi.yml
  format: yaml
  label: Award Travel Finder Agent API
  slug: awardtravelfinder-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardtravelfinder-com/openapi/awardtravelfinder-com-agent-api-openapi.yml
- filename: awardtravelfinder-com-airlines-api-openapi.yml
  format: yaml
  label: Award Travel Finder Airlines API
  slug: awardtravelfinder-com-airlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardtravelfinder-com/openapi/awardtravelfinder-com-airlines-api-openapi.yml
- filename: awardtravelfinder-com-british-airways-admin-only-api-openapi.yml
  format: yaml
  label: Award Travel Finder British Airways (Admin Only) API
  slug: awardtravelfinder-com-british-airways-admin-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardtravelfinder-com/openapi/awardtravelfinder-com-british-airways-admin-only-api-openapi.yml
- filename: awardtravelfinder-com-cathay-pacific-api-openapi.yml
  format: yaml
  label: Award Travel Finder Cathay Pacific API
  slug: awardtravelfinder-com-cathay-pacific-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardtravelfinder-com/openapi/awardtravelfinder-com-cathay-pacific-api-openapi.yml
- filename: awardtravelfinder-com-hotels-api-openapi.yml
  format: yaml
  label: Award Travel Finder Hotels API
  slug: awardtravelfinder-com-hotels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardtravelfinder-com/openapi/awardtravelfinder-com-hotels-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: API and MCP access on non-enterprise plans is for personal, non-commercial use only.
    type: individual
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
name: Award Travel Finder
provenance_date: '2026-11-09'
provider_name: Award Travel Finder
provider_slug: awardtravelfinder-com
slug: awardtravelfinder-com-eligibility
source_date: '2026-11-09'
source_filename: awardtravelfinder-com-eligibility.yml
source_heading: Eligibility
source_page: https://awardtravelfinder.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Award Travel Finder\naid: awardtravelfinder-com\nurl: https://awardtravelfinder.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: API and MCP access on non-enterprise plans is for personal, non-commercial use only.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/awardtravelfinder-com/eligibility/awardtravelfinder-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Award Travel Finder's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Awards
- Artificial Intelligence
- Flights
- Loyalty
---
