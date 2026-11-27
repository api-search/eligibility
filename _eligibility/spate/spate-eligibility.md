---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Licensee” or “You” or “Your” means the company or other legal entity which holds a License for the Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors
    text: Except with Spate’s prior written consent, You may not access the Services or Licensed Materials if You directly compete with Spate’s business in any material way.
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
name: Spate
provenance_date: '2026-11-10'
provider_name: Spate
provider_slug: spate
slug: spate-eligibility
source_date: '2026-11-10'
source_filename: spate-eligibility.yml
source_heading: Eligibility
source_page: https://www.spate.nyc/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spate\naid: spate\nurl: https://www.spate.nyc/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Licensee” or “You” or “Your” means the company or other legal entity which holds a License for the Services.\nrestricted_uses:\n- summary: Direct competitors\n  text: Except with Spate’s prior written consent, You may not access the Services or Licensed Materials if You\n    directly compete with Spate’s business in any material way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spate/eligibility/spate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Market Intelligence
- Trend Forecasting
- Consumer Insights
- Social Listening
- Analytics
- Beauty
- MCP
- AI Agents
- Trend Data
- Consumer Packaged Goods
---
