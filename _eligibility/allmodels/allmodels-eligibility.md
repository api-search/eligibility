---
api_specs:
- filename: allmodels-account-api-openapi.yml
  format: yaml
  label: Allmodels Account API
  slug: allmodels-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-account-api-openapi.yml
- filename: allmodels-allmodels-api-api-openapi.yml
  format: yaml
  label: Allmodels Allmodels API
  slug: allmodels-allmodels-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-allmodels-api-api-openapi.yml
- filename: allmodels-custom-voices-api-openapi.yml
  format: yaml
  label: Allmodels Custom Voices API
  slug: allmodels-custom-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-custom-voices-api-openapi.yml
- filename: allmodels-el-api-openapi.yml
  format: yaml
  label: Allmodels El API
  slug: allmodels-el-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-el-api-openapi.yml
- filename: allmodels-health-api-openapi.yml
  format: yaml
  label: Allmodels Health API
  slug: allmodels-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-health-api-openapi.yml
- filename: allmodels-oai-api-openapi.yml
  format: yaml
  label: Allmodels Oai API
  slug: allmodels-oai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-oai-api-openapi.yml
- filename: allmodels-realtime-api-openapi.yml
  format: yaml
  label: Allmodels Realtime API
  slug: allmodels-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-realtime-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a business or other organization, you confirm that you have authority to accept these terms for that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: No sexual content involving minors
    text: sexualizes or exploits minors in any way
  - summary: No deceptive impersonation or deepfakes
    text: impersonates a real person or organization to deceive, defraud, or harm others, including deepfake calls, messages, or recordings
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
name: Allmodels
provenance_date: '2026-11-09'
provider_name: Allmodels
provider_slug: allmodels
slug: allmodels-eligibility
source_date: '2026-11-09'
source_filename: allmodels-eligibility.yml
source_heading: Eligibility
source_page: https://allmodels.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allmodels\naid: allmodels\nurl: https://allmodels.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a business or other organization, you confirm that you have authority to accept\n    these terms for that organization.\nrestricted_uses:\n- summary: No sexual content involving minors\n  text: sexualizes or exploits minors in any way\n- summary: No deceptive impersonation or deepfakes\n  text: impersonates a real person or organization to deceive, defraud, or harm others, including deepfake calls,\n \
  \   messages, or recordings\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/allmodels/eligibility/allmodels-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Allmodels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Text-to-Speech
- Speech-to-Text
- Real-Time
---
