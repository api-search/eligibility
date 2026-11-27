---
api_specs:
- filename: vyond-content-generation-api-openapi.yml
  format: yaml
  label: Vyond Content Generation API
  slug: vyond-content-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-content-generation-api-openapi.yml
- filename: vyond-parameter-api-openapi.yml
  format: yaml
  label: Vyond Parameter API
  slug: vyond-parameter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-parameter-api-openapi.yml
- filename: vyond-scim-api-openapi.yml
  format: yaml
  label: Vyond SCIM API
  slug: vyond-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-scim-api-openapi.yml
- filename: vyond-turbo-api-openapi.yml
  format: yaml
  label: Vyond Turbo API
  slug: vyond-turbo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-turbo-api-openapi.yml
- filename: vyond-user-api-openapi.yml
  format: yaml
  label: Vyond User API
  slug: vyond-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-user-api-openapi.yml
- filename: vyond-video-api-openapi.yml
  format: yaml
  label: Vyond Video API
  slug: vyond-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-video-api-openapi.yml
- filename: vyond-video-export-api-openapi.yml
  format: yaml
  label: Vyond Video Export API
  slug: vyond-video-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-video-export-api-openapi.yml
- filename: vyond-webhook-api-openapi.yml
  format: yaml
  label: Vyond Webhook API
  slug: vyond-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vyond/openapi/vyond-webhook-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity you represent (e.g., your employer)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: Customer may not export or re-export Videos, the Vyond Assets, or the SaaS except in compliance with the United States Export Administration Act and the related rules and regulations
  - summary: Shutterstock asset restrictions
    text: Customer shall not use any Shutterstock Assets (a) together with pornographic, defamatory, or unlawful content
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
name: Vyond
provenance_date: '2026-11-10'
provider_name: Vyond
provider_slug: vyond
slug: vyond-eligibility
source_date: '2026-11-10'
source_filename: vyond-eligibility.yml
source_heading: Eligibility
source_page: https://www.vyond.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vyond\naid: vyond\nurl: https://www.vyond.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity you represent (e.g., your employer)\nrestricted_uses:\n- summary: Export compliance\n  text: Customer may not export or re-export Videos, the Vyond Assets, or the SaaS except in compliance with the\n    United States Export Administration Act and the related rules and regulations\n- summary: Shutterstock asset restrictions\n  text: Customer shall not use any Shutterstock Assets (a) together with pornographic, defamatory,\
  \ or unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vyond/eligibility/vyond-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Vyond's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Animation
- Video Generation
- Artificial Intelligence
- E-Learning
- Learning and Development
- Content Generation
- SCIM
- Identity Provisioning
- Webhook
- Enterprise
- Media
---
