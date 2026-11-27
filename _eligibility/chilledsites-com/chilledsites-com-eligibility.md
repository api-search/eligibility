---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use this service
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use this service
    value: '13'
  restricted_uses:
  - summary: Illegal, harmful, or offensive content
    text: Generate content that is illegal, harmful, or offensive
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
name: ChilledSites
provenance_date: '2026-11-09'
provider_name: ChilledSites
provider_slug: chilledsites-com
slug: chilledsites-com-eligibility
source_date: '2026-11-09'
source_filename: chilledsites-com-eligibility.yml
source_heading: Eligibility
source_page: https://chilledsites.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChilledSites\naid: chilledsites-com\nurl: https://chilledsites.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use this service\nrestricted_uses:\n- summary: Illegal, harmful, or offensive content\n  text: Generate content that is illegal, harmful, or offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use this service\n"
source_yaml_url: https://artifacts.apis.io/chilledsites-com/eligibility/chilledsites-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ChilledSites's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Website Builder
- Artificial Intelligence
- No-Code
- Web Hosting
- Image Generation
- Video Generation
- Advertising
- MCP
- Agents
- A2A
- Small Business
- United Kingdom
---
