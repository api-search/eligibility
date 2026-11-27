---
api_specs:
- filename: aidataparser-com-openapi-generated.yml
  format: yaml
  label: AIDataParser API
  slug: aidataparser-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aidataparser-com/openapi/_ae-authored/aidataparser-com-openapi-generated.yml
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
  - summary: Illegal or unauthorized content
    text: Don't use the service to process content that is illegal, infringing, or that you don't have authorization to share with a third-party AI provider.
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
name: AIDataParser
provenance_date: '2026-11-09'
provider_name: AIDataParser
provider_slug: aidataparser-com
slug: aidataparser-com-eligibility
source_date: '2026-11-09'
source_filename: aidataparser-com-eligibility.yml
source_heading: Eligibility
source_page: https://aidataparser.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIDataParser\naid: aidataparser-com\nurl: https://aidataparser.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized content\n  text: Don't use the service to process content that is illegal, infringing, or that you don't have authorization\n    to share with a third-party AI provider.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aidataparser-com/eligibility/aidataparser-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AIDataParser's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Extraction
- JSON
- PDF
- Image Processing
---
