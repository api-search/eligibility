---
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
  - summary: Fair use limits
    text: Do not use the service to overload the Google Ads API, to access accounts without permission, or to resell access. We may limit or suspend accounts that do.
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
name: Ads MCP
provenance_date: '2026-11-09'
provider_name: Ads MCP
provider_slug: adsmcp-dev
slug: adsmcp-dev-eligibility
source_date: '2026-11-09'
source_filename: adsmcp-dev-eligibility.yml
source_heading: Eligibility
source_page: https://adsmcp.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ads MCP\naid: adsmcp-dev\nurl: https://adsmcp.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fair use limits\n  text: Do not use the service to overload the Google Ads API, to access accounts without permission, or to resell\n    access. We may limit or suspend accounts that do.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adsmcp-dev/eligibility/adsmcp-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Ads MCP's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Google Ads
- Cost Optimization
- MCP
---
