---
api_specs:
- filename: spoken-md-transcripts-api-openapi.yml
  format: yaml
  label: Podcast Transcripts API
  slug: podcast-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/spoken-md-transcripts-api-openapi.yml
- filename: spoken-md-well-known-openapi.json
  format: json
  label: Podcast Transcripts API .well-known API
  slug: podcast-transcripts-api-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/_original/spoken-md-well-known-openapi.json
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
  restricted_uses:
  - summary: Unauthorized use of transcripts
    text: Redistribute raw transcripts as a standalone dataset or corpus, resell API access or credits, or use transcripts fetched from Spoken to build or train a competing transcript or podcast-data API.
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
name: spoken-md
provenance_date: '2026-11-10'
provider_name: spoken-md
provider_slug: spoken-md
slug: spoken-md-eligibility
source_date: '2026-11-10'
source_filename: spoken-md-eligibility.yml
source_heading: Eligibility
source_page: https://spoken.md/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: spoken-md\naid: spoken-md\nurl: https://spoken.md/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized use of transcripts\n  text: Redistribute raw transcripts as a standalone dataset or corpus, resell API access or credits, or use transcripts\n    fetched from Spoken to build or train a competing transcript or podcast-data API.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spoken-md/eligibility/spoken-md-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from spoken-md's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Transcripts
- Markdown
- Artificial Intelligence
---
