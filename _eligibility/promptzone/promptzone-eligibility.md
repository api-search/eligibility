---
api_specs:
- filename: promptzone-openapi.json
  format: json
  label: Promptzone API
  slug: promptzone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/promptzone/openapi/promptzone-openapi.json
claim_count: 2
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
  - summary: Promotional or backlink content
    text: Users must make a good-faith effort to share content that is on-topic, of high-quality, and is not designed primarily for the purposes of promotion or creating backlinks.
  - summary: Affiliate link disclosure
    text: If a post contains affiliate links, that fact must be clearly disclosed.
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
name: Promptzone
provenance_date: '2026-11-10'
provider_name: Promptzone
provider_slug: promptzone
slug: promptzone-eligibility
source_date: '2026-11-10'
source_filename: promptzone-eligibility.yml
source_heading: Eligibility
source_page: https://www.promptzone.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Promptzone\naid: promptzone\nurl: https://www.promptzone.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Promotional or backlink content\n  text: Users must make a good-faith effort to share content that is on-topic, of high-quality, and is not designed\n    primarily for the purposes of promotion or creating backlinks.\n- summary: Affiliate link disclosure\n  text: If a post contains affiliate links, that fact must be clearly disclosed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/promptzone/eligibility/promptzone-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Promptzone's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Community
- Prompts
- Tools
- Resources
---
