---
api_specs:
- filename: avacast-jp-openapi-generated.yml
  format: yaml
  label: avacast-jp API
  slug: avacast-jp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avacast-jp/openapi/_ae-authored/avacast-jp-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本サービスを利用する法人・団体・個人
    type: business
  - text: 本サービスを利用する法人・団体・個人
    type: nonprofit
  - text: 本サービスを利用する法人・団体・個人
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or public-order-violating use
    text: 法令または公序良俗に違反する行為、およびそのおそれのある行為
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
name: avacast-jp
provenance_date: '2026-11-09'
provider_name: avacast-jp
provider_slug: avacast-jp
slug: avacast-jp-eligibility
source_date: '2026-11-09'
source_filename: avacast-jp-eligibility.yml
source_heading: Eligibility
source_page: https://avacast.jp/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: avacast-jp\naid: avacast-jp\nurl: https://avacast.jp/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 本サービスを利用する法人・団体・個人\n- type: nonprofit\n  text: 本サービスを利用する法人・団体・個人\n- type: individual\n  text: 本サービスを利用する法人・団体・個人\nrestricted_uses:\n- summary: Unlawful or public-order-violating use\n  text: 法令または公序良俗に違反する行為、およびそのおそれのある行為\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avacast-jp/eligibility/avacast-jp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from avacast-jp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Avatars
- Real-Time
- Japan
---
