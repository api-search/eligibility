---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you confirm that you have authority to accept these Terms for it, and “you” includes that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Special-category data collection
    text: collect health, payment card, government identification, or other information subject to special regulatory or security requirements, unless we have agreed to it in writing
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
name: Cloche
provenance_date: '2026-11-09'
provider_name: Cloche
provider_slug: cloche-dev
slug: cloche-dev-eligibility
source_date: '2026-11-09'
source_filename: cloche-dev-eligibility.yml
source_heading: Eligibility
source_page: https://cloche.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloche\naid: cloche-dev\nurl: https://cloche.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you confirm that you have authority to accept these\n    Terms for it, and “you” includes that organization.\nrestricted_uses:\n- summary: Special-category data collection\n  text: collect health, payment card, government identification, or other information subject to special regulatory\n    or security\
  \ requirements, unless we have agreed to it in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cloche-dev/eligibility/cloche-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cloche's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- AI Apps
- Governance
- Low Code
- Internal Tools
- Agents
---
