---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Service, you must be at least 18 years old.
    type: individual
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s employer (such entity, an “ Organization ”).
    type: business
  minimum_age:
    text: To use the Service, you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable Use Policy restrictions
    text: Your use of the Service is subject to our Acceptable Use Policy , which is incorporated into these Terms by reference.
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
name: Brand.ai
provenance_date: '2026-11-09'
provider_name: Brand.ai
provider_slug: brandai
slug: brandai-eligibility
source_date: '2026-11-09'
source_filename: brandai-eligibility.yml
source_heading: Eligibility
source_page: https://brand.ai/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brand.ai\naid: brandai\nurl: https://brand.ai/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years old.\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s\n    employer (such entity, an “ Organization ”).\nrestricted_uses:\n- summary: Acceptable Use Policy restrictions\n  text: Your use of the Service is subject to our Acceptable Use Policy , which is incorporated into\
  \ these Terms\n    by reference.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Service, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/brandai/eligibility/brandai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Brand.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Brand Management
- Artificial Intelligence
- Marketing
- Software-as-a-Service
- Brand Operating System
- AI Agents
- Design
- MCP
- Brand Governance
- Brand Intelligence
---
