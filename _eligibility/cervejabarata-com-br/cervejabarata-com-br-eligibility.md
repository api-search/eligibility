---
api_specs:
- filename: cervejabarata-com-br-datasets-api-openapi.yml
  format: yaml
  label: Cerveja Barata Datasets API
  slug: cervejabarata-com-br-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-datasets-api-openapi.yml
- filename: cervejabarata-com-br-mcp-api-openapi.yml
  format: yaml
  label: Cerveja Barata MCP API
  slug: cervejabarata-com-br-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-mcp-api-openapi.yml
- filename: cervejabarata-com-br-public-api-openapi.yml
  format: yaml
  label: Cerveja Barata Public API
  slug: cervejabarata-com-br-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-public-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The content is for people aged 18 or over.
    value: '18'
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
name: Cerveja Barata
provenance_date: '2026-11-09'
provider_name: Cerveja Barata
provider_slug: cervejabarata-com-br
slug: cervejabarata-com-br-eligibility
source_date: '2026-11-09'
source_filename: cervejabarata-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://cervejabarata.com.br/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerveja Barata\naid: cervejabarata-com-br\nurl: https://cervejabarata.com.br/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The content is for people aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/cervejabarata-com-br/eligibility/cervejabarata-com-br-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Cerveja Barata's own page on 2026-11-09.
synthetic: false
tags:
- Beer
- Price Comparison
- Brazil
- Salvador
- LauroDeFreitas
---
