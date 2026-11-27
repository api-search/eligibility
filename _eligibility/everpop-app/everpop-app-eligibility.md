---
api_specs:
- filename: everpop-app-campaigns-api-openapi.yml
  format: yaml
  label: Everpop Campaigns API
  slug: everpop-app-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-campaigns-api-openapi.yml
- filename: everpop-app-clip-api-openapi.yml
  format: yaml
  label: Everpop Clip API
  slug: everpop-app-clip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-clip-api-openapi.yml
- filename: everpop-app-generate-api-openapi.yml
  format: yaml
  label: Everpop Generate API
  slug: everpop-app-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-generate-api-openapi.yml
- filename: everpop-app-jobs-api-openapi.yml
  format: yaml
  label: Everpop Jobs API
  slug: everpop-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-jobs-api-openapi.yml
- filename: everpop-app-posts-api-openapi.yml
  format: yaml
  label: Everpop Posts API
  slug: everpop-app-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-posts-api-openapi.yml
- filename: everpop-app-publish-api-openapi.yml
  format: yaml
  label: Everpop Publish API
  slug: everpop-app-publish-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-publish-api-openapi.yml
- filename: everpop-app-receipts-api-openapi.yml
  format: yaml
  label: Everpop Receipts API
  slug: everpop-app-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-receipts-api-openapi.yml
- filename: everpop-app-usage-api-openapi.yml
  format: yaml
  label: Everpop Usage API
  slug: everpop-app-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-usage-api-openapi.yml
- filename: everpop-app-videos-api-openapi.yml
  format: yaml
  label: Everpop Videos API
  slug: everpop-app-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-videos-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and able to form a binding contract.
    type: individual
  - text: If you use the Service as a business, you agree to indemnify, defend, and hold harmless Everpop and its affiliates
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Synthetic impersonation
    text: generate or publish synthetic content that impersonates a real person
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
name: Everpop
provenance_date: '2026-11-09'
provider_name: Everpop
provider_slug: everpop-app
slug: everpop-app-eligibility
source_date: '2026-11-09'
source_filename: everpop-app-eligibility.yml
source_heading: Eligibility
source_page: https://everpop.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everpop\naid: everpop-app\nurl: https://everpop.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and able to form a binding\n    contract.\n- type: business\n  text: If you use the Service as a business, you agree to indemnify, defend, and hold harmless Everpop and its\n    affiliates\nrestricted_uses:\n- summary: Synthetic impersonation\n  text: generate or publish synthetic content that impersonates a real person\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/everpop-app/eligibility/everpop-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Everpop's own page on 2026-11-09.
synthetic: false
tags:
- Video
- Artificial Intelligence
- Social Media
- Shorts
- Reels
---
