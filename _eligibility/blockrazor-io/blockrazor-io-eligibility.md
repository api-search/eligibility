---
api_specs:
- filename: blockrazor-io-openapi-generated.yml
  format: yaml
  label: BlockRazor API
  slug: blockrazor-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockrazor-io/openapi/_ae-authored/blockrazor-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual or legal entity using the Company's services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activities
    text: DO NOT USE THE SERVICES FOR ANY ILLEGAL ACTIVITIES OR ASSIST OTHERS IN ILLEGAL ACTIVITIES, INCLUDING BUT NOT LIMITED TO ILLEGAL GAMBLING, FRAUD, MONEY LAUNDERING, DRUG TRAFFICKING, ARMS TRAFFICKING, OR TERRORIST ACTIVITIES
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
name: BlockRazor
provenance_date: '2026-11-09'
provider_name: BlockRazor
provider_slug: blockrazor-io
slug: blockrazor-io-eligibility
source_date: '2026-11-09'
source_filename: blockrazor-io-eligibility.yml
source_heading: Eligibility
source_page: https://blockrazor.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlockRazor\naid: blockrazor-io\nurl: https://blockrazor.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: An individual or legal entity using the Company's services.\nrestricted_uses:\n- summary: Illegal activities\n  text: DO NOT USE THE SERVICES FOR ANY ILLEGAL ACTIVITIES OR ASSIST OTHERS IN ILLEGAL ACTIVITIES, INCLUDING BUT\n    NOT LIMITED TO ILLEGAL GAMBLING, FRAUD, MONEY LAUNDERING, DRUG TRAFFICKING, ARMS TRAFFICKING, OR TERRORIST ACTIVITIES\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blockrazor-io/eligibility/blockrazor-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BlockRazor's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Infrastructure
- Low Latency
- Web3
- Data Streams
- Company
---
