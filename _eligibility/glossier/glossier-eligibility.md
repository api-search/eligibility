---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside in the United Kingdom or European Union, additional terms and conditions may be applicable to you
  entity_types:
  - text: You represent and warrant that you are at least 13 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age. If you are under age 13, you may not, under any circumstances or for any reason, use the Site.
    value: '13'
  restricted_uses:
  - summary: Personal use only
    text: All orders of Products must be for your personal use only.
  - summary: Personal, noncommercial site access
    text: You may only access the Site for your own personal, noncommercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Glossier reserves the right, in its sole discretion, to verify your information prior to processing your order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Glossier
provenance_date: '2026-11-09'
provider_name: Glossier
provider_slug: glossier
slug: glossier-eligibility
source_date: '2026-11-09'
source_filename: glossier-eligibility.yml
source_heading: Eligibility
source_page: https://www.glossier.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glossier\naid: glossier\nurl: https://www.glossier.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you reside in the United Kingdom or European Union, additional terms and conditions may be applicable\n    to you\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 13 years of age.\nrestricted_uses:\n- summary: Personal use only\n  text: All orders of Products must be for your personal use only.\n- summary: Personal, noncommercial site access\n  text: You may only access the Site for your own\
  \ personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Glossier reserves the right, in its sole discretion, to verify your information prior to processing your\n    order\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age. If you are under age 13, you may not, under\n    any circumstances or for any reason, use the Site.\n"
source_yaml_url: https://artifacts.apis.io/glossier/eligibility/glossier-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Glossier's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Beauty
- Cosmetics
- E-Commerce
- Retail
- Agentic Commerce
- Universal Commerce Protocol
- Shopify
- MCP
---
