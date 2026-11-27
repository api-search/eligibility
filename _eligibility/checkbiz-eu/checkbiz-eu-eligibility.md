---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Brand Watch is a monthly subscription for businesses (Starter €39, Pro €79, excluding VAT).
    type: business
  - text: Merchant Check is an API and MCP tool for developers of shopping agents.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Brand Watch brand ownership
    text: You may only watch brands and domains that you own or are authorised to protect.
  - summary: Compliance and credit uses
    text: Reports must not be used as the sole basis for legally mandated compliance processes, credit decisioning or legal documentation.
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
name: CheckBiz.eu
provenance_date: '2026-11-09'
provider_name: CheckBiz.eu
provider_slug: checkbiz-eu
slug: checkbiz-eu-eligibility
source_date: '2026-11-09'
source_filename: checkbiz-eu-eligibility.yml
source_heading: Eligibility
source_page: https://checkbiz.eu/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CheckBiz.eu\naid: checkbiz-eu\nurl: https://checkbiz.eu/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Brand Watch is a monthly subscription for businesses (Starter €39, Pro €79, excluding VAT).\n- type: developer\n  text: Merchant Check is an API and MCP tool for developers of shopping agents.\nrestricted_uses:\n- summary: Brand Watch brand ownership\n  text: You may only watch brands and domains that you own or are authorised to protect.\n- summary: Compliance and credit uses\n  text: Reports must not be used as the sole basis\
  \ for legally mandated compliance processes, credit decisioning\n    or legal documentation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/checkbiz-eu/eligibility/checkbiz-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CheckBiz.eu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Verification
- Business Registers
- VAT
- Brand Protection
- Fraud Prevention
- E-Commerce
- AI Agents
- MCP
- Europe
---
