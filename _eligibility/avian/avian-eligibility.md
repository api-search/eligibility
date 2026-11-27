---
api_specs:
- filename: avian-openapi-generated.yml
  format: yaml
  label: Avian.io API
  slug: avian-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avian/openapi/_ae-authored/avian-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account and use the Services.
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account and use the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Generate content that is illegal, harmful, threatening, abusive, harassing, defamatory, or otherwise objectionable.
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
name: Avian.io
provenance_date: '2026-11-09'
provider_name: Avian.io
provider_slug: avian
slug: avian-eligibility
source_date: '2026-11-09'
source_filename: avian-eligibility.yml
source_heading: Eligibility
source_page: https://avian.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avian.io\naid: avian\nurl: https://avian.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account and use the Services.\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Generate content that is illegal, harmful, threatening, abusive, harassing, defamatory, or otherwise objectionable.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/avian/eligibility/avian-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Avian.io's own page on 2026-11-09.
synthetic: false
tags:
- Inference
- Compute
- OpenAI Compatibility
- GPU Compute
- Enterprise Security
---
