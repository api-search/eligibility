---
api_specs:
- filename: blockreq-com-build-openapi-generated.yml
  format: yaml
  label: BlockReq build API
  slug: build-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockreq-com/openapi/_ae-authored/blockreq-com-build-openapi-generated.yml
- filename: blockreq-com-getting-started-openapi-generated.yml
  format: yaml
  label: BlockReq Getting Started API
  slug: getting-started-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockreq-com/openapi/_ae-authored/blockreq-com-getting-started-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to enter a binding contract where you live.
    type: individual
  - text: If you use BlockReq for an organization, you agree on its behalf.
    type: business
  minimum_age:
    text: You must be old enough to enter a binding contract where you live.
    value: null
  restricted_uses:
  - summary: Sanctions and unlawful use
    text: 'You may not: break the law or help others do so, including sanctions laws'
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
name: BlockReq
provenance_date: '2026-11-09'
provider_name: BlockReq
provider_slug: blockreq-com
slug: blockreq-com-eligibility
source_date: '2026-11-09'
source_filename: blockreq-com-eligibility.yml
source_heading: Eligibility
source_page: https://blockreq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlockReq\naid: blockreq-com\nurl: https://blockreq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to enter a binding contract where you live.\n- type: business\n  text: If you use BlockReq for an organization, you agree on its behalf.\nrestricted_uses:\n- summary: Sanctions and unlawful use\n  text: 'You may not: break the law or help others do so, including sanctions laws'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must\
  \ be old enough to enter a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/blockreq-com/eligibility/blockreq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BlockReq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- RPC
- EVM
- Infrastructure
- Developer Tools
---
