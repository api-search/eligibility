---
api_specs:
- filename: burrow-events-api-openapi.yml
  format: yaml
  label: Burrow Events API
  slug: burrow-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burrow/openapi/burrow-events-api-openapi.yml
- filename: burrow-mcp-api-openapi.yml
  format: yaml
  label: Burrow MCP API
  slug: burrow-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burrow/openapi/burrow-mcp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are the legal age of majority under applicable law to form a binding contract with us
    value: age of majority
  restricted_uses:
  - summary: Competing product
    text: You may not use the Services to build a competing product.
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
name: Burrow
provenance_date: '2026-11-09'
provider_name: Burrow
provider_slug: burrow
slug: burrow-eligibility
source_date: '2026-11-09'
source_filename: burrow-eligibility.yml
source_heading: Eligibility
source_page: https://useburrow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Burrow\naid: burrow\nurl: https://useburrow.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing product\n  text: You may not use the Services to build a competing product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are the legal age of majority under applicable law to form a binding contract with us\n"
source_yaml_url: https://artifacts.apis.io/burrow/eligibility/burrow-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Burrow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Reporting
- Automation
---
