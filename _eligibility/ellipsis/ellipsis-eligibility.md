---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The company or person accepting this Agreement
    type: individual
  - text: If you accept on behalf of a company, you represent that you are authorized to bind that company.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Ellipsis
provenance_date: '2026-11-09'
provider_name: Ellipsis
provider_slug: ellipsis
slug: ellipsis-eligibility
source_date: '2026-11-09'
source_filename: ellipsis-eligibility.yml
source_heading: Eligibility
source_page: https://www.ellipsis.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ellipsis\naid: ellipsis\nurl: https://www.ellipsis.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The company or person accepting this Agreement\n- type: business\n  text: If you accept on behalf of a company, you represent that you are authorized to bind that company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ellipsis/eligibility/ellipsis-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Ellipsis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Review
- AI Agents
- Coding Agents
- Developer Tools
- Software Development
- Automation
- DevOps
- Pull Requests
---
