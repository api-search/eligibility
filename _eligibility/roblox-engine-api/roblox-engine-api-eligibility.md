---
api_specs:
- filename: roblox-engine-api-assets-api-openapi.yml
  format: yaml
  label: Roblox Engine API Assets API
  slug: roblox-engine-api-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-assets-api-openapi.yml
- filename: roblox-engine-api-groups-api-openapi.yml
  format: yaml
  label: Roblox Engine API Groups API
  slug: roblox-engine-api-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-groups-api-openapi.yml
- filename: roblox-engine-api-messaging-api-openapi.yml
  format: yaml
  label: Roblox Engine API Messaging API
  slug: roblox-engine-api-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-messaging-api-openapi.yml
- filename: roblox-engine-api-places-api-openapi.yml
  format: yaml
  label: Roblox Engine API Places API
  slug: roblox-engine-api-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-places-api-openapi.yml
- filename: roblox-engine-api-universes-api-openapi.yml
  format: yaml
  label: Roblox Engine API Universes API
  slug: roblox-engine-api-universes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-universes-api-openapi.yml
- filename: roblox-engine-api-users-api-openapi.yml
  format: yaml
  label: Roblox Engine API Users API
  slug: roblox-engine-api-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-users-api-openapi.yml
- filename: roblox-engine-api-datastores-api-openapi.yml
  format: yaml
  label: Roblox Engine API Datastores API
  slug: roblox-engine-api-datastores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roblox-engine-api/openapi/roblox-engine-api-datastores-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users ages 5 and older may create an Account , but certain features for the Services must be enabled by a parent or legal guardian through our Parental Controls .
    type: individual
  - text: If you are using the Services on behalf of an entity, you represent and warrant that you have authority to bind that entity to Roblox Terms
    type: business
  minimum_age:
    text: Users ages 5 and older may create an Account
    value: '5'
  restricted_uses:
  - summary: AI Features prohibited uses
    text: submit Prompts that include sensitive, confidential, or personal information
  - summary: AI Features prohibited uses
    text: implement automated decision making that has legal or similarly significant effects on individuals
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Roblox reserves the right to take steps to verify the information you provide for your Account .
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Roblox Engine API
provenance_date: '2026-11-10'
provider_name: Roblox Engine API
provider_slug: roblox-engine-api
slug: roblox-engine-api-eligibility
source_date: '2026-11-10'
source_filename: roblox-engine-api-eligibility.yml
source_heading: Eligibility
source_page: https://en.help.roblox.com/hc/en-us/articles/115004647846-Roblox-Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roblox Engine API\naid: roblox-engine-api\nurl: https://en.help.roblox.com/hc/en-us/articles/115004647846-Roblox-Terms-of-Use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users ages 5 and older may create an Account , but certain features for the Services must be enabled by\n    a parent or legal guardian through our Parental Controls .\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent and warrant that you have authority\n    to bind that entity to Roblox Terms\nrestricted_uses:\n\
  - summary: AI Features prohibited uses\n  text: submit Prompts that include sensitive, confidential, or personal information\n- summary: AI Features prohibited uses\n  text: implement automated decision making that has legal or similarly significant effects on individuals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Roblox reserves the right to take steps to verify the information you provide for your Account .\nminimum_age:\n  value: '5'\n  text: Users ages 5 and older may create an Account\n"
source_yaml_url: https://artifacts.apis.io/roblox-engine-api/eligibility/roblox-engine-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Roblox Engine API's own page on 2026-11-10.
synthetic: false
tags:
- Gaming
- Game Development
- Metaverse
- Roblox
- Open Cloud
---
