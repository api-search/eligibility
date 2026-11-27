---
api_specs:
- filename: boardrepo-com-openapi-generated.yml
  format: yaml
  label: BoardRepo API
  slug: boardrepo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boardrepo-com/openapi/_ae-authored/boardrepo-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use BoardRepo for a company or other organization, you confirm that you can accept these terms for it.
    type: business
  minimum_age:
    text: You must be at least 13, or older if the law where you live sets a higher minimum age for agreeing to online terms
    value: '13'
  restricted_uses:
  - summary: Export-control and sanctions
    text: store or share technical data in breach of export-control or sanctions law, or use the service from a place or on behalf of a person where that law forbids it
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
name: BoardRepo
provenance_date: '2026-11-09'
provider_name: BoardRepo
provider_slug: boardrepo-com
slug: boardrepo-com-eligibility
source_date: '2026-11-09'
source_filename: boardrepo-com-eligibility.yml
source_heading: Eligibility
source_page: https://boardrepo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoardRepo\naid: boardrepo-com\nurl: https://boardrepo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use BoardRepo for a company or other organization, you confirm that you can accept these terms for\n    it.\nrestricted_uses:\n- summary: Export-control and sanctions\n  text: store or share technical data in breach of export-control or sanctions law, or use the service from a place\n    or on behalf of a person where that law forbids it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You must be at least 13, or older if the law where you live sets a higher minimum age for agreeing to online\n    terms\n"
source_yaml_url: https://artifacts.apis.io/boardrepo-com/eligibility/boardrepo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BoardRepo's own page on 2026-11-09.
synthetic: false
tags:
- Hardware
- KiCad
- Collaboration
- Open Source
- Design
---
