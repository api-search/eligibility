---
api_specs:
- filename: nightfall-ai-scan-api-openapi.yml
  format: yaml
  label: Nightfall AI Scan API
  slug: nightfall-ai-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nightfall-ai/openapi/nightfall-ai-scan-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export or re-export the Services to countries as to which the United States maintains an embargo (Embargoed Countries).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No timesharing or service bureau use
    text: (4) use the Subscription Services or Software for timesharing or service bureau purposes
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
name: Nightfall AI
provenance_date: '2026-11-10'
provider_name: Nightfall AI
provider_slug: nightfall-ai
slug: nightfall-ai-eligibility
source_date: '2026-11-10'
source_filename: nightfall-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.nightfall.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nightfall AI\naid: nightfall-ai\nurl: https://www.nightfall.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export or re-export the Services to countries as to which the United States maintains an\n    embargo (Embargoed Countries).\nentity_types: []\nrestricted_uses:\n- summary: No timesharing or service bureau use\n  text: (4) use the Subscription Services or Software for timesharing or service bureau purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nightfall-ai/eligibility/nightfall-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Nightfall AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Privacy
- Sensitive Data
---
