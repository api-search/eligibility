---
api_specs:
- filename: comos-gateway-com-actions-api-openapi.yml
  format: yaml
  label: comos-gateway-com Actions API
  slug: comos-gateway-com-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-gateway-com/openapi/comos-gateway-com-actions-api-openapi.yml
- filename: comos-gateway-com-tools-api-openapi.yml
  format: yaml
  label: comos-gateway-com Tools API
  slug: comos-gateway-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-gateway-com/openapi/comos-gateway-com-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: or be a legal entity acting through an authorized representative
    type: business
  minimum_age:
    text: Be at least 18 years of age, if an individual
    value: '18'
  restricted_uses:
  - summary: Illegal or unlicensed goods
    text: Use the Platform to sell illegal products, regulated goods without proper licensing, or items prohibited by Stripe or other payment processors
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You join the Platform as a manager, admitted either through the `federation_apply` tool or by signing in with Google or GitHub.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: comos-gateway-com
provenance_date: '2026-11-09'
provider_name: comos-gateway-com
provider_slug: comos-gateway-com
slug: comos-gateway-com-eligibility
source_date: '2026-11-09'
source_filename: comos-gateway-com-eligibility.yml
source_heading: Eligibility
source_page: https://comos-gateway.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: comos-gateway-com\naid: comos-gateway-com\nurl: https://comos-gateway.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: or be a legal entity acting through an authorized representative\nrestricted_uses:\n- summary: Illegal or unlicensed goods\n  text: Use the Platform to sell illegal products, regulated goods without proper licensing, or items prohibited\n    by Stripe or other payment processors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You join the Platform as a manager, admitted either through\
  \ the `federation_apply` tool or by signing in\n    with Google or GitHub.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age, if an individual\n"
source_yaml_url: https://artifacts.apis.io/comos-gateway-com/eligibility/comos-gateway-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from comos-gateway-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Federation
- On-Premises
- Commerce
---
