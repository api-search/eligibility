---
api_specs:
- filename: avocadoai-co-openapi.json
  format: json
  label: Avocado AI API
  slug: avocado-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avocadoai-co/openapi/avocadoai-co-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business and professional use.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No sexual content involving minors
    text: Generate sexually explicit content involving minors, non-consensual sexual content, or any content that exploits or endangers minors
  - summary: No impersonation or undisclosed deepfakes
    text: Impersonate real people or generate misleading deepfakes without clear consent and disclosure
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
name: Avocado AI
provenance_date: '2026-11-09'
provider_name: Avocado AI
provider_slug: avocadoai-co
slug: avocadoai-co-eligibility
source_date: '2026-11-09'
source_filename: avocadoai-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.avocadoai.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avocado AI\naid: avocadoai-co\nurl: https://www.avocadoai.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use.\nrestricted_uses:\n- summary: No sexual content involving minors\n  text: Generate sexually explicit content involving minors, non-consensual sexual content, or any content that\n    exploits or endangers minors\n- summary: No impersonation or undisclosed deepfakes\n  text: Impersonate real people or generate misleading deepfakes without clear consent and disclosure\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/avocadoai-co/eligibility/avocadoai-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Avocado AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Creative
- E-Commerce
- Image Generation
- Video Generation
---
