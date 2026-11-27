---
api_specs:
- filename: bedrocktap-com-openapi.yml
  format: yaml
  label: BedrockTap API
  slug: bedrocktap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bedrocktap-com/openapi/bedrocktap-com-openapi.yml
claim_count: 2
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
  - summary: Excessive traffic
    text: Excessive traffic will be rate-limited or blocked.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The free allowance is granted on sign-in and costs nothing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BedrockTap
provenance_date: '2026-11-09'
provider_name: BedrockTap
provider_slug: bedrocktap-com
slug: bedrocktap-com-eligibility
source_date: '2026-11-09'
source_filename: bedrocktap-com-eligibility.yml
source_heading: Eligibility
source_page: https://bedrocktap.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BedrockTap\naid: bedrocktap-com\nurl: https://bedrocktap.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Excessive traffic\n  text: Excessive traffic will be rate-limited or blocked.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The free allowance is granted on sign-in and costs nothing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bedrocktap-com/eligibility/bedrocktap-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BedrockTap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- Data Aggregation
- Marketing
- Analytics
---
