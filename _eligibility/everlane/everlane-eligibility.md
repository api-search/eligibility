---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may use the Services to make purchases only if you are 18 years or older and capable of forming a binding contract with us.
    value: '18'
  restricted_uses:
  - summary: Automated access to the Services
    text: Attempt to access or search the Services or Content or download Content from the Services through the use of any engine, software, tool, agent, device or mechanism (including spiders, robots, crawlers, data mining tools or the like)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may also need to provide additional information to verify your identity before completing your transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: everlane
provenance_date: '2026-11-09'
provider_name: everlane
provider_slug: everlane
slug: everlane-eligibility
source_date: '2026-11-09'
source_filename: everlane-eligibility.yml
source_heading: Eligibility
source_page: https://www.everlane.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: everlane\naid: everlane\nurl: https://www.everlane.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated access to the Services\n  text: Attempt to access or search the Services or Content or download Content from the Services through the use\n    of any engine, software, tool, agent, device or mechanism (including spiders, robots, crawlers, data mining\n    tools or the like)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may also need to provide additional information\
  \ to verify your identity before completing your transaction.\nminimum_age:\n  value: '18'\n  text: You may use the Services to make purchases only if you are 18 years or older and capable of forming a binding\n    contract with us.\n"
source_yaml_url: https://artifacts.apis.io/everlane/eligibility/everlane-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from everlane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Apparel
- Fashion
- Direct to Consumer
- Shopify
- Agentic Commerce
---
