---
api_specs:
- filename: clearpolicy-app-api-openapi.json
  format: json
  label: ClearPolicy API API
  slug: clearpolicy-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearpolicy-app/openapi/_original/clearpolicy-app-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use ClearPolicy, you must: Be authorized to act on behalf of your organization'
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Documents without distribution authority
    text: Use the service to collect signatures on documents you don't have authority to distribute
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
name: ClearPolicy
provenance_date: '2026-11-09'
provider_name: ClearPolicy
provider_slug: clearpolicy-app
slug: clearpolicy-app-eligibility
source_date: '2026-11-09'
source_filename: clearpolicy-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearpolicy.app/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearPolicy\naid: clearpolicy-app\nurl: https://www.clearpolicy.app/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 'To use ClearPolicy, you must: Be authorized to act on behalf of your organization'\nrestricted_uses:\n- summary: Documents without distribution authority\n  text: Use the service to collect signatures on documents you don't have authority to distribute\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearpolicy-app/eligibility/clearpolicy-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ClearPolicy's own page on 2026-11-09.
synthetic: false
tags:
- Policy
- E-Signature
- Software-as-a-Service
- Small Business
- Non-Profit
---
