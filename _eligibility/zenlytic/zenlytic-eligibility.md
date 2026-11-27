---
api_specs:
- filename: zenlytic-embedding-api-openapi.yml
  format: yaml
  label: Zenlytic Embedding API
  slug: zenlytic-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenlytic/openapi/zenlytic-embedding-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: use the Service or any product thereof for any illegal or unauthorized purpose, or in a manner which violates any laws or regulations in your jurisdiction
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
name: Zenlytic
provenance_date: '2026-11-10'
provider_name: Zenlytic
provider_slug: zenlytic
slug: zenlytic-eligibility
source_date: '2026-11-10'
source_filename: zenlytic-eligibility.yml
source_heading: Eligibility
source_page: https://docs.zenlytic.com/legal-and-support/legal/terms-of-service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenlytic\naid: zenlytic\nurl: https://docs.zenlytic.com/legal-and-support/legal/terms-of-service-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: use the Service or any product thereof for any illegal or unauthorized purpose, or in a manner which violates\n    any laws or regulations in your jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zenlytic/eligibility/zenlytic-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Zenlytic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Business Intelligence
- Analytics
- Artificial Intelligence
- Data
- Embedded Analytics
- MCP
---
