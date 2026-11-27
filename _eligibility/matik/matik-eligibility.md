---
api_specs:
- filename: matik-oauth-postman-collection.json
  format: json
  label: Matik External API
  slug: matik-external-api
  spec_type: Postman
  url: https://artifacts.apis.io/matik/postman/matik-oauth-postman-collection.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: engage in any unlawful or fraudulent activity
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
name: Matik
provenance_date: '2026-11-10'
provider_name: Matik
provider_slug: matik
slug: matik-eligibility
source_date: '2026-11-10'
source_filename: matik-eligibility.yml
source_heading: Eligibility
source_page: https://www.matik.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matik\naid: matik\nurl: https://www.matik.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: engage in any unlawful or fraudulent activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/matik/eligibility/matik-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Matik's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Content Automation
- Presentations
- Documents
- Data-Driven Content
- Sales Enablement
- Customer Success
- Revenue Operations
- Artificial Intelligence
- MCP
---
