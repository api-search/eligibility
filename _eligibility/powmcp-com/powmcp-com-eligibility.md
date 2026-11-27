---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old, or the age of majority in your jurisdiction if higher, to use the Website.
    type: individual
  minimum_age:
    text: You must be at least 13 years old, or the age of majority in your jurisdiction if higher, to use the Website.
    value: '13'
  restricted_uses:
  - summary: Sensitive personal data
    text: Do not submit identifiable patient records, directly identifying genetic information, payment-card or bank credentials, government identifiers, authentication secrets, or other sensitive personal information.
  - summary: Regulated professional advice
    text: The health, financial-reporting, government-data, security, and related apps validate technical formats and public configuration only; they do not provide diagnosis, treatment, legal, tax, financial, filing, certification, or other regulated professional services.
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
name: powmcp-com
provenance_date: '2026-11-10'
provider_name: powmcp-com
provider_slug: powmcp-com
slug: powmcp-com-eligibility
source_date: '2026-11-10'
source_filename: powmcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://powmcp.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: powmcp-com\naid: powmcp-com\nurl: https://powmcp.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old, or the age of majority in your jurisdiction if higher, to use the Website.\nrestricted_uses:\n- summary: Sensitive personal data\n  text: Do not submit identifiable patient records, directly identifying genetic information, payment-card or bank\n    credentials, government identifiers, authentication secrets, or other sensitive personal information.\n- summary: Regulated professional advice\n\
  \  text: The health, financial-reporting, government-data, security, and related apps validate technical formats\n    and public configuration only; they do not provide diagnosis, treatment, legal, tax, financial, filing, certification,\n    or other regulated professional services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old, or the age of majority in your jurisdiction if higher, to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/powmcp-com/eligibility/powmcp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from powmcp-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Utilities
- ChatGPT
- Claude
- MCP
---
