---
api_specs:
- filename: brandtrack-accounts-api-openapi.yml
  format: yaml
  label: Brandtrack Accounts API
  slug: brandtrack-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-accounts-api-openapi.yml
- filename: brandtrack-groups-api-openapi.yml
  format: yaml
  label: Brandtrack Groups API
  slug: brandtrack-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-groups-api-openapi.yml
- filename: brandtrack-locations-api-openapi.yml
  format: yaml
  label: Brandtrack Locations API
  slug: brandtrack-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-locations-api-openapi.yml
- filename: brandtrack-other-api-openapi.yml
  format: yaml
  label: Brandtrack Other API
  slug: brandtrack-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-other-api-openapi.yml
- filename: brandtrack-partner-api-openapi.yml
  format: yaml
  label: Brandtrack Partner API
  slug: brandtrack-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-partner-api-openapi.yml
- filename: brandtrack-roles-api-openapi.yml
  format: yaml
  label: Brandtrack Roles API
  slug: brandtrack-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-roles-api-openapi.yml
- filename: brandtrack-subscriptions-api-openapi.yml
  format: yaml
  label: Brandtrack Subscriptions API
  slug: brandtrack-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-subscriptions-api-openapi.yml
- filename: brandtrack-users-api-openapi.yml
  format: yaml
  label: Brandtrack Users API
  slug: brandtrack-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-users-api-openapi.yml
- filename: brandtrack-zones-api-openapi.yml
  format: yaml
  label: Brandtrack Zones API
  slug: brandtrack-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandtrack/openapi/brandtrack-zones-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only at listed premises
    text: Don't forget that you can only use the Service in the premises listed in the "Info Players" annex.
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
name: Brandtrack
provenance_date: '2026-11-09'
provider_name: Brandtrack
provider_slug: brandtrack
slug: brandtrack-eligibility
source_date: '2026-11-09'
source_filename: brandtrack-eligibility.yml
source_heading: Eligibility
source_page: https://www.brandtrack.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandtrack\naid: brandtrack\nurl: https://www.brandtrack.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Only at listed premises\n  text: Don't forget that you can only use the Service in the premises listed in the \"Info Players\" annex.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brandtrack/eligibility/brandtrack-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Brandtrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Background Music
- Audio
- Streaming
- Retail
- Hospitality
- In-Store Experience
- Media
- Sound
---
