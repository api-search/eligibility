---
api_specs:
- filename: sitefire-book-demo-api-openapi.yml
  format: yaml
  label: Sitefire Book Demo API
  slug: sitefire-book-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitefire/openapi/sitefire-book-demo-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By subscribing, the individual represents they have the legal authority to bind their company to these terms.
    type: business
  minimum_age:
    text: null
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
name: Sitefire
provenance_date: '2026-11-10'
provider_name: Sitefire
provider_slug: sitefire
slug: sitefire-eligibility
source_date: '2026-11-10'
source_filename: sitefire-eligibility.yml
source_heading: Eligibility
source_page: https://sitefire.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sitefire\naid: sitefire\nurl: https://sitefire.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By subscribing, the individual represents they have the legal authority to bind their company to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sitefire/eligibility/sitefire-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Sitefire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Generative Engine Optimization
- AI Visibility
- Marketing
- SEO
- Analytics
- Artificial Intelligence
- Content Generation
- MCP
- Agents
---
