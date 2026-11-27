---
api_specs:
- filename: mason-apps-api-openapi.yml
  format: yaml
  label: Mason Apps API
  slug: mason-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-apps-api-openapi.yml
- filename: mason-create-image-api-openapi.yml
  format: yaml
  label: Mason Create Image API
  slug: mason-create-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-create-image-api-openapi.yml
- filename: mason-images-api-openapi.yml
  format: yaml
  label: Mason Images API
  slug: mason-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-images-api-openapi.yml
- filename: mason-retrieve-an-image-api-openapi.yml
  format: yaml
  label: Mason Retrieve an Image API
  slug: mason-retrieve-an-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-retrieve-an-image-api-openapi.yml
- filename: mason-search-api-openapi.yml
  format: yaml
  label: Mason Search API
  slug: mason-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-search-api-openapi.yml
- filename: mason-template-mappings-api-openapi.yml
  format: yaml
  label: Mason Template Mappings API
  slug: mason-template-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-template-mappings-api-openapi.yml
- filename: mason-tiered-discounts-api-openapi.yml
  format: yaml
  label: Mason Tiered Discounts API
  slug: mason-tiered-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-tiered-discounts-api-openapi.yml
- filename: mason-webhooks-api-openapi.yml
  format: yaml
  label: Mason Webhooks API
  slug: mason-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mason/openapi/mason-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To redeem a Gift Card, you must register as a Creative Sparks user and must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No automated access
    text: You specifically agree not to access (or attempt to access) any of the Services through any automated means (including use of scripts or web crawlers)
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
name: Mason
provenance_date: '2026-11-10'
provider_name: Mason
provider_slug: mason
slug: mason-eligibility
source_date: '2026-11-10'
source_filename: mason-eligibility.yml
source_heading: Eligibility
source_page: https://getmason.io/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mason\naid: mason\nurl: https://getmason.io/termsofuse/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No automated access\n  text: You specifically agree not to access (or attempt to access) any of the Services through any automated means\n    (including use of scripts or web crawlers)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To redeem a Gift Card, you must register as a Creative Sparks user and must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/mason/eligibility/mason-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Mason's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Commerce
- Artificial Intelligence
- Agents
- Content Generation
- Discounts
- Promotions
- Webhook
- Shopify
---
