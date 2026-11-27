---
api_specs:
- filename: clearly-sh-openapi-generated.yml
  format: yaml
  label: Clearly API
  slug: clearly-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearly-sh/openapi/_ae-authored/clearly-sh-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (16 in the EU)
    type: individual
  - text: If you're using Clearly on behalf of a company, you confirm you have authority to bind that company.
    type: business
  minimum_age:
    text: You must be at least 13 years old (16 in the EU)
    value: '13'
  restricted_uses:
  - summary: Illegal or infringing use
    text: Violate any law or third-party right (copyright, trademark, privacy, etc.)
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
name: Clearly
provenance_date: '2026-11-09'
provider_name: Clearly
provider_slug: clearly-sh
slug: clearly-sh-eligibility
source_date: '2026-11-09'
source_filename: clearly-sh-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearly.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearly\naid: clearly-sh\nurl: https://www.clearly.sh/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (16 in the EU)\n- type: business\n  text: If you're using Clearly on behalf of a company, you confirm you have authority to bind that company.\nrestricted_uses:\n- summary: Illegal or infringing use\n  text: Violate any law or third-party right (copyright, trademark, privacy, etc.)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You must be at least 13 years old (16 in the EU)\n"
source_yaml_url: https://artifacts.apis.io/clearly-sh/eligibility/clearly-sh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Clearly's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Workspace
- Design Tools
---
