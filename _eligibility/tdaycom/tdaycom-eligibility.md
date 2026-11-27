---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform is available worldwide. You may not use the Platform if you are located in, or a resident of, a country or region we are prohibited from serving under applicable sanctions or export control laws.
  entity_types:
  - text: You must be at least 18 years of age to use the Platform. If you are under 18, you may only use the Platform with the involvement and consent of a parent or guardian.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or regions
    text: You may not use the Platform if you are located in, or a resident of, a country or region we are prohibited from serving under applicable sanctions or export control laws, or if you are a person we are prohibited from dealing with under those laws.
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
name: Tdaycom
provenance_date: '2026-11-10'
provider_name: Tdaycom
provider_slug: tdaycom
slug: tdaycom-eligibility
source_date: '2026-11-10'
source_filename: tdaycom-eligibility.yml
source_heading: Eligibility
source_page: https://tday.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tdaycom\naid: tdaycom\nurl: https://tday.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Platform is available worldwide. You may not use the Platform if you are located in, or a resident of,\n    a country or region we are prohibited from serving under applicable sanctions or export control laws.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Platform. If you are under 18, you may only use the Platform\n    with the involvement and consent of a parent or guardian.\nrestricted_uses:\n- summary: Sanctioned persons or regions\n\
  \  text: You may not use the Platform if you are located in, or a resident of, a country or region we are prohibited\n    from serving under applicable sanctions or export control laws, or if you are a person we are prohibited from\n    dealing with under those laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/tdaycom/eligibility/tdaycom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tdaycom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Artificial Intelligence
- Content Generation
- Design
- Video
- Social Media
- Developer Tools
- MCP
- Agents
- Y Combinator
---
