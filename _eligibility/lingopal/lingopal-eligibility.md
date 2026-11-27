---
api_specs:
- filename: lingopal-jobs-api-openapi.yml
  format: yaml
  label: Lingopal Jobs API
  slug: lingopal-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-jobs-api-openapi.yml
- filename: lingopal-languages-api-openapi.yml
  format: yaml
  label: Lingopal Languages API
  slug: lingopal-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-languages-api-openapi.yml
- filename: lingopal-job-outputs-api-openapi.yml
  format: yaml
  label: Lingopal Job Outputs API
  slug: lingopal-job-outputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-job-outputs-api-openapi.yml
- filename: lingopal-job-registration-api-openapi.yml
  format: yaml
  label: Lingopal Job Registration API
  slug: lingopal-job-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-job-registration-api-openapi.yml
- filename: lingopal-job-workflows-api-openapi.yml
  format: yaml
  label: Lingopal Job Workflows API
  slug: lingopal-job-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-job-workflows-api-openapi.yml
- filename: lingopal-storage-api-openapi.yml
  format: yaml
  label: Lingopal Storage API
  slug: lingopal-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-storage-api-openapi.yml
- filename: lingopal-text-translation-api-openapi.yml
  format: yaml
  label: Lingopal Text Translation API
  slug: lingopal-text-translation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingopal/openapi/lingopal-text-translation-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Refunds do not apply to business customers unless otherwise agreed in writing.
    type: business
  minimum_age:
    text: The platform is intended for users who are at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You must not use the platform in ways that violate law, infringe the rights of others, impersonate another person or entity, expose minors to harm, create offensive or fraudulent content, or interfere with the platform's operation or security.
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
name: Lingopal
provenance_date: '2026-11-09'
provider_name: Lingopal
provider_slug: lingopal
slug: lingopal-eligibility
source_date: '2026-11-09'
source_filename: lingopal-eligibility.yml
source_heading: Eligibility
source_page: https://lingopal.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lingopal\naid: lingopal\nurl: https://lingopal.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Refunds do not apply to business customers unless otherwise agreed in writing.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You must not use the platform in ways that violate law, infringe the rights of others, impersonate another\n    person or entity, expose minors to harm, create offensive or fraudulent content, or interfere with the platform's\n    operation or security.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The platform is intended for users who are at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/lingopal/eligibility/lingopal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lingopal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Frontier Tech
- Artificial Intelligence
- Translation
- Localization
- Speech
- Media
- Broadcasting
- Video
- Subtitles
- Voice Cloning
---
