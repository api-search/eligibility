---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company, organization, or other entity, you represent and warrant that you have authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: submit or transmit any content that is unlawful, infringing, defamatory, or that violates the rights of others
  - summary: Personal or regulated data without authority
    text: submit personal, sensitive, or regulated data of others without all required authority and consents
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
name: Glen
provenance_date: '2026-11-09'
provider_name: Glen
provider_slug: glen
slug: glen-eligibility
source_date: '2026-11-09'
source_filename: glen-eligibility.yml
source_heading: Eligibility
source_page: https://tryglen.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glen\naid: glen\nurl: https://tryglen.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company, organization, or other entity, you represent and warrant\n    that you have authority to bind that entity\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: submit or transmit any content that is unlawful, infringing, defamatory, or that violates the rights\
  \ of\n    others\n- summary: Personal or regulated data without authority\n  text: submit personal, sensitive, or regulated data of others without all required authority and consents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/glen/eligibility/glen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Glen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- MCP
- Organizational Memory
- Knowledge Management
- Developer Tools
- Y Combinator
---
