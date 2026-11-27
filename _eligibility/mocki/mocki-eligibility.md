---
api_specs:
- filename: mocki-openapi-generated.yml
  format: yaml
  label: Mocki API
  slug: mocki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mocki/openapi/_ae-authored/mocki-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you agree on behalf of yourself or the entity that you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: post or otherwise transmit any unlawful, harmful, threatening, abusive, harassing, defamatory, vulgar, obscene, or hateful content
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
name: Mocki
provenance_date: '2026-11-10'
provider_name: Mocki
provider_slug: mocki
slug: mocki-eligibility
source_date: '2026-11-10'
source_filename: mocki-eligibility.yml
source_heading: Eligibility
source_page: https://mocki.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mocki\naid: mocki\nurl: https://mocki.io/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you agree on behalf of yourself or the entity that you represent\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: post or otherwise transmit any unlawful, harmful, threatening, abusive, harassing, defamatory, vulgar, obscene,\n    or hateful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mocki/eligibility/mocki-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Mocki's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Mock API
- Testing
- Development
---
