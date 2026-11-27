---
api_specs:
- filename: tokenusage-dev-nerfwatch-api-openapi.yml
  format: yaml
  label: tokenusage-dev Nerfwatch API
  slug: tokenusage-dev-nerfwatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-nerfwatch-api-openapi.yml
- filename: tokenusage-dev-resets-api-openapi.yml
  format: yaml
  label: tokenusage-dev Resets API
  slug: tokenusage-dev-resets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-resets-api-openapi.yml
- filename: tokenusage-dev-resets-atom-api-openapi.yml
  format: yaml
  label: tokenusage-dev Resets.atom API
  slug: tokenusage-dev-resets-atom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-resets-atom-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Reset Alerts texts are for a US or Canadian mobile number.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Enroll only owned or authorized contacts
    text: Use only a number you own or are authorized to enroll.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Confirm the six-digit code sent to that number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tokenusage-dev
provenance_date: '2026-11-10'
provider_name: tokenusage-dev
provider_slug: tokenusage-dev
slug: tokenusage-dev-eligibility
source_date: '2026-11-10'
source_filename: tokenusage-dev-eligibility.yml
source_heading: Eligibility
source_page: https://tokenusage.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tokenusage-dev\naid: tokenusage-dev\nurl: https://tokenusage.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Reset Alerts texts are for a US or Canadian mobile number.\nentity_types: []\nrestricted_uses:\n- summary: Enroll only owned or authorized contacts\n  text: Use only a number you own or are authorized to enroll.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Confirm the six-digit code sent to that number.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tokenusage-dev/eligibility/tokenusage-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from tokenusage-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Token Usage
- Artificial Intelligence
- Analytics
- OpenAI
- Anthropic
---
