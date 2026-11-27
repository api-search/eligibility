---
api_specs:
- filename: enhancedint-com-agent-api-openapi.yml
  format: yaml
  label: enhancedint-com Agent API
  slug: enhancedint-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enhancedint-com/openapi/enhancedint-com-agent-api-openapi.yml
- filename: enhancedint-com-mcp-api-openapi.yml
  format: yaml
  label: enhancedint-com MCP API
  slug: enhancedint-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enhancedint-com/openapi/enhancedint-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use this service. If you are between 13 and 18 years old, you must have permission from a parent or legal guardian.
    type: individual
  - text: We grant you a limited, non-exclusive, non-transferable license to access and use the service for personal or business purposes in accordance with these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use this service.
    value: '13'
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
name: enhancedint-com
provenance_date: '2026-11-09'
provider_name: enhancedint-com
provider_slug: enhancedint-com
slug: enhancedint-com-eligibility
source_date: '2026-11-09'
source_filename: enhancedint-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.enhancedint.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: enhancedint-com\naid: enhancedint-com\nurl: https://www.enhancedint.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use this service. If you are between 13 and 18 years old, you must\n    have permission from a parent or legal guardian.\n- type: business\n  text: We grant you a limited, non-exclusive, non-transferable license to access and use the service for personal\n    or business purposes in accordance with these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use this service.\n"
source_yaml_url: https://artifacts.apis.io/enhancedint-com/eligibility/enhancedint-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from enhancedint-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Websites
- Receptionist
- Booking
- Local Business
- Automation
---
