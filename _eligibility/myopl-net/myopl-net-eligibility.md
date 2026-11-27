---
api_specs:
- filename: myopl-net-mcp-api-openapi.yml
  format: yaml
  label: myopl-net MCP API
  slug: myopl-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myopl-net/openapi/myopl-net-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you access or use our Products for commercial or business purposes, such as buying ads, selling products, developing apps, managing a group or Page for your business, or using our measurement services, you must agree to our Commercial Terms.
    type: business
  minimum_age:
    text: You are under 13 years old.
    value: '13'
  restricted_uses:
  - summary: Prohibited from receiving products under law
    text: You are prohibited from receiving our products, services, or software under applicable laws.
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
name: myopl-net
provenance_date: '2026-11-10'
provider_name: myopl-net
provider_slug: myopl-net
slug: myopl-net-eligibility
source_date: '2026-11-10'
source_filename: myopl-net-eligibility.yml
source_heading: Eligibility
source_page: https://myopl.net/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: myopl-net\naid: myopl-net\nurl: https://myopl.net/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you access or use our Products for commercial or business purposes, such as buying ads, selling products,\n    developing apps, managing a group or Page for your business, or using our measurement services, you must agree\n    to our Commercial Terms.\nrestricted_uses:\n- summary: Prohibited from receiving products under law\n  text: You are prohibited from receiving our products, services, or software under applicable\
  \ laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are under 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/myopl-net/eligibility/myopl-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from myopl-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pickleball
- Sports
- Community
- Platform
---
