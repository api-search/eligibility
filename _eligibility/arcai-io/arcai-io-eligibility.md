---
api_specs:
- filename: arcai-io-openapi-generated.yml
  format: yaml
  label: ARC AI API
  slug: arcai-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcai-io/openapi/_ae-authored/arcai-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally allowed to use the Service where you live.
    type: individual
  minimum_age:
    text: You must be at least 18 and legally allowed to use the Service where you live.
    value: '18'
  restricted_uses:
  - summary: Illegal or sanctioned use
    text: No use that breaks applicable laws or sanctions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in by connecting a wallet you control.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ARC AI
provenance_date: '2026-11-09'
provider_name: ARC AI
provider_slug: arcai-io
slug: arcai-io-eligibility
source_date: '2026-11-09'
source_filename: arcai-io-eligibility.yml
source_heading: Eligibility
source_page: https://arcai.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ARC AI\naid: arcai-io\nurl: https://arcai.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally allowed to use the Service where you live.\nrestricted_uses:\n- summary: Illegal or sanctioned use\n  text: No use that breaks applicable laws or sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in by connecting a wallet you control.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally allowed to use the Service where you live.\n"
source_yaml_url: https://artifacts.apis.io/arcai-io/eligibility/arcai-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ARC AI's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Cryptocurrency
- Artificial Intelligence
- Intelligence
- Blockchain
---
