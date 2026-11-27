---
api_specs:
- filename: lightricks-asyncvideogeneration-api-openapi.yml
  format: yaml
  label: Lightricks Async Video Generation API
  slug: lightricks-asyncvideogeneration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-asyncvideogeneration-api-openapi.yml
- filename: lightricks-upload-api-openapi.yml
  format: yaml
  label: Lightricks Upload API
  slug: lightricks-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-upload-api-openapi.yml
- filename: lightricks-video-generation-api-openapi.yml
  format: yaml
  label: Lightricks Video Generation API
  slug: lightricks-video-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-video-generation-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of an entity (such as your employer), you represent that you have full authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: Children under the age of thirteen (13) are not permitted to use any of the Services.
    value: '13'
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
name: Lightricks
provenance_date: '2026-11-09'
provider_name: Lightricks
provider_slug: lightricks
slug: lightricks-eligibility
source_date: '2026-11-09'
source_filename: lightricks-eligibility.yml
source_heading: Eligibility
source_page: https://static.lightricks.com/legal/terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightricks\naid: lightricks\nurl: https://static.lightricks.com/legal/terms-of-use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of an entity (such as your employer), you represent that\n    you have full authority to bind such entity to this Agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children under the age of thirteen (13) are not permitted to use any of\
  \ the Services.\n"
source_yaml_url: https://artifacts.apis.io/lightricks/eligibility/lightricks-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Lightricks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Artificial Intelligence
- Generative AI
- Video
- Video Generation
- Media
- Machine Learning
- Creative Tools
---
