---
api_specs:
- filename: centeringlab-com-grade-api-openapi.yml
  format: yaml
  label: Centering Lab Grade API
  slug: centeringlab-com-grade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centeringlab-com/openapi/centeringlab-com-grade-api-openapi.yml
- filename: centeringlab-com-health-api-openapi.yml
  format: yaml
  label: Centering Lab Health API
  slug: centeringlab-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centeringlab-com/openapi/centeringlab-com-health-api-openapi.yml
- filename: centeringlab-com-measure-api-openapi.yml
  format: yaml
  label: Centering Lab Measure API
  slug: centeringlab-com-measure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centeringlab-com/openapi/centeringlab-com-measure-api-openapi.yml
- filename: centeringlab-com-openapi-json-api-openapi.yml
  format: yaml
  label: Centering Lab Openapi.json API
  slug: centeringlab-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centeringlab-com/openapi/centeringlab-com-openapi-json-api-openapi.yml
- filename: centeringlab-com-standards-api-openapi.yml
  format: yaml
  label: Centering Lab Standards API
  slug: centeringlab-com-standards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centeringlab-com/openapi/centeringlab-com-standards-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use the service for personal and collecting purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Abuse, overloading, bypassing rate limits, bulk API scraping, unlawful activity
    text: Abuse, overloading, bypassing rate limits, bulk API scraping and unlawful activities are prohibited.
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
name: Centering Lab
provenance_date: '2026-11-09'
provider_name: Centering Lab
provider_slug: centeringlab-com
slug: centeringlab-com-eligibility
source_date: '2026-11-09'
source_filename: centeringlab-com-eligibility.yml
source_heading: Eligibility
source_page: https://centeringlab.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centering Lab\naid: centeringlab-com\nurl: https://centeringlab.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use the service for personal and collecting purposes.\nrestricted_uses:\n- summary: Abuse, overloading, bypassing rate limits, bulk API scraping, unlawful activity\n  text: Abuse, overloading, bypassing rate limits, bulk API scraping and unlawful activities are prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centeringlab-com/eligibility/centeringlab-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Centering Lab's own page on 2026-11-09.
synthetic: false
tags:
- Cards
- Centering
- Collectors
- Web App
---
