---
api_specs:
- filename: stoplight-versions-api-openapi.yml
  format: yaml
  label: Stoplight Versions API
  slug: stoplight-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stoplight/openapi/stoplight-versions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer agrees that the Controlled Subject Matter will not be used or transferred or otherwise exported or re-exported to countries as to which the United States maintains an embargo
  entity_types:
  - text: If you are executing this agreement on behalf of an organization, you represent that you have authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: use the Licensed Materials in connection with any high risk or strict liability activity
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
name: Stoplight
provenance_date: '2026-11-10'
provider_name: Stoplight
provider_slug: stoplight
slug: stoplight-eligibility
source_date: '2026-11-10'
source_filename: stoplight-eligibility.yml
source_heading: Eligibility
source_page: https://stoplight.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stoplight\naid: stoplight\nurl: https://stoplight.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer agrees that the Controlled Subject Matter will not be used or transferred or otherwise exported\n    or re-exported to countries as to which the United States maintains an embargo\nentity_types:\n- type: business\n  text: If you are executing this agreement on behalf of an organization, you represent that you have authority\n    to do so.\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Licensed Materials in connection with any high risk or strict\
  \ liability activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stoplight/eligibility/stoplight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Stoplight's own page on 2026-11-10.
synthetic: false
tags:
- API Design
- API Documentation
- API Governance
- AsyncAPI
- Design-First
- Developer Tools
- Linting
- Mock Servers
- OpenAPI
- SmartBear API Hub
- Style Guides
- Documentation
---
