---
api_specs:
- filename: beatapi-account-api-openapi.yml
  format: yaml
  label: BeatAPI Account API
  slug: beatapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-account-api-openapi.yml
- filename: beatapi-capabilities-api-openapi.yml
  format: yaml
  label: BeatAPI Capabilities API
  slug: beatapi-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-capabilities-api-openapi.yml
- filename: beatapi-decisions-api-openapi.yml
  format: yaml
  label: BeatAPI Decisions API
  slug: beatapi-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-decisions-api-openapi.yml
- filename: beatapi-ecommerce-video-api-openapi.yml
  format: yaml
  label: BeatAPI Ecommerce Video API
  slug: beatapi-ecommerce-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-ecommerce-video-api-openapi.yml
- filename: beatapi-effects-api-openapi.yml
  format: yaml
  label: BeatAPI Effects API
  slug: beatapi-effects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-effects-api-openapi.yml
- filename: beatapi-files-api-openapi.yml
  format: yaml
  label: BeatAPI Files API
  slug: beatapi-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-files-api-openapi.yml
- filename: beatapi-generation-api-openapi.yml
  format: yaml
  label: BeatAPI Generation API
  slug: beatapi-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-generation-api-openapi.yml
- filename: beatapi-music-video-api-openapi.yml
  format: yaml
  label: BeatAPI Music Video API
  slug: beatapi-music-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-music-video-api-openapi.yml
- filename: beatapi-realtime-video-api-openapi.yml
  format: yaml
  label: BeatAPI Realtime Video API
  slug: beatapi-realtime-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-realtime-video-api-openapi.yml
- filename: beatapi-social-data-api-openapi.yml
  format: yaml
  label: BeatAPI Social Data API
  slug: beatapi-social-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-social-data-api-openapi.yml
- filename: beatapi-tasks-api-openapi.yml
  format: yaml
  label: BeatAPI Tasks API
  slug: beatapi-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-tasks-api-openapi.yml
- filename: beatapi-text-api-openapi.yml
  format: yaml
  label: BeatAPI Text API
  slug: beatapi-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-text-api-openapi.yml
- filename: beatapi-usage-api-openapi.yml
  format: yaml
  label: BeatAPI Usage API
  slug: beatapi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-usage-api-openapi.yml
- filename: beatapi-video-analysis-api-openapi.yml
  format: yaml
  label: BeatAPI Video Analysis API
  slug: beatapi-video-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-video-analysis-api-openapi.yml
- filename: beatapi-web-search-api-openapi.yml
  format: yaml
  label: BeatAPI Web Search API
  slug: beatapi-web-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-web-search-api-openapi.yml
- filename: beatapi-webhooks-api-openapi.yml
  format: yaml
  label: BeatAPI Webhooks API
  slug: beatapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-webhooks-api-openapi.yml
- filename: beatapi-workflows-api-openapi.yml
  format: yaml
  label: BeatAPI Workflows API
  slug: beatapi-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability may vary by region, capability, provider policy, and legal requirements.
  entity_types:
  - text: If you use BeatAPI on behalf of a company or other organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: You must not access, use, transfer, or provide BeatAPI services in violation of export control or economic sanctions laws applicable to the service or transaction.
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
name: BeatAPI
provenance_date: '2026-11-09'
provider_name: BeatAPI
provider_slug: beatapi
slug: beatapi-eligibility
source_date: '2026-11-09'
source_filename: beatapi-eligibility.yml
source_heading: Eligibility
source_page: https://beatapi.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeatAPI\naid: beatapi\nurl: https://beatapi.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability may vary by region, capability, provider policy, and legal requirements.\nentity_types:\n- type: business\n  text: If you use BeatAPI on behalf of a company or other organization, you represent that you have authority to\n    bind that organization.\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: You must not access, use, transfer, or provide BeatAPI services in violation of export control or economic\n    sanctions laws applicable to the\
  \ service or transaction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beatapi/eligibility/beatapi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from BeatAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Unified API
- Data Integration
---
