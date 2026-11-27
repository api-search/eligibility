---
api_specs:
- filename: neurable-core-api-openapi.yml
  format: yaml
  label: Neurable Core API
  slug: neurable-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurable/openapi/neurable-core-api-openapi.yml
- filename: neurable-oidc-api-openapi.yml
  format: yaml
  label: Neurable OIDC API
  slug: neurable-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurable/openapi/neurable-oidc-api-openapi.yml
- filename: neurable-open-api-openapi.yml
  format: yaml
  label: Neurable Open API
  slug: neurable-open-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurable/openapi/neurable-open-api-openapi.yml
- filename: neurable-protected-api-openapi.yml
  format: yaml
  label: Neurable Protected API
  slug: neurable-protected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurable/openapi/neurable-protected-api-openapi.yml
- filename: neurable-oauth-api-openapi.yml
  format: yaml
  label: Neurable O Auth API
  slug: neurable-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurable/openapi/neurable-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Website.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Neurable grants you a limited, non-exclusive, non-transferable, and revocable license to use the Website for personal, non-commercial use.
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
name: Neurable
provenance_date: '2026-11-10'
provider_name: Neurable
provider_slug: neurable
slug: neurable-eligibility
source_date: '2026-11-10'
source_filename: neurable-eligibility.yml
source_heading: Eligibility
source_page: https://www.neurable.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neurable\naid: neurable\nurl: https://www.neurable.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Website.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Neurable grants you a limited, non-exclusive, non-transferable, and revocable license to use the Website\n    for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/neurable/eligibility/neurable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Neurable's own page on 2026-11-10.
synthetic: false
tags:
- Neurotechnology
- Brain-Computer Interface
- EEG
- Neuroscience
- Wearables
- biosignals
- Hardware
- Consumer Electronics
- Research Tools
- cognitive-analytics
- Health Data
- OAuth
- Authentication
---
