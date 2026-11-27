---
api_specs:
- filename: ci-hub-assets-api-openapi.yml
  format: yaml
  label: CI HUB Assets API
  slug: ci-hub-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ci-hub/openapi/ci-hub-assets-api-openapi.yml
- filename: ci-hub-auth-api-openapi.yml
  format: yaml
  label: CI HUB Auth API
  slug: ci-hub-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ci-hub/openapi/ci-hub-auth-api-openapi.yml
- filename: ci-hub-system-api-openapi.yml
  format: yaml
  label: CI HUB System API
  slug: ci-hub-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ci-hub/openapi/ci-hub-system-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: which are acting in their commercial or independent professional capacity when they conclude a license
    type: business
  - text: The CI HUB Service is only provided CI HUB Users and customers that are natural persons or legal entities or partnerships with legal capacity
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In the context of concluding a CI HUB license, the licensees must warrant that they belong to the group of persons described above.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CI HUB
provenance_date: '2026-11-09'
provider_name: CI HUB
provider_slug: ci-hub
slug: ci-hub-eligibility
source_date: '2026-11-09'
source_filename: ci-hub-eligibility.yml
source_heading: Eligibility
source_page: https://ci-hub.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CI HUB\naid: ci-hub\nurl: https://ci-hub.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: which are acting in their commercial or independent professional capacity when they conclude a license\n- type: individual\n  text: The CI HUB Service is only provided CI HUB Users and customers that are natural persons or legal entities\n    or partnerships with legal capacity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In the context of concluding a CI HUB license, the licensees\
  \ must warrant that they belong to the group\n    of persons described above.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ci-hub/eligibility/ci-hub-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from CI HUB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Asset Management
- Content Management
- Product Information Management
- Integration
- Connectors
- Creative Tools
- Marketing
- Brand Management
- MCP
- Cloud Storage
- Germany
---
