---
api_specs:
- filename: deflectvo-com-dataset-api-openapi.yml
  format: yaml
  label: Deflectvo Dataset API
  slug: deflectvo-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deflectvo-com/openapi/deflectvo-com-dataset-api-openapi.yml
- filename: deflectvo-com-mcp-api-openapi.yml
  format: yaml
  label: Deflectvo MCP API
  slug: deflectvo-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deflectvo-com/openapi/deflectvo-com-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Purchase is offered to people acting for purposes related to their trade or profession.
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
name: Deflectvo
provenance_date: '2026-11-09'
provider_name: Deflectvo
provider_slug: deflectvo-com
slug: deflectvo-com-eligibility
source_date: '2026-11-09'
source_filename: deflectvo-com-eligibility.yml
source_heading: Eligibility
source_page: https://deflectvo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deflectvo\naid: deflectvo-com\nurl: https://deflectvo.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Purchase is offered to people acting for purposes related to their trade or profession.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deflectvo-com/eligibility/deflectvo-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Deflectvo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Self-Service
- Customer Service
- Help Center
- Ticket Deflection
- Customer Portal
- Software-as-a-Service
---
