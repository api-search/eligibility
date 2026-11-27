---
api_specs:
- filename: shortkit-ad-configuration-api-openapi.yml
  format: yaml
  label: ShortKit Ad Configuration API
  slug: shortkit-ad-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shortkit/openapi/shortkit-ad-configuration-api-openapi.yml
- filename: shortkit-analytics-api-openapi.yml
  format: yaml
  label: ShortKit Analytics API
  slug: shortkit-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shortkit/openapi/shortkit-analytics-api-openapi.yml
- filename: shortkit-content-api-openapi.yml
  format: yaml
  label: ShortKit Content API
  slug: shortkit-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shortkit/openapi/shortkit-content-api-openapi.yml
- filename: shortkit-live-streams-api-openapi.yml
  format: yaml
  label: ShortKit Live Streams API
  slug: shortkit-live-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shortkit/openapi/shortkit-live-streams-api-openapi.yml
- filename: shortkit-surveys-api-openapi.yml
  format: yaml
  label: ShortKit Surveys API
  slug: shortkit-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shortkit/openapi/shortkit-surveys-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited content
    text: 'use the Services to upload, transmit, store, process, or distribute any content that: (i) is unlawful or promotes unlawful activity'
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
name: ShortKit
provenance_date: '2026-11-10'
provider_name: ShortKit
provider_slug: shortkit
slug: shortkit-eligibility
source_date: '2026-11-10'
source_filename: shortkit-eligibility.yml
source_heading: Eligibility
source_page: https://www.shortkit.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShortKit\naid: shortkit\nurl: https://www.shortkit.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity.\nrestricted_uses:\n- summary: Unlawful or prohibited content\n  text: 'use the Services to upload, transmit, store, process, or distribute any content that: (i) is unlawful or\n    promotes unlawful activity'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shortkit/eligibility/shortkit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ShortKit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Short-Form Video
- Video SDK
- Streaming
- Live Streaming
- Content Delivery
- Analytics
- Advertising
- Y Combinator
---
