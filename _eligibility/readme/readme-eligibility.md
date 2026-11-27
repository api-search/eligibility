---
api_specs:
- filename: readme-personalized-docs-webhook-asyncapi.yml
  format: yaml
  label: ReadMe Personalized Docs Webhook
  slug: personalized-docs-webhook
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/readme/asyncapi/readme-personalized-docs-webhook-asyncapi.yml
- filename: readme-analytics-api-openapi.yml
  format: yaml
  label: ReadMe Analytics API
  slug: readme-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-analytics-api-openapi.yml
- filename: readme-api-keys-api-openapi.yml
  format: yaml
  label: ReadMe API Keys API
  slug: readme-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-api-keys-api-openapi.yml
- filename: readme-branches-api-openapi.yml
  format: yaml
  label: ReadMe Branches API
  slug: readme-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-branches-api-openapi.yml
- filename: readme-categories-api-openapi.yml
  format: yaml
  label: ReadMe Categories API
  slug: readme-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-categories-api-openapi.yml
- filename: readme-changelog-api-openapi.yml
  format: yaml
  label: ReadMe Changelog API
  slug: readme-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-changelog-api-openapi.yml
- filename: readme-custom-pages-api-openapi.yml
  format: yaml
  label: ReadMe Custom Pages API
  slug: readme-custom-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-custom-pages-api-openapi.yml
- filename: readme-guides-api-openapi.yml
  format: yaml
  label: ReadMe Guides API
  slug: readme-guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-guides-api-openapi.yml
- filename: readme-images-api-openapi.yml
  format: yaml
  label: ReadMe Images API
  slug: readme-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-images-api-openapi.yml
- filename: readme-metrics-api-openapi.yml
  format: yaml
  label: ReadMe Metrics API
  slug: readme-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-metrics-api-openapi.yml
- filename: readme-recipes-api-openapi.yml
  format: yaml
  label: ReadMe Recipes API
  slug: readme-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-recipes-api-openapi.yml
- filename: readme-search-api-openapi.yml
  format: yaml
  label: ReadMe Search API
  slug: readme-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-search-api-openapi.yml
- filename: readme-apis-api-openapi.yml
  format: yaml
  label: ReadMe APIs API
  slug: readme-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readme/openapi/readme-apis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 years or older to use ReadMe.
    type: individual
  - text: If you are entering into this agreement on behalf of a company or other legal entity, the terms “you” and “your” shall refer to the entity.
    type: business
  minimum_age:
    text: You must be 13 years or older to use ReadMe.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use ReadMe for illegal or unauthorized purpose.
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
name: ReadMe
provenance_date: '2026-11-10'
provider_name: ReadMe
provider_slug: readme
slug: readme-eligibility
source_date: '2026-11-10'
source_filename: readme-eligibility.yml
source_heading: Eligibility
source_page: https://readme.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReadMe\naid: readme\nurl: https://readme.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 years or older to use ReadMe.\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, the terms “you” and\n    “your” shall refer to the entity.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use ReadMe for illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be 13 years or older to use ReadMe.\n"
source_yaml_url: https://artifacts.apis.io/readme/eligibility/readme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ReadMe's own page on 2026-11-10.
synthetic: false
tags:
- Documentation
- Developer Hub
- API Reference
- Portal
- Analytics
- Artificial Intelligence
- MCP
- Bi-Directional Sync
- API Documentation
- Developer Portal
- OpenAPI
---
