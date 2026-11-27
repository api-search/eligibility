---
api_specs:
- filename: mochify-app-generate-api-openapi.yml
  format: yaml
  label: mochify-app Generate API
  slug: mochify-app-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mochify-app/openapi/mochify-app-generate-api-openapi.yml
- filename: mochify-app-image-api-openapi.yml
  format: yaml
  label: mochify-app Image API
  slug: mochify-app-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mochify-app/openapi/mochify-app-image-api-openapi.yml
- filename: mochify-app-meta-api-openapi.yml
  format: yaml
  label: mochify-app Meta API
  slug: mochify-app-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mochify-app/openapi/mochify-app-meta-api-openapi.yml
- filename: mochify-app-pdf-api-openapi.yml
  format: yaml
  label: mochify-app PDF API
  slug: mochify-app-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mochify-app/openapi/mochify-app-pdf-api-openapi.yml
- filename: mochify-app-upload-api-openapi.yml
  format: yaml
  label: mochify-app Upload API
  slug: mochify-app-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mochify-app/openapi/mochify-app-upload-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use this Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use this Website.
    value: '18'
  restricted_uses:
  - summary: Uploading confidential, illegal or infringing content
    text: You may not upload to, distribute or otherwise publish through the Website any Content that (i) is confidential, proprietary, false, fraudulent, libellous, defamatory, obscene, threatening, invasive of privacy or publicity rights, infringing on intellectual property rights, abusive, illegal or otherwise objectionable;
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
name: mochify-app
provenance_date: '2026-11-10'
provider_name: mochify-app
provider_slug: mochify-app
slug: mochify-app-eligibility
source_date: '2026-11-10'
source_filename: mochify-app-eligibility.yml
source_heading: Eligibility
source_page: https://mochify.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mochify-app\naid: mochify-app\nurl: https://mochify.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use this Website.\nrestricted_uses:\n- summary: Uploading confidential, illegal or infringing content\n  text: You may not upload to, distribute or otherwise publish through the Website any Content that (i) is confidential,\n    proprietary, false, fraudulent, libellous, defamatory, obscene, threatening, invasive of privacy or publicity\n    rights, infringing on intellectual property\
  \ rights, abusive, illegal or otherwise objectionable;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/mochify-app/eligibility/mochify-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from mochify-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Image Compression
- Video Compression
- PDF compression
- Artificial Intelligence
- PrivacyFocused
---
