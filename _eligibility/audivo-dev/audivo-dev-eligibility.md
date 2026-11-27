---
api_specs:
- filename: audivo-dev-account-api-openapi.yml
  format: yaml
  label: audivo-dev Account API
  slug: audivo-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-account-api-openapi.yml
- filename: audivo-dev-api-keys-api-openapi.yml
  format: yaml
  label: audivo-dev API Keys API
  slug: audivo-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-api-keys-api-openapi.yml
- filename: audivo-dev-billing-api-openapi.yml
  format: yaml
  label: audivo-dev Billing API
  slug: audivo-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-billing-api-openapi.yml
- filename: audivo-dev-catalog-api-openapi.yml
  format: yaml
  label: audivo-dev Catalog API
  slug: audivo-dev-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-catalog-api-openapi.yml
- filename: audivo-dev-connected-apps-api-openapi.yml
  format: yaml
  label: audivo-dev Connected Apps API
  slug: audivo-dev-connected-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-connected-apps-api-openapi.yml
- filename: audivo-dev-data-api-openapi.yml
  format: yaml
  label: audivo-dev Data API
  slug: audivo-dev-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-data-api-openapi.yml
- filename: audivo-dev-groups-api-openapi.yml
  format: yaml
  label: audivo-dev Groups API
  slug: audivo-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-groups-api-openapi.yml
- filename: audivo-dev-quotes-api-openapi.yml
  format: yaml
  label: audivo-dev Quotes API
  slug: audivo-dev-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-quotes-api-openapi.yml
- filename: audivo-dev-session-api-openapi.yml
  format: yaml
  label: audivo-dev Session API
  slug: audivo-dev-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-session-api-openapi.yml
- filename: audivo-dev-transcripts-api-openapi.yml
  format: yaml
  label: audivo-dev Transcripts API
  slug: audivo-dev-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-transcripts-api-openapi.yml
- filename: audivo-dev-uploads-api-openapi.yml
  format: yaml
  label: audivo-dev Uploads API
  slug: audivo-dev-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-uploads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter a binding agreement to use Audivo.
    type: individual
  - text: If you use the service for an organization, you must have authority to agree on its behalf.
    type: business
  minimum_age:
    text: You must be legally able to enter a binding agreement to use Audivo.
    value: null
  restricted_uses:
  - summary: Unauthorized uploads
    text: Upload audio you do not own or do not have the rights and permissions to have transcribed.
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
name: audivo-dev
provenance_date: '2026-11-09'
provider_name: audivo-dev
provider_slug: audivo-dev
slug: audivo-dev-eligibility
source_date: '2026-11-09'
source_filename: audivo-dev-eligibility.yml
source_heading: Eligibility
source_page: https://audivo.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: audivo-dev\naid: audivo-dev\nurl: https://audivo.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter a binding agreement to use Audivo.\n- type: business\n  text: If you use the service for an organization, you must have authority to agree on its behalf.\nrestricted_uses:\n- summary: Unauthorized uploads\n  text: Upload audio you do not own or do not have the rights and permissions to have transcribed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: You must be legally able to enter a binding agreement to use Audivo.\n"
source_yaml_url: https://artifacts.apis.io/audivo-dev/eligibility/audivo-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from audivo-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Transcripts
- Audio
---
