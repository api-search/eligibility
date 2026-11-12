---
api_specs:
- filename: eudr-dev-a2a-api-openapi.yml
  format: yaml
  label: eudr.dev A2a API
  slug: eudr-dev-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-a2a-api-openapi.yml
- filename: eudr-dev-agent-api-openapi.yml
  format: yaml
  label: eudr.dev Agent API
  slug: eudr-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-agent-api-openapi.yml
- filename: eudr-dev-discovery-api-openapi.yml
  format: yaml
  label: eudr.dev Discovery API
  slug: eudr-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-discovery-api-openapi.yml
- filename: eudr-dev-engineer-api-openapi.yml
  format: yaml
  label: eudr.dev Engineer API
  slug: eudr-dev-engineer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-engineer-api-openapi.yml
- filename: eudr-dev-ops-api-openapi.yml
  format: yaml
  label: eudr.dev Ops API
  slug: eudr-dev-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-ops-api-openapi.yml
- filename: eudr-dev-public-api-openapi.yml
  format: yaml
  label: eudr.dev Public API
  slug: eudr-dev-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-public-api-openapi.yml
- filename: eudr-dev-reference-api-openapi.yml
  format: yaml
  label: eudr.dev Reference API
  slug: eudr-dev-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-reference-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The hosted service is offered for use by operators within the meaning of Reg. 2023/1115 Art. 2(15) and their authorised agents
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only operators/authorised agents under EUDR
    text: The Customer is acting as such an operator or authorised agent.
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
name: eudr.dev
provenance_date: '2026-11-09'
provider_name: eudr.dev
provider_slug: eudr-dev
slug: eudr-dev-eligibility
source_date: '2026-11-09'
source_filename: eudr-dev-eligibility.yml
source_heading: Eligibility
source_page: https://eudr.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eudr.dev\naid: eudr-dev\nurl: https://eudr.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The hosted service is offered for use by operators within the meaning of Reg. 2023/1115 Art. 2(15) and their\n    authorised agents\nrestricted_uses:\n- summary: Only operators/authorised agents under EUDR\n  text: The Customer is acting as such an operator or authorised agent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eudr-dev/eligibility/eudr-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from eudr.dev's own page on 2026-11-09.
synthetic: false
tags:
- EU Deforestation
- Compliance
- Agriculture
- AI
- Environmental
---
