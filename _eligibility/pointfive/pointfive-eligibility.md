---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Use the Services to violate any applicable laws, rules or regulations, or for any unlawful, harmful, irresponsible, or inappropriate purpose
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
name: Pointfive
provenance_date: '2026-11-10'
provider_name: Pointfive
provider_slug: pointfive
slug: pointfive-eligibility
source_date: '2026-11-10'
source_filename: pointfive-eligibility.yml
source_heading: Eligibility
source_page: https://www.pointfive.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pointfive\naid: pointfive\nurl: https://www.pointfive.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that\n    entity\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Use the Services to violate any applicable laws, rules or regulations, or for any unlawful, harmful, irresponsible,\n    or inappropriate purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pointfive/eligibility/pointfive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Pointfive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- FinOps
- Cloud Cost Optimization
- Cloud Infrastructure
- Kubernetes
- AI Infrastructure
- MCP
---
