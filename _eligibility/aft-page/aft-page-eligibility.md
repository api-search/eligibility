---
api_specs:
- filename: aft-page-api-openapi.json
  format: json
  label: aft.page API API
  slug: aft-page-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aft-page/openapi/_original/aft-page-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Free and Personal are for individuals: use by or for a company, or a project more than one person edits, needs Team.'
    type: individual
  - text: use by or for a company, or a project more than one person edits, needs Team. Team and Enterprise are quoted in one conversation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Company or multi-editor use requires Team plan
    text: use by or for a company, or a project more than one person edits, needs Team.
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
name: aft.page
provenance_date: '2026-11-09'
provider_name: aft.page
provider_slug: aft-page
slug: aft-page-eligibility
source_date: '2026-11-09'
source_filename: aft-page-eligibility.yml
source_heading: Eligibility
source_page: https://aft.page/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aft.page\naid: aft-page\nurl: https://aft.page/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Free and Personal are for individuals: use by or for a company, or a project more than one person edits,\n    needs Team.'\n- type: business\n  text: use by or for a company, or a project more than one person edits, needs Team. Team and Enterprise are quoted\n    in one conversation.\nrestricted_uses:\n- summary: Company or multi-editor use requires Team plan\n  text: use by or for a company, or a project more than one person edits,\
  \ needs Team.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aft-page/eligibility/aft-page-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from aft.page's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Hosting
- CLI
- Deployment
- Low‑friction
---
