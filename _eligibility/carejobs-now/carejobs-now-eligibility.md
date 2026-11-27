---
api_specs:
- filename: carejobs-now-pay-api-openapi.yml
  format: yaml
  label: CareJobs.Now Pay API
  slug: carejobs-now-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carejobs-now/openapi/carejobs-now-pay-api-openapi.yml
- filename: carejobs-now-roles-api-openapi.yml
  format: yaml
  label: CareJobs.Now Roles API
  slug: carejobs-now-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carejobs-now/openapi/carejobs-now-roles-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You may use it only if you meet the minimum age required to consent to the processing of your personal data in your country, or the age of majority where that is higher.
    value: null
  restricted_uses:
  - summary: Competing product or other prohibited purposes
    text: use the Service to build a competing product
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
name: CareJobs.Now
provenance_date: '2026-11-09'
provider_name: CareJobs.Now
provider_slug: carejobs-now
slug: carejobs-now-eligibility
source_date: '2026-11-09'
source_filename: carejobs-now-eligibility.yml
source_heading: Eligibility
source_page: https://carejobs.now/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CareJobs.Now\naid: carejobs-now\nurl: https://carejobs.now/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that entity to these Terms\nrestricted_uses:\n- summary: Competing product or other prohibited purposes\n  text: use the Service to build a competing product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may use it only if\
  \ you meet the minimum age required to consent to the processing of your personal data\n    in your country, or the age of majority where that is higher.\n"
source_yaml_url: https://artifacts.apis.io/carejobs-now/eligibility/carejobs-now-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CareJobs.Now's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Job
- Data
- Transparency
- US
---
