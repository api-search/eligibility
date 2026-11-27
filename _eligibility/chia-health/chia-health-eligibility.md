---
api_specs:
- filename: chia-health-catalog-api-openapi.yml
  format: yaml
  label: Chia Health Catalog API
  slug: chia-health-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-catalog-api-openapi.yml
- filename: chia-health-handoff-sessions-api-openapi.yml
  format: yaml
  label: Chia Health Handoff sessions API
  slug: chia-health-handoff-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-handoff-sessions-api-openapi.yml
- filename: chia-health-settlements-api-openapi.yml
  format: yaml
  label: Chia Health Settlements API
  slug: chia-health-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-settlements-api-openapi.yml
- filename: chia-health-webhook-tests-api-openapi.yml
  format: yaml
  label: Chia Health Webhook tests API
  slug: chia-health-webhook-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-webhook-tests-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  entity_types:
  - text: Our Services are intended for use by you only if you are 18 years of age or over.
    type: individual
  minimum_age:
    text: Our Services are intended for use by you only if you are 18 years of age or over.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You may not access or use for any commercial purposes any part of the Services or Services Content.
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
name: Chia Health
provenance_date: '2026-11-09'
provider_name: Chia Health
provider_slug: chia-health
slug: chia-health-eligibility
source_date: '2026-11-09'
source_filename: chia-health-eligibility.yml
source_heading: Eligibility
source_page: https://chia.health/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chia Health\naid: chia-health\nurl: https://chia.health/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\nrestricted_uses:\n- summary: No commercial use\n  text: You may not access or use for any commercial purposes any part of the Services or Services Content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/chia-health/eligibility/chia-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chia Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telehealth
- Healthcare
- Peptides
- GLP-1
- Weight Loss
- Partner API
- MCP
---
