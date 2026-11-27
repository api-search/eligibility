---
api_specs:
- filename: aicamp-openapi.json
  format: json
  label: AICamp API
  slug: aicamp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicamp/openapi/aicamp-openapi.json
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
  - summary: Unlawful purposes
    text: Will not be for any unlawful purposes or in furtherance of illegal activities
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
name: AICamp
provenance_date: '2026-11-09'
provider_name: AICamp
provider_slug: aicamp
slug: aicamp-eligibility
source_date: '2026-11-09'
source_filename: aicamp-eligibility.yml
source_heading: Eligibility
source_page: https://aicamp.so/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AICamp\naid: aicamp\nurl: https://aicamp.so/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Will not be for any unlawful purposes or in furtherance of illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aicamp/eligibility/aicamp-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AICamp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Collaboration
- Workspace
- Team
- Platform
---
