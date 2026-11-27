---
api_specs:
- filename: nereo-api-reference-openapi-generated.yml
  format: yaml
  label: Nereo Overview API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nereo/openapi/_ae-authored/nereo-api-reference-openapi-generated.yml
- filename: nereo-core-openapi-generated.yml
  format: yaml
  label: Nereo core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nereo/openapi/_ae-authored/nereo-core-openapi-generated.yml
- filename: nereo-models-openapi-generated.yml
  format: yaml
  label: Nereo Overview API
  slug: models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nereo/openapi/_ae-authored/nereo-models-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our services.
    value: '18'
  restricted_uses:
  - summary: NSFW/sexual content prohibited
    text: Nereo prohibits the creation, upload, request, or distribution of sexual, adult, pornographic, NSFW, or sexually explicit content through our AI image, video, and creative generation services.
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
name: Nereo
provenance_date: '2026-11-10'
provider_name: Nereo
provider_slug: nereo
slug: nereo-eligibility
source_date: '2026-11-10'
source_filename: nereo-eligibility.yml
source_heading: Eligibility
source_page: https://www.nereo.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nereo\naid: nereo\nurl: https://www.nereo.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our services.\nrestricted_uses:\n- summary: NSFW/sexual content prohibited\n  text: Nereo prohibits the creation, upload, request, or distribution of sexual, adult, pornographic, NSFW, or\n    sexually explicit content through our AI image, video, and creative generation services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old to use our services.\n"
source_yaml_url: https://artifacts.apis.io/nereo/eligibility/nereo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nereo's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- Marketing
- Creator Tools
- Software-as-a-Service
---
