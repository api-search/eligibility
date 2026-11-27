---
api_specs:
- filename: beehero-audio-api-openapi.yml
  format: yaml
  label: BeeHero Audio API
  slug: beehero-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beehero/openapi/beehero-audio-api-openapi.yml
- filename: beehero-auth-api-openapi.yml
  format: yaml
  label: BeeHero Auth API
  slug: beehero-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beehero/openapi/beehero-auth-api-openapi.yml
- filename: beehero-gateways-api-openapi.yml
  format: yaml
  label: BeeHero Gateways API
  slug: beehero-gateways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beehero/openapi/beehero-gateways-api-openapi.yml
- filename: beehero-sensors-api-openapi.yml
  format: yaml
  label: BeeHero Sensors API
  slug: beehero-sensors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beehero/openapi/beehero-sensors-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: if you are not of legal age to form a binding contract, please do not use or access this Site
    value: null
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
name: BeeHero
provenance_date: '2026-11-09'
provider_name: BeeHero
provider_slug: beehero
slug: beehero-eligibility
source_date: '2026-11-09'
source_filename: beehero-eligibility.yml
source_heading: Eligibility
source_page: https://www.beehero.io/legals
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeeHero\naid: beehero\nurl: https://www.beehero.io/legals\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are not of legal age to form a binding contract, please do not use or access this Site\n"
source_yaml_url: https://artifacts.apis.io/beehero/eligibility/beehero-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from BeeHero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Pollination
- beekeeping
- Precision Agriculture
- IoT
- Sensors
- Environmental Data
- MCP
- Agent-Native
---
