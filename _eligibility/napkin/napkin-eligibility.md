---
api_specs:
- filename: napkin-visuals-api-openapi.yml
  format: yaml
  label: Napkin Visuals API
  slug: napkin-visuals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/napkin/openapi/napkin-visuals-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU REPRESENT THAT (1) YOU HAVE READ, UNDERSTAND, AND AGREE TO BE BOUND BY THE TERMS
    type: individual
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: No prohibited content
    text: Your Content may not contain nudity, violence, sexually explicit, or offensive subject matter as determined by Napkin in its sole discretion.
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
name: Napkin
provenance_date: '2026-11-10'
provider_name: Napkin
provider_slug: napkin
slug: napkin-eligibility
source_date: '2026-11-10'
source_filename: napkin-eligibility.yml
source_heading: Eligibility
source_page: https://www.napkin.ai/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Napkin\naid: napkin\nurl: https://www.napkin.ai/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU REPRESENT THAT (1) YOU HAVE READ, UNDERSTAND, AND AGREE TO BE BOUND BY THE TERMS\nrestricted_uses:\n- summary: No prohibited content\n  text: Your Content may not contain nudity, violence, sexually explicit, or offensive subject matter as determined\n    by Napkin in its sole discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You represent that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/napkin/eligibility/napkin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Napkin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Visualization
- Diagramming
- Infographics
- Presentations
- Content Generation
- Developer API
- Design
---
