---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
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
name: Omni Analytics
provenance_date: '2026-11-10'
provider_name: Omni Analytics
provider_slug: omni-analytics
slug: omni-analytics-eligibility
source_date: '2026-11-10'
source_filename: omni-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://omni.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omni Analytics\naid: omni-analytics\nurl: https://omni.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/omni-analytics/eligibility/omni-analytics-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Omni Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Analytics
- Business Intelligence
- Embedded Analytics
- Semantic Layer
- Artificial Intelligence
- Data
- MCP
---
