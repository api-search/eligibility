---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old or have authorization from your organization to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You may not share your account or use the Service for unlawful purposes.
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
name: ClimbPast
provenance_date: '2026-11-09'
provider_name: ClimbPast
provider_slug: climbpast-com
slug: climbpast-com-eligibility
source_date: '2026-11-09'
source_filename: climbpast-com-eligibility.yml
source_heading: Eligibility
source_page: https://climbpast.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClimbPast\naid: climbpast-com\nurl: https://climbpast.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You may not share your account or use the Service for unlawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have authorization from your organization to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/climbpast-com/eligibility/climbpast-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ClimbPast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- Model Context Protocol
- Google Analytics
- Search Console
- Google Tag Manager
- Analytics
- SEO
- AI Agents
---
