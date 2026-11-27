---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use our products for any illegal or unauthorized purpose
  - summary: Reselling by dealers
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
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
name: RYSE
provenance_date: '2026-11-10'
provider_name: RYSE
provider_slug: ryse
slug: ryse-eligibility
source_date: '2026-11-10'
source_filename: ryse-eligibility.yml
source_heading: Eligibility
source_page: https://www.helloryse.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RYSE\naid: ryse\nurl: https://www.helloryse.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use our products for any illegal or unauthorized purpose\n- summary: Reselling by dealers\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed\
  \ by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/ryse/eligibility/ryse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RYSE's own page on 2026-11-10.
synthetic: false
tags:
- Smart Home
- IoT
- Consumer Electronics
- Home Automation
- Window Coverings
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- E-Commerce
- Shopify
---
