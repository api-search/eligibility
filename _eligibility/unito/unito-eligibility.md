---
api_specs:
- filename: unito-reports-api-openapi.yml
  format: yaml
  label: Unito Reports API
  slug: unito-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-reports-api-openapi.yml
- filename: unito-server-api-openapi.yml
  format: yaml
  label: Unito Server API
  slug: unito-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-server-api-openapi.yml
- filename: unito-workspaces-api-openapi.yml
  format: yaml
  label: Unito Workspaces API
  slug: unito-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-workspaces-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Software we provide is for commercial use only and is not intended for use by individual consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: the Client shall not export or re-export, directly or indirectly, the Software or its technology and its technical data under this Agreement to any country, entity or individual whereto exportation or re-exportation is prohibited under applicable export control laws and regulations.
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
name: Unito
provenance_date: '2026-11-10'
provider_name: Unito
provider_slug: unito
slug: unito-eligibility
source_date: '2026-11-10'
source_filename: unito-eligibility.yml
source_heading: Eligibility
source_page: https://unito.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unito\naid: unito\nurl: https://unito.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Software we provide is for commercial use only and is not intended for use by individual consumers.\nrestricted_uses:\n- summary: Export control restrictions\n  text: the Client shall not export or re-export, directly or indirectly, the Software or its technology and its\n    technical data under this Agreement to any country, entity or individual whereto exportation or re-exportation\n    is prohibited under applicable export control\
  \ laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unito/eligibility/unito-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Unito's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Two-Way Sync
- Workflow Automation
- Project Management
- Collaboration
- Embedded Integrations
- Software-as-a-Service
---
