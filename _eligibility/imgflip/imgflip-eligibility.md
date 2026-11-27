---
api_specs:
- filename: imgflip-memes-api-openapi.yml
  format: yaml
  label: Imgflip Memes API
  slug: imgflip-memes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgflip/openapi/imgflip-memes-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
    type: business
  minimum_age:
    text: You must be at least 13 years of age to use our Services.
    value: '13'
  restricted_uses:
  - summary: No pornographic content on public generators
    text: Any pornographic images that are not created with the "private" setting are subject to removal.
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
name: Imgflip
provenance_date: '2026-11-09'
provider_name: Imgflip
provider_slug: imgflip
slug: imgflip-eligibility
source_date: '2026-11-09'
source_filename: imgflip-eligibility.yml
source_heading: Eligibility
source_page: https://imgflip.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imgflip\naid: imgflip\nurl: https://imgflip.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\nrestricted_uses:\n- summary: No pornographic content on public generators\n  text: Any pornographic images that are not created with the \"private\" setting are subject to removal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use our\
  \ Services.\n"
source_yaml_url: https://artifacts.apis.io/imgflip/eligibility/imgflip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Imgflip's own page on 2026-11-09.
synthetic: false
tags:
- Memes
- Image
- GIFs
- Entertainment
- Artificial Intelligence
- Image Generation
---
