---
api_specs:
- filename: beeper-accounts-api-openapi.yml
  format: yaml
  label: Beeper Accounts API
  slug: beeper-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-accounts-api-openapi.yml
- filename: beeper-app-api-openapi.yml
  format: yaml
  label: Beeper App API
  slug: beeper-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-app-api-openapi.yml
- filename: beeper-chats-api-openapi.yml
  format: yaml
  label: Beeper Chats API
  slug: beeper-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-chats-api-openapi.yml
- filename: beeper-contacts-api-openapi.yml
  format: yaml
  label: Beeper Contacts API
  slug: beeper-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-contacts-api-openapi.yml
- filename: beeper-files-api-openapi.yml
  format: yaml
  label: Beeper Files API
  slug: beeper-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-files-api-openapi.yml
- filename: beeper-messages-api-openapi.yml
  format: yaml
  label: Beeper Messages API
  slug: beeper-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-messages-api-openapi.yml
- filename: beeper-server-api-openapi.yml
  format: yaml
  label: Beeper Server API
  slug: beeper-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beeper/openapi/beeper-server-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your right to access and use Beeper is personal to you, and you may not allow anyone else to access your Beeper account.
    type: individual
  minimum_age:
    text: You must be at least 13 years old or the minimum legal age in your country/state to use Beeper. If you live in a country in the European Economic Area, you must be at least 16 years old to use Beeper.
    value: '13'
  restricted_uses:
  - summary: Suspension for fraud or illegal activity
    text: We may suspend your Beeper account or stop providing Beeper to you if we suspect you are committing fraud or are engaging in illegal activity.
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
name: Beeper
provenance_date: '2026-11-09'
provider_name: Beeper
provider_slug: beeper
slug: beeper-eligibility
source_date: '2026-11-09'
source_filename: beeper-eligibility.yml
source_heading: Eligibility
source_page: https://www.beeper.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beeper\naid: beeper\nurl: https://www.beeper.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Your right to access and use Beeper is personal to you, and you may not allow anyone else to access your\n    Beeper account.\nrestricted_uses:\n- summary: Suspension for fraud or illegal activity\n  text: We may suspend your Beeper account or stop providing Beeper to you if we suspect you are committing fraud\n    or are engaging in illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You must be at least 13 years old or the minimum legal age in your country/state to use Beeper. If you live\n    in a country in the European Economic Area, you must be at least 16 years old to use Beeper.\n"
source_yaml_url: https://artifacts.apis.io/beeper/eligibility/beeper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Beeper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Messaging
- Chat
- Communications
- Matrix
- MCP
- Desktop
- Aggregator
- Real-Time
---
