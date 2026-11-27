---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Service Terms and the Agreement for an entity, such as the company you work for, you represent to us that you have legal authority to bind that entity.
    type: business
  minimum_age:
    text: You represent to us that you are lawfully able to enter into contracts (e.g., you are not a minor).
    value: null
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
name: Vendia
provenance_date: '2026-11-10'
provider_name: Vendia
provider_slug: vendia
slug: vendia-eligibility
source_date: '2026-11-10'
source_filename: vendia-eligibility.yml
source_heading: Eligibility
source_page: https://www.vendia.com/legal/share-service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vendia\naid: vendia\nurl: https://www.vendia.com/legal/share-service-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Service Terms and the Agreement for an entity, such as the company you work\n    for, you represent to us that you have legal authority to bind that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent to us that you are lawfully able to enter into contracts (e.g., you are\
  \ not a minor).\n"
source_yaml_url: https://artifacts.apis.io/vendia/eligibility/vendia-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Vendia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Artificial Intelligence
- Data Sharing
- Data Platform
- GraphQL
- Agents
- API Gateway
- Data Governance
---
