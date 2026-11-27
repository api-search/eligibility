---
api_specs:
- filename: cision-mentions-api-openapi.yml
  format: yaml
  label: Cision Mentions API
  slug: cision-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cision/openapi/cision-mentions-api-openapi.yml
- filename: cision-stream-api-openapi.yml
  format: yaml
  label: Cision Stream API
  slug: cision-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cision/openapi/cision-stream-api-openapi.yml
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
  - summary: Sanctions and export control compliance
    text: is identified on, or owned or controlled by or acting on behalf of a person identified on, any Canadian, U.S., UK, EU, or other applicable prohibited party list
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
name: Cision
provenance_date: '2026-11-09'
provider_name: Cision
provider_slug: cision
slug: cision-eligibility
source_date: '2026-11-09'
source_filename: cision-eligibility.yml
source_heading: Eligibility
source_page: https://www.cision.com/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cision\naid: cision\nurl: https://www.cision.com/legal/msa/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctions and export control compliance\n  text: is identified on, or owned or controlled by or acting on behalf of a person identified on, any Canadian,\n    U.S., UK, EU, or other applicable prohibited party list\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cision/eligibility/cision-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cision's own page on 2026-11-09.
synthetic: false
tags:
- PR Software
- Public Relations
- Earned Media
- Media Monitoring
- Press Release Distribution
- Media Database
- Influencer Identification
- Analytics
---
