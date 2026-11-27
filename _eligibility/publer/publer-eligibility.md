---
api_specs:
- filename: publer-accounts-api-openapi.yml
  format: yaml
  label: Publer Accounts API
  slug: publer-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-accounts-api-openapi.yml
- filename: publer-analytics-api-openapi.yml
  format: yaml
  label: Publer Analytics API
  slug: publer-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-analytics-api-openapi.yml
- filename: publer-competitors-api-openapi.yml
  format: yaml
  label: Publer Competitors API
  slug: publer-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-competitors-api-openapi.yml
- filename: publer-jobs-api-openapi.yml
  format: yaml
  label: Publer Jobs API
  slug: publer-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-jobs-api-openapi.yml
- filename: publer-media-api-openapi.yml
  format: yaml
  label: Publer Media API
  slug: publer-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-media-api-openapi.yml
- filename: publer-posts-api-openapi.yml
  format: yaml
  label: Publer Posts API
  slug: publer-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-posts-api-openapi.yml
- filename: publer-users-api-openapi.yml
  format: yaml
  label: Publer Users API
  slug: publer-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-users-api-openapi.yml
- filename: publer-workspaces-api-openapi.yml
  format: yaml
  label: Publer Workspaces API
  slug: publer-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-workspaces-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who are at least 13 years old.
    type: individual
  - text: User certifies to us that if User is an individual (i.e., not a corporation) User is at least 13 years of age.
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: Use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to refuse registration of, or cancel, a Publer User at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Publer
provenance_date: '2026-11-10'
provider_name: Publer
provider_slug: publer
slug: publer-eligibility
source_date: '2026-11-10'
source_filename: publer-eligibility.yml
source_heading: Eligibility
source_page: https://publer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Publer\naid: publer\nurl: https://publer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 13 years old.\n- type: business\n  text: User certifies to us that if User is an individual (i.e., not a corporation) User is at least 13 years of\n    age.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: Use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: We reserve the right to refuse registration of, or cancel, a Publer User at our discretion.\nminimum_age:\n  value: '13'\n  text: The Service is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/publer/eligibility/publer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Publer's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Scheduling
- Publishing
- Content Management
- Marketing
- Social Media Management
- Analytics
- Agents
- MCP
- Automation
---
