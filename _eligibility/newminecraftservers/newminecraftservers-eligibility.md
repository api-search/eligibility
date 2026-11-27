---
api_specs:
- filename: newminecraftservers-minecraft-services-api-openapi.yml
  format: yaml
  label: NewMinecraftServers Minecraft services API
  slug: newminecraftservers-minecraft-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newminecraftservers/openapi/newminecraftservers-minecraft-services-api-openapi.yml
- filename: newminecraftservers-servers-api-openapi.yml
  format: yaml
  label: NewMinecraftServers Servers API
  slug: newminecraftservers-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newminecraftservers/openapi/newminecraftservers-servers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for business purposes, you agree to defend and indemnify us against third-party claims
    type: business
  minimum_age:
    text: To create one you must be at least 13 years old, or older if your country requires it
    value: '13'
  restricted_uses:
  - summary: Vote manipulation
    text: manipulate rankings, votes, player counts or other metrics, including with bots, scripts or fake accounts
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
name: NewMinecraftServers
provenance_date: '2026-11-10'
provider_name: NewMinecraftServers
provider_slug: newminecraftservers
slug: newminecraftservers-eligibility
source_date: '2026-11-10'
source_filename: newminecraftservers-eligibility.yml
source_heading: Eligibility
source_page: https://newminecraftservers.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NewMinecraftServers\naid: newminecraftservers\nurl: https://newminecraftservers.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for business purposes, you agree to defend and indemnify us against third-party claims\nrestricted_uses:\n- summary: Vote manipulation\n  text: manipulate rankings, votes, player counts or other metrics, including with bots, scripts or fake accounts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To create\
  \ one you must be at least 13 years old, or older if your country requires it\n"
source_yaml_url: https://artifacts.apis.io/newminecraftservers/eligibility/newminecraftservers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NewMinecraftServers's own page on 2026-11-10.
synthetic: false
tags:
- Minecraft
- Gaming
- server-directory
- Game Servers
- status-monitoring
- Public APIs
- Read Only
- JSON
---
