---
api_specs:
- filename: byimprint-com-mcp-api-openapi.yml
  format: yaml
  label: byImprint MCP API
  slug: byimprint-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/byimprint-com/openapi/byimprint-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All fees are in Canadian dollars; agreed software costs and applicable taxes are additional.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: 90-minute fix exclusions
    text: Not for Not a website rebuild, a brand, anything that needs someone else’s approval first, or anything that moves money.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Start dates depend on an accepted scope, agreed access and the initial payment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: byImprint
provenance_date: '2026-11-09'
provider_name: byImprint
provider_slug: byimprint-com
slug: byimprint-com-eligibility
source_date: '2026-11-09'
source_filename: byimprint-com-eligibility.yml
source_heading: Eligibility
source_page: https://byimprint.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: byImprint\naid: byimprint-com\nurl: https://byimprint.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All fees are in Canadian dollars; agreed software costs and applicable taxes are additional.\nentity_types: []\nrestricted_uses:\n- summary: 90-minute fix exclusions\n  text: Not for Not a website rebuild, a brand, anything that needs someone else’s approval first, or anything that\n    moves money.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Start dates depend on an accepted scope, agreed access and the initial payment.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/byimprint-com/eligibility/byimprint-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from byImprint's own page on 2026-11-09.
synthetic: false
tags:
- Website Design
- Customer Experience
---
