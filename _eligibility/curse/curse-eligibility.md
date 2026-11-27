---
api_specs:
- filename: curse-categories-api-openapi.yml
  format: yaml
  label: Curse Categories API
  slug: curse-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-categories-api-openapi.yml
- filename: curse-files-api-openapi.yml
  format: yaml
  label: Curse Files API
  slug: curse-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-files-api-openapi.yml
- filename: curse-games-api-openapi.yml
  format: yaml
  label: Curse Games API
  slug: curse-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-games-api-openapi.yml
- filename: curse-minecraft-api-openapi.yml
  format: yaml
  label: Curse Minecraft API
  slug: curse-minecraft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-minecraft-api-openapi.yml
- filename: curse-mods-api-openapi.yml
  format: yaml
  label: Curse Mods API
  slug: curse-mods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-mods-api-openapi.yml
- filename: curse-subscriptions-api-openapi.yml
  format: yaml
  label: Curse Subscriptions API
  slug: curse-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-subscriptions-api-openapi.yml
- filename: curse-usermods-api-openapi.yml
  format: yaml
  label: Curse User Mods API
  slug: curse-usermods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curse/openapi/curse-usermods-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When logged in to the CurseForge for Studios console, game developers can set up their games to be available on the CurseForge website
    type: developer
  - text: If you’re running a 3rd party modding service, we have an API solution for you.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unrequested non-developer accounts deleted
    text: Any registered account which is not a game developer and did not request a key, will be deleted
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
name: Curse
provenance_date: '2026-11-09'
provider_name: Curse
provider_slug: curse
slug: curse-eligibility
source_date: '2026-11-09'
source_filename: curse-eligibility.yml
source_heading: Eligibility
source_page: https://docs.curseforge.com/rest-api/#getting-started
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curse\naid: curse\nurl: https://docs.curseforge.com/rest-api/#getting-started\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: When logged in to the CurseForge for Studios console, game developers can set up their games to be available\n    on the CurseForge website\n- type: other\n  text: If you’re running a 3rd party modding service, we have an API solution for you.\nrestricted_uses:\n- summary: Unrequested non-developer accounts deleted\n  text: Any registered account which is not a game developer and did not request\
  \ a key, will be deleted\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curse/eligibility/curse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Curse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- MODS
- Minecraft
- Game Content
- Developer Platform
- Catalog
---
