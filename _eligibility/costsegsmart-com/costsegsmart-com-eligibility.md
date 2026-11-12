---
api_specs:
- filename: costsegsmart-com-openapi-generated.yml
  format: yaml
  label: Cost Seg Smart API
  slug: costsegsmart-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costsegsmart-com/openapi/_ae-authored/costsegsmart-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our reports are designed for property located within the United States and its territories, owned by US taxpayers. We do not offer cost segregation for property located outside the US.
  entity_types:
  - text: US taxpayers (individuals, US LLCs, US partnerships, US corporations, and US trusts).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Securities-context use
    text: Any claim arising from use of the report in connection with a securities offering, syndication, fund formation, or capital raise
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
name: Cost Seg Smart
provenance_date: '2026-11-09'
provider_name: Cost Seg Smart
provider_slug: costsegsmart-com
slug: costsegsmart-com-eligibility
source_date: '2026-11-09'
source_filename: costsegsmart-com-eligibility.yml
source_heading: Eligibility
source_page: https://costsegsmart.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cost Seg Smart\naid: costsegsmart-com\nurl: https://costsegsmart.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our reports are designed for property located within the United States and its territories, owned by US\n    taxpayers. We do not offer cost segregation for property located outside the US.\nentity_types:\n- type: individual\n  text: US taxpayers (individuals, US LLCs, US partnerships, US corporations, and US trusts).\nrestricted_uses:\n- summary: Securities-context use\n  text: Any claim arising from use of the report in connection with a securities offering,\
  \ syndication, fund formation,\n    or capital raise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/costsegsmart-com/eligibility/costsegsmart-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cost Seg Smart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cost Segregation
- Tax
- Depreciation
- Real Estate
- Accounting
- MCP
- Agent Commerce
---
