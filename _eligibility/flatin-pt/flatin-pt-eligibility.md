---
api_specs:
- filename: flatin-pt-public-api-openapi.yml
  format: yaml
  label: flatin.pt Public API
  slug: flatin-pt-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-public-api-openapi.yml
- filename: flatin-pt-actions-api-openapi.yml
  format: yaml
  label: flatin.pt Actions API
  slug: flatin-pt-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-actions-api-openapi.yml
- filename: flatin-pt-places-api-openapi.yml
  format: yaml
  label: flatin.pt Places API
  slug: flatin-pt-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-places-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: HOLY CHAOS, UNIPESSOAL LDA, a real-estate mediation company holding AMI licence no. 28163
    type: business
  minimum_age:
    text: null
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
name: flatin.pt
provenance_date: '2026-11-09'
provider_name: flatin.pt
provider_slug: flatin-pt
slug: flatin-pt-eligibility
source_date: '2026-11-09'
source_filename: flatin-pt-eligibility.yml
source_heading: Eligibility
source_page: https://flatin.pt/en/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flatin.pt\naid: flatin-pt\nurl: https://flatin.pt/en/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: HOLY CHAOS, UNIPESSOAL LDA, a real-estate mediation company holding AMI licence no. 28163\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flatin-pt/eligibility/flatin-pt-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from flatin.pt's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Tax
- Tax
- IMI
- IMT
- Stamp Duty
- Portugal
- Open Data
- Government Data
- Fiscal Data
- MCP
- AI Agents
---
