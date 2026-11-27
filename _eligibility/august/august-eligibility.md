---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: '*Note: Our smart locks and app are for use in the US and Canada only.'
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
name: August
provenance_date: '2026-11-09'
provider_name: August
provider_slug: august
slug: august-eligibility
source_date: '2026-11-09'
source_filename: august-eligibility.yml
source_heading: Eligibility
source_page: https://august.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: August\naid: august\nurl: https://august.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: '*Note: Our smart locks and app are for use in the US and Canada only.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/august/eligibility/august-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from August's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Smart Home
- Smart Lock
- IoT
- Home Security
- Access Control
- Agentic Commerce
- MCP
---
