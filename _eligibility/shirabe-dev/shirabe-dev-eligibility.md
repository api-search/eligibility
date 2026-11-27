---
api_specs:
- filename: shirabe-dev-calendar-api-openapi.yml
  format: yaml
  label: shirabe-dev Calendar API
  slug: shirabe-dev-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-calendar-api-openapi.yml
- filename: shirabe-dev-hub-api-openapi.yml
  format: yaml
  label: shirabe-dev Hub API
  slug: shirabe-dev-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-hub-api-openapi.yml
- filename: shirabe-dev-system-api-openapi.yml
  format: yaml
  label: shirabe-dev System API
  slug: shirabe-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-system-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: 法令に違反する目的での利用
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社がこれを承認しAPIキーを発行した時点で利用契約が成立します。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: shirabe-dev
provenance_date: '2026-11-10'
provider_name: shirabe-dev
provider_slug: shirabe-dev
slug: shirabe-dev-eligibility
source_date: '2026-11-10'
source_filename: shirabe-dev-eligibility.yml
source_heading: Eligibility
source_page: https://shirabe.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shirabe-dev\naid: shirabe-dev\nurl: https://shirabe.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: 法令に違反する目的での利用\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社がこれを承認しAPIキーを発行した時点で利用契約が成立します。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shirabe-dev/eligibility/shirabe-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from shirabe-dev's own page on 2026-11-10.
synthetic: false
tags:
- API Platform
- Japanese Data
- Free Tier
- AI Integration
---
