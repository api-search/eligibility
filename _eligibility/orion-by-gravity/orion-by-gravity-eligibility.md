---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not enter into these Terms on behalf of an organization, company, or other entity unless you have the legal authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for consumer use
    text: Services under these Terms are not for consumer use.
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
name: Orion by Gravity
provenance_date: '2026-11-10'
provider_name: Orion by Gravity
provider_slug: orion-by-gravity
slug: orion-by-gravity-eligibility
source_date: '2026-11-10'
source_filename: orion-by-gravity-eligibility.yml
source_heading: Eligibility
source_page: https://www.bygravity.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orion by Gravity\naid: orion-by-gravity\nurl: https://www.bygravity.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may not enter into these Terms on behalf of an organization, company, or other entity unless you have\n    the legal authority to bind that entity.\nrestricted_uses:\n- summary: Not for consumer use\n  text: Services under these Terms are not for consumer use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orion-by-gravity/eligibility/orion-by-gravity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Orion by Gravity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Business Intelligence
- Artificial Intelligence
- Data
- MCP
- Data Warehouse
- Software-as-a-Service
---
