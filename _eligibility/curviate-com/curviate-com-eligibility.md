---
api_specs:
- filename: curviate-com-openapi.json
  format: json
  label: Curviate API
  slug: curviate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curviate-com/openapi/curviate-com-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Curviate is provided for business and professional use. It is not intended for personal, family, or household use
    type: business
  minimum_age:
    text: You must be at least 18 and have the authority to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: No personal or household use
    text: It is not intended for personal, family, or household use
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
name: curviate-com
provenance_date: '2026-11-09'
provider_name: curviate-com
provider_slug: curviate-com
slug: curviate-com-eligibility
source_date: '2026-11-09'
source_filename: curviate-com-eligibility.yml
source_heading: Eligibility
source_page: https://curviate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: curviate-com\naid: curviate-com\nurl: https://curviate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Curviate is provided for business and professional use. It is not intended for personal, family, or household\n    use\nrestricted_uses:\n- summary: No personal or household use\n  text: It is not intended for personal, family, or household use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and have the authority to enter into\
  \ this agreement.\n"
source_yaml_url: https://artifacts.apis.io/curviate-com/eligibility/curviate-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from curviate-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LinkedIn
- Automation
- Agents
---
