---
api_specs:
- filename: compressgif-net-compressions-api-openapi.yml
  format: yaml
  label: CompressGIF Compressions API
  slug: compressgif-net-compressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compressgif-net/openapi/compressgif-net-compressions-api-openapi.yml
- filename: compressgif-net-usage-api-openapi.yml
  format: yaml
  label: CompressGIF Usage API
  slug: compressgif-net-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compressgif-net/openapi/compressgif-net-usage-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An account uses Google sign-in with a verified @gmail.com address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CompressGIF
provenance_date: '2026-11-09'
provider_name: CompressGIF
provider_slug: compressgif-net
slug: compressgif-net-eligibility
source_date: '2026-11-09'
source_filename: compressgif-net-eligibility.yml
source_heading: Eligibility
source_page: https://compressgif.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompressGIF\naid: compressgif-net\nurl: https://compressgif.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An account uses Google sign-in with a verified @gmail.com address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compressgif-net/eligibility/compressgif-net-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from CompressGIF's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GIF
- Image Compression
- Image Processing
- Animation
- Media
- MCP
- REST API
---
