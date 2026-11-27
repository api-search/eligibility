---
api_specs:
- filename: sealgate-jp-openapi-generated.yml
  format: yaml
  label: sealgate-jp API
  slug: sealgate-jp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sealgate-jp/openapi/_ae-authored/sealgate-jp-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本サービスを利用する法人・団体・個人（以下「利用者」）は、本規約に同意したうえで本サービスを利用するものとします。
    type: business
  minimum_age:
    text: null
    value: null
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
name: sealgate-jp
provenance_date: '2026-11-10'
provider_name: sealgate-jp
provider_slug: sealgate-jp
slug: sealgate-jp-eligibility
source_date: '2026-11-10'
source_filename: sealgate-jp-eligibility.yml
source_heading: Eligibility
source_page: https://sealgate.jp/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sealgate-jp\naid: sealgate-jp\nurl: https://sealgate.jp/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 本サービスを利用する法人・団体・個人（以下「利用者」）は、本規約に同意したうえで本サービスを利用するものとします。\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sealgate-jp/eligibility/sealgate-jp-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from sealgate-jp's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- WebAuthn
- FIDO2
- Security
- Japan
---
