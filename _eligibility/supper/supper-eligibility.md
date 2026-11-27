---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Web Site is directed to users in the United States. We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: not to export or re-export any of the Content to countries or persons prohibited under the export control laws
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
name: Supper
provenance_date: '2026-11-10'
provider_name: Supper
provider_slug: supper
slug: supper-eligibility
source_date: '2026-11-10'
source_filename: supper-eligibility.yml
source_heading: Eligibility
source_page: https://www.supper.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supper\naid: supper\nurl: https://www.supper.co/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Web Site is directed to users in the United States. We make no claims concerning whether the Content\n    may be downloaded, viewed, or be appropriate for use outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: not to export or re-export any of the Content to countries or persons prohibited under the export control\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/supper/eligibility/supper-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Supper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Analytics
- Artificial Intelligence
- MCP
- Business Intelligence
- Semantic Layer
- Data Agent
---
