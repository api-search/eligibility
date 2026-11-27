---
api_specs:
- filename: seedance2ai-downloads-api-openapi.yml
  format: yaml
  label: Seedance2AI (SixBryan LLC) Downloads API
  slug: seedance2ai-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seedance2ai/openapi/seedance2ai-downloads-api-openapi.yml
- filename: seedance2ai-image-api-openapi.yml
  format: yaml
  label: Seedance2AI (SixBryan LLC) Image API
  slug: seedance2ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seedance2ai/openapi/seedance2ai-image-api-openapi.yml
- filename: seedance2ai-tasks-api-openapi.yml
  format: yaml
  label: Seedance2AI (SixBryan LLC) Tasks API
  slug: seedance2ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seedance2ai/openapi/seedance2ai-tasks-api-openapi.yml
- filename: seedance2ai-video-api-openapi.yml
  format: yaml
  label: Seedance2AI (SixBryan LLC) Video API
  slug: seedance2ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seedance2ai/openapi/seedance2ai-video-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This service is only available to users 18 years of age or older
    type: individual
  minimum_age:
    text: This service is only available to users 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: 'The following content is strictly prohibited:'
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
name: Seedance2AI (SixBryan LLC)
provenance_date: '2026-11-10'
provider_name: Seedance2AI (SixBryan LLC)
provider_slug: seedance2ai
slug: seedance2ai-eligibility
source_date: '2026-11-10'
source_filename: seedance2ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.seedance2ai.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seedance2AI (SixBryan LLC)\naid: seedance2ai\nurl: https://www.seedance2ai.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This service is only available to users 18 years of age or older\nrestricted_uses:\n- summary: Prohibited content\n  text: 'The following content is strictly prohibited:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This service is only available to users 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/seedance2ai/eligibility/seedance2ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Seedance2AI (SixBryan LLC)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Generation
- Multi-Modal
- Developer Platform
---
