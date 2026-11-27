---
api_specs:
- filename: blumify-io-openapi-generated.yml
  format: yaml
  label: blumify-io API
  slug: blumify-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blumify-io/openapi/_ae-authored/blumify-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unlimited is for one person.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use or harassment
    text: Do not use Blumify for anything unlawful, or to harass anyone.
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
name: blumify-io
provenance_date: '2026-11-09'
provider_name: blumify-io
provider_slug: blumify-io
slug: blumify-io-eligibility
source_date: '2026-11-09'
source_filename: blumify-io-eligibility.yml
source_heading: Eligibility
source_page: https://blumify.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blumify-io\naid: blumify-io\nurl: https://blumify.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unlimited is for one person.\nrestricted_uses:\n- summary: Unlawful use or harassment\n  text: Do not use Blumify for anything unlawful, or to harass anyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blumify-io/eligibility/blumify-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from blumify-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Finance
- Transcription
- Data
- Analytics
---
