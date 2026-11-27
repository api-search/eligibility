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
  - summary: Serving clients without paid plan
    text: Using it to serve clients, or in a product or service you provide to others, needs a paid plan (the C4C API Client plan or C4C Private client updates).
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
name: Claude for Compliance
provenance_date: '2026-11-09'
provider_name: Claude for Compliance
provider_slug: claudeforcompliance-com
slug: claudeforcompliance-com-eligibility
source_date: '2026-11-09'
source_filename: claudeforcompliance-com-eligibility.yml
source_heading: Eligibility
source_page: https://claudeforcompliance.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claude for Compliance\naid: claudeforcompliance-com\nurl: https://claudeforcompliance.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Serving clients without paid plan\n  text: Using it to serve clients, or in a product or service you provide to others, needs a paid plan (the C4C\n    API Client plan or C4C Private client updates).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/claudeforcompliance-com/eligibility/claudeforcompliance-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Claude for Compliance's own page on 2026-11-09.
synthetic: false
tags:
- Mortgage Compliance
- Compliance API
- AI Governance
---
