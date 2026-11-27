---
api_specs:
- filename: substructure-openapi-generated.yml
  format: yaml
  label: Substructure API
  slug: substructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/substructure/openapi/_ae-authored/substructure-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be old enough to enter a contract where you live, and at least 16.
    value: '16'
  restricted_uses:
  - summary: Illegal or unlawful content
    text: upload content you have no right to, or that is unlawful where you operate
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
name: Substructure
provenance_date: '2026-11-10'
provider_name: Substructure
provider_slug: substructure
slug: substructure-eligibility
source_date: '2026-11-10'
source_filename: substructure-eligibility.yml
source_heading: Eligibility
source_page: https://substructure.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Substructure\naid: substructure\nurl: https://substructure.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful content\n  text: upload content you have no right to, or that is unlawful where you operate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be old enough to enter a contract where you live, and at least 16.\n"
source_yaml_url: https://artifacts.apis.io/substructure/eligibility/substructure-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Substructure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Cloud-Native
- Automation
---
