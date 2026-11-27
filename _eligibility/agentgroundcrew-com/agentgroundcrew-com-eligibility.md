---
api_specs:
- filename: openapi.json
  format: json
  label: Agent Groundcrew API
  slug: agentgroundcrew-api
  spec_type: OpenAPI
  url: https://agentgroundcrew.com/openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Nationwide United States operations, including Arkansas, Oklahoma and Texas. International inquiries welcome; scope and scheduling confirmed per request.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Specialized or hazardous work
    text: Specialized construction, vehicle operation, regulated trades, and hazardous work require appropriately qualified providers and job-specific verification.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Task locations, rental vendors, insurance providers, property owners, or applicable requirements may still require identity or contact details.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: agentgroundcrew-com
provenance_date: '2026-11-09'
provider_name: agentgroundcrew-com
provider_slug: agentgroundcrew-com
slug: agentgroundcrew-com-eligibility
source_date: '2026-11-09'
source_filename: agentgroundcrew-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentgroundcrew.com/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agentgroundcrew-com\naid: agentgroundcrew-com\nurl: https://agentgroundcrew.com/policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Nationwide United States operations, including Arkansas, Oklahoma and Texas. International inquiries welcome;\n    scope and scheduling confirmed per request.\nentity_types: []\nrestricted_uses:\n- summary: Specialized or hazardous work\n  text: Specialized construction, vehicle operation, regulated trades, and hazardous work require appropriately\n    qualified providers and job-specific verification.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Task locations, rental vendors, insurance providers, property owners, or applicable requirements may still\n    require identity or contact details.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentgroundcrew-com/eligibility/agentgroundcrew-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from agentgroundcrew-com's own page on 2026-11-09.
synthetic: false
tags:
- Field Service Management
- Human Execution
- MCP
- Payments
- REST API
---
