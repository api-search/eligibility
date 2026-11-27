---
api_specs:
- filename: storylane-connect
  format: yaml
  label: Storylane External API
  slug: storylane-external-api
  spec_type: Postman
  url: https://www.postman.com/team-storylane/storylane-public/collection/2zkg7jc/storylane-connect
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
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
name: Storylane
provenance_date: '2026-11-10'
provider_name: Storylane
provider_slug: storylane
slug: storylane-eligibility
source_date: '2026-11-10'
source_filename: storylane-eligibility.yml
source_heading: Eligibility
source_page: https://www.storylane.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Storylane\naid: storylane\nurl: https://www.storylane.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/storylane/eligibility/storylane-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Storylane's own page on 2026-11-10.
synthetic: false
tags:
- Interactive Demos
- Product Walkthroughs
- Sales Enablement
- Marketing
- Demo Analytics
- Demo Automation
- Buyer Hub
- Sales
- MCP
- Agent Tools
- Webhook
- Embed
- oEmbed
- Demo Automation Platform
---
