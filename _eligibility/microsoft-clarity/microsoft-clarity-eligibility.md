---
api_specs:
- filename: microsoft-clarity-data-export-api-openapi.yml
  format: yaml
  label: Microsoft Clarity Data Export API
  slug: microsoft-clarity-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-clarity/openapi/microsoft-clarity-data-export-api-openapi.yml
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
  - summary: Unlawful or prohibited use
    text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Microsoft Clarity
provenance_date: '2026-11-10'
provider_name: Microsoft Clarity
provider_slug: microsoft-clarity
slug: microsoft-clarity-eligibility
source_date: '2026-11-10'
source_filename: microsoft-clarity-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microsoft Clarity\naid: microsoft-clarity\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful\n    or prohibited by these terms, conditions, and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-clarity/eligibility/microsoft-clarity-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Microsoft Clarity's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Heatmaps
- Session Recording
- Web Analytics
- Behavioral Analytics
- Product Analytics
- User Experience
- Data Export
- MCP
---
