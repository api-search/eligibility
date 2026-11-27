---
api_specs:
- filename: dystro-dev-accounts-api-openapi.yml
  format: yaml
  label: dystro-dev Accounts API
  slug: dystro-dev-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-accounts-api-openapi.yml
- filename: dystro-dev-analytics-api-openapi.yml
  format: yaml
  label: dystro-dev Analytics API
  slug: dystro-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-analytics-api-openapi.yml
- filename: dystro-dev-api-keys-api-openapi.yml
  format: yaml
  label: dystro-dev API Keys API
  slug: dystro-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-api-keys-api-openapi.yml
- filename: dystro-dev-campaigns-api-openapi.yml
  format: yaml
  label: dystro-dev Campaigns API
  slug: dystro-dev-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-campaigns-api-openapi.yml
- filename: dystro-dev-connect-api-openapi.yml
  format: yaml
  label: dystro-dev Connect API
  slug: dystro-dev-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-connect-api-openapi.yml
- filename: dystro-dev-inbox-api-openapi.yml
  format: yaml
  label: dystro-dev Inbox API
  slug: dystro-dev-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-inbox-api-openapi.yml
- filename: dystro-dev-media-api-openapi.yml
  format: yaml
  label: dystro-dev Media API
  slug: dystro-dev-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-media-api-openapi.yml
- filename: dystro-dev-meta-api-openapi.yml
  format: yaml
  label: dystro-dev Meta API
  slug: dystro-dev-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-meta-api-openapi.yml
- filename: dystro-dev-posts-api-openapi.yml
  format: yaml
  label: dystro-dev Posts API
  slug: dystro-dev-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-posts-api-openapi.yml
- filename: dystro-dev-queue-api-openapi.yml
  format: yaml
  label: dystro-dev Queue API
  slug: dystro-dev-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-queue-api-openapi.yml
- filename: dystro-dev-webhooks-api-openapi.yml
  format: yaml
  label: dystro-dev Webhooks API
  slug: dystro-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and able to form a binding contract.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old and able to form a binding contract.
    value: '16'
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
name: dystro-dev
provenance_date: '2026-11-09'
provider_name: dystro-dev
provider_slug: dystro-dev
slug: dystro-dev-eligibility
source_date: '2026-11-09'
source_filename: dystro-dev-eligibility.yml
source_heading: Eligibility
source_page: https://dystro.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dystro-dev\naid: dystro-dev\nurl: https://dystro.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and able to form a binding contract.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that\n    organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/dystro-dev/eligibility/dystro-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from dystro-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developers
- Technology
- Integration
---
