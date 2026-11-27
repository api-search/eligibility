---
api_specs:
- filename: alphabotpro-cloud-checkout-api-openapi.yml
  format: yaml
  label: AlphaBotPro Checkout API
  slug: alphabotpro-cloud-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-checkout-api-openapi.yml
- filename: alphabotpro-cloud-ea-api-openapi.yml
  format: yaml
  label: AlphaBotPro Ea API
  slug: alphabotpro-cloud-ea-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-ea-api-openapi.yml
- filename: alphabotpro-cloud-expert-advisors-api-openapi.yml
  format: yaml
  label: AlphaBotPro Expert Advisors API
  slug: alphabotpro-cloud-expert-advisors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-expert-advisors-api-openapi.yml
- filename: alphabotpro-cloud-mcp-api-openapi.yml
  format: yaml
  label: AlphaBotPro MCP API
  slug: alphabotpro-cloud-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-mcp-api-openapi.yml
- filename: alphabotpro-cloud-signals-api-openapi.yml
  format: yaml
  label: AlphaBotPro Signals API
  slug: alphabotpro-cloud-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-signals-api-openapi.yml
- filename: alphabotpro-cloud-stocks-api-openapi.yml
  format: yaml
  label: AlphaBotPro Stocks API
  slug: alphabotpro-cloud-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-stocks-api-openapi.yml
- filename: alphabotpro-cloud-warroom-api-openapi.yml
  format: yaml
  label: AlphaBotPro Warroom API
  slug: alphabotpro-cloud-warroom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-warroom-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Trading services may not be available in all countries.
  entity_types:
  - text: You must be at least 18 years old and legally permitted to use trading services in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal or broker-violating use
    text: Using our bots for illegal purposes or in violation of broker terms
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
name: AlphaBotPro
provenance_date: '2026-11-09'
provider_name: AlphaBotPro
provider_slug: alphabotpro-cloud
slug: alphabotpro-cloud-eligibility
source_date: '2026-11-09'
source_filename: alphabotpro-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://alphabotpro.cloud/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlphaBotPro\naid: alphabotpro-cloud\nurl: https://alphabotpro.cloud/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Trading services may not be available in all countries.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally permitted to use trading services in your jurisdiction.\nrestricted_uses:\n- summary: Illegal or broker-violating use\n  text: Using our bots for illegal purposes or in violation of broker terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/alphabotpro-cloud/eligibility/alphabotpro-cloud-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlphaBotPro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Automation
- Signals
- MT5
- PropFirm
---
