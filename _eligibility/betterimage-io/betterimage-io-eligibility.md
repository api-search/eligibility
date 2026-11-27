---
api_specs:
- filename: betterimage-io-openapi-generated.yml
  format: yaml
  label: BetterImage.io API
  slug: betterimage-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterimage-io/openapi/_ae-authored/betterimage-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer in the EU, EEA or UK you normally have 14 days to withdraw from an online purchase.
  entity_types:
  - text: One account per person.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Infringing, defamatory, harassing or unlawful content
    text: you must not create content that infringes someone's rights, defames or harasses a person, or breaks the law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Use a real email address you control and confirm it from the link we send.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BetterImage.io
provenance_date: '2026-11-09'
provider_name: BetterImage.io
provider_slug: betterimage-io
slug: betterimage-io-eligibility
source_date: '2026-11-09'
source_filename: betterimage-io-eligibility.yml
source_heading: Eligibility
source_page: https://betterimage.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterImage.io\naid: betterimage-io\nurl: https://betterimage.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer in the EU, EEA or UK you normally have 14 days to withdraw from an online purchase.\nentity_types:\n- type: individual\n  text: One account per person.\nrestricted_uses:\n- summary: Infringing, defamatory, harassing or unlawful content\n  text: you must not create content that infringes someone's rights, defames or harasses a person, or breaks the\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Use a real\
  \ email address you control and confirm it from the link we send.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/betterimage-io/eligibility/betterimage-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from BetterImage.io's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Image Generation
---
