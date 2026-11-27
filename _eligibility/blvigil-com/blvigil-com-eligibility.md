---
api_specs:
- filename: blvigil-com-agent-api-openapi.yml
  format: yaml
  label: Vigil Agent API
  slug: blvigil-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvigil-com/openapi/blvigil-com-agent-api-openapi.yml
- filename: blvigil-com-mcp-api-openapi.yml
  format: yaml
  label: Vigil MCP API
  slug: blvigil-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvigil-com/openapi/blvigil-com-mcp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The consumer edition is offered directly to individuals for personal household use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-safety and medical use excluded
    text: must not be used for diagnosis, treatment, emergency decisions, or as a substitute for medical, fire, carbon-monoxide, intrusion-alarm, or other life-safety equipment.
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
name: Vigil
provenance_date: '2026-11-09'
provider_name: Vigil
provider_slug: blvigil-com
slug: blvigil-com-eligibility
source_date: '2026-11-09'
source_filename: blvigil-com-eligibility.yml
source_heading: Eligibility
source_page: https://blvigil.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vigil\naid: blvigil-com\nurl: https://blvigil.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The consumer edition is offered directly to individuals for personal household use.\nrestricted_uses:\n- summary: Life-safety and medical use excluded\n  text: must not be used for diagnosis, treatment, emergency decisions, or as a substitute for medical, fire, carbon-monoxide,\n    intrusion-alarm, or other life-safety equipment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blvigil-com/eligibility/blvigil-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Vigil's own page on 2026-11-09.
synthetic: false
tags:
- Home Automation
- Security
- Smart Home
- Software
- Mac
- Windows
---
