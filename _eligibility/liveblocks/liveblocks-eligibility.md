---
api_specs:
- filename: liveblocks-comments-api-openapi.yml
  format: yaml
  label: Liveblocks Comments API
  slug: liveblocks-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-comments-api-openapi.yml
- filename: liveblocks-storage-api-openapi.yml
  format: yaml
  label: Liveblocks Storage API
  slug: liveblocks-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-storage-api-openapi.yml
- filename: liveblocks-yjs-api-openapi.yml
  format: yaml
  label: Liveblocks Yjs API
  slug: liveblocks-yjs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-yjs-api-openapi.yml
- filename: liveblocks-ai-api-openapi.yml
  format: yaml
  label: Liveblocks AI API
  slug: liveblocks-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-ai-api-openapi.yml
- filename: liveblocks-auth-api-openapi.yml
  format: yaml
  label: Liveblocks Auth API
  slug: liveblocks-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-auth-api-openapi.yml
- filename: liveblocks-feeds-api-openapi.yml
  format: yaml
  label: Liveblocks Feeds API
  slug: liveblocks-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-feeds-api-openapi.yml
- filename: liveblocks-groups-api-openapi.yml
  format: yaml
  label: Liveblocks Groups API
  slug: liveblocks-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-groups-api-openapi.yml
- filename: liveblocks-management-api-openapi.yml
  format: yaml
  label: Liveblocks Management API
  slug: liveblocks-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-management-api-openapi.yml
- filename: liveblocks-notifications-api-openapi.yml
  format: yaml
  label: Liveblocks Notifications API
  slug: liveblocks-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-notifications-api-openapi.yml
- filename: liveblocks-room-api-openapi.yml
  format: yaml
  label: Liveblocks Room API
  slug: liveblocks-room-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-room-api-openapi.yml
- filename: liveblocks-version-history-api-openapi.yml
  format: yaml
  label: Liveblocks Version History API
  slug: liveblocks-version-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-version-history-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the approval of your parent or guardian.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Unauthorized use of unpurchased products
    text: you are only permitted to use products that you have purchased
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
name: Liveblocks
provenance_date: '2026-11-09'
provider_name: Liveblocks
provider_slug: liveblocks
slug: liveblocks-eligibility
source_date: '2026-11-09'
source_filename: liveblocks-eligibility.yml
source_heading: Eligibility
source_page: https://liveblocks.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liveblocks\naid: liveblocks\nurl: https://liveblocks.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the approval of your parent or guardian.\nrestricted_uses:\n- summary: Unauthorized use of unpurchased products\n  text: you are only permitted to use products that you have purchased\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/liveblocks/eligibility/liveblocks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Liveblocks's own page on 2026-11-09.
synthetic: false
tags:
- Real-Time
- Collaboration
- Multiplayer
- Presence
- CRDT
- Yjs
- Comments
- Threads
- Notification
- WebSocket
---
