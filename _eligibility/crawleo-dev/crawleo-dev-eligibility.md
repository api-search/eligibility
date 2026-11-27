---
api_specs:
- filename: crawleo-dev-crawl-api-openapi.yml
  format: yaml
  label: crawleo-dev Crawl API
  slug: crawleo-dev-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawleo-dev/openapi/crawleo-dev-crawl-api-openapi.yml
- filename: crawleo-dev-google-maps-api-openapi.yml
  format: yaml
  label: crawleo-dev Google Maps API
  slug: crawleo-dev-google-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawleo-dev/openapi/crawleo-dev-google-maps-api-openapi.yml
- filename: crawleo-dev-search-api-openapi.yml
  format: yaml
  label: crawleo-dev Search API
  slug: crawleo-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawleo-dev/openapi/crawleo-dev-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Crawleo on behalf of a company or other entity, you represent that you have authority to bind that entity, and "you" refers to that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the Services for high-risk activities where failure could lead to harm (e.g., emergency response, medical diagnosis, weapons development, critical infrastructure control).
  - summary: Sanctions and export controls
    text: You may not use the Services in violation of export controls or sanctions laws, or for the benefit of sanctioned persons or restricted territories as prohibited by applicable law.
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
name: crawleo-dev
provenance_date: '2026-11-09'
provider_name: crawleo-dev
provider_slug: crawleo-dev
slug: crawleo-dev-eligibility
source_date: '2026-11-09'
source_filename: crawleo-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.crawleo.dev/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crawleo-dev\naid: crawleo-dev\nurl: https://www.crawleo.dev/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Crawleo on behalf of a company or other entity, you represent that you have authority to\n    bind that entity, and \"you\" refers to that entity.\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the Services for high-risk activities where failure could lead to harm (e.g., emergency response, medical\n    diagnosis, weapons development, critical infrastructure control).\n- summary:\
  \ Sanctions and export controls\n  text: You may not use the Services in violation of export controls or sanctions laws, or for the benefit of sanctioned\n    persons or restricted territories as prohibited by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crawleo-dev/eligibility/crawleo-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from crawleo-dev's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- Crawling
- MCP
---
