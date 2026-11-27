---
api_specs:
- filename: videoamp-admeasurements-api-openapi.yml
  format: yaml
  label: VideoAmp Ad Measurements API
  slug: videoamp-admeasurements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-admeasurements-api-openapi.yml
- filename: videoamp-audiences-api-openapi.yml
  format: yaml
  label: VideoAmp Audiences API
  slug: videoamp-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-audiences-api-openapi.yml
- filename: videoamp-campaigns-api-openapi.yml
  format: yaml
  label: VideoAmp Campaigns API
  slug: videoamp-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-campaigns-api-openapi.yml
- filename: videoamp-consents-api-openapi.yml
  format: yaml
  label: VideoAmp Consents API
  slug: videoamp-consents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-consents-api-openapi.yml
- filename: videoamp-content-api-openapi.yml
  format: yaml
  label: VideoAmp Content API
  slug: videoamp-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-content-api-openapi.yml
- filename: videoamp-currency-of-record-api-openapi.yml
  format: yaml
  label: VideoAmp Currency Of Record API
  slug: videoamp-currency-of-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-currency-of-record-api-openapi.yml
- filename: videoamp-datastreamtypes-api-openapi.yml
  format: yaml
  label: VideoAmp Data Stream Types API
  slug: videoamp-datastreamtypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-datastreamtypes-api-openapi.yml
- filename: videoamp-inventories-api-openapi.yml
  format: yaml
  label: VideoAmp Inventories API
  slug: videoamp-inventories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-inventories-api-openapi.yml
- filename: videoamp-library-api-openapi.yml
  format: yaml
  label: VideoAmp Library API
  slug: videoamp-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-library-api-openapi.yml
- filename: videoamp-me-api-openapi.yml
  format: yaml
  label: VideoAmp Me API
  slug: videoamp-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-me-api-openapi.yml
- filename: videoamp-plans-api-openapi.yml
  format: yaml
  label: VideoAmp Plans API
  slug: videoamp-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-plans-api-openapi.yml
- filename: videoamp-reports-api-openapi.yml
  format: yaml
  label: VideoAmp Reports API
  slug: videoamp-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-reports-api-openapi.yml
- filename: videoamp-shares-api-openapi.yml
  format: yaml
  label: VideoAmp Shares API
  slug: videoamp-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-shares-api-openapi.yml
- filename: videoamp-data-streams-api-openapi.yml
  format: yaml
  label: VideoAmp Data Streams API
  slug: videoamp-data-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videoamp/openapi/videoamp-data-streams-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: acting in a business or professional capacity
    type: business
  minimum_age:
    text: This Site is offered and intended for use by users who are 18 years of age
    value: '18'
  restricted_uses:
  - summary: No scraping or data extraction
    text: you are not permitted to engage in or use any data mining, robots, scraping or similar data gathering or extraction methods.
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
name: VideoAmp
provenance_date: '2026-11-10'
provider_name: VideoAmp
provider_slug: videoamp
slug: videoamp-eligibility
source_date: '2026-11-10'
source_filename: videoamp-eligibility.yml
source_heading: Eligibility
source_page: https://videoamp.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VideoAmp\naid: videoamp\nurl: https://videoamp.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: acting in a business or professional capacity\nrestricted_uses:\n- summary: No scraping or data extraction\n  text: you are not permitted to engage in or use any data mining, robots, scraping or similar data gathering or\n    extraction methods.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is offered and intended for use by users who are 18\
  \ years of age\n"
source_yaml_url: https://artifacts.apis.io/videoamp/eligibility/videoamp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from VideoAmp's own page on 2026-11-10.
synthetic: false
tags:
- Media Measurement
- Advertising
- AdTech
- tv-currency
- Audience Measurement
- Media Planning
- Streaming
- Attribution
- Data Collaboration
- MCP
- Agent-Native
---
