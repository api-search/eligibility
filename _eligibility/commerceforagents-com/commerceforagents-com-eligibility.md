---
api_specs:
- filename: commerceforagents-com-mcp-api-openapi.yml
  format: yaml
  label: Commerce for Agents MCP API
  slug: commerceforagents-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commerceforagents-com/openapi/commerceforagents-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    - US
    text: The Service compares live electricity and gas tariffs for households in Germany. The Service also compares fixed home internet providers available at a US address
  entity_types:
  - text: you are of legal age
    type: individual
  minimum_age:
    text: you are of legal age
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
name: Commerce for Agents
provenance_date: '2026-11-09'
provider_name: Commerce for Agents
provider_slug: commerceforagents-com
slug: commerceforagents-com-eligibility
source_date: '2026-11-09'
source_filename: commerceforagents-com-eligibility.yml
source_heading: Eligibility
source_page: https://commerceforagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Commerce for Agents\naid: commerceforagents-com\nurl: https://commerceforagents.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  - US\n  excluded: []\n  text: The Service compares live electricity and gas tariffs for households in Germany. The Service also compares\n    fixed home internet providers available at a US address\nentity_types:\n- type: individual\n  text: you are of legal age\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age\n"
source_yaml_url: https://artifacts.apis.io/commerceforagents-com/eligibility/commerceforagents-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Commerce for Agents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agentic Commerce
- MCP
- Price Comparison
- Energy
- Electricity
- Gas
- Broadband
- Mobile Plans
- eSIM
- VPN
- Germany
---
