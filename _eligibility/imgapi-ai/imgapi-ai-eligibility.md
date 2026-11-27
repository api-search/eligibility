---
api_specs:
- filename: imgapi-ai-openapi-generated.yml
  format: yaml
  label: ImgAPI API
  slug: imgapi-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgapi-ai/openapi/_ae-authored/imgapi-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for a business, team or organization, you confirm that you are authorized and will ensure its compliance with these terms.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must have the legal capacity required for your use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ImgAPI
provenance_date: '2026-11-09'
provider_name: ImgAPI
provider_slug: imgapi-ai
slug: imgapi-ai-eligibility
source_date: '2026-11-09'
source_filename: imgapi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://imgapi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ImgAPI\naid: imgapi-ai\nurl: https://imgapi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for a business, team or organization, you confirm that you are authorized and will ensure its\n    compliance with these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must have the legal capacity required for your use.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imgapi-ai/eligibility/imgapi-ai-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from ImgAPI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Image to Image
- Model Comparison
---
