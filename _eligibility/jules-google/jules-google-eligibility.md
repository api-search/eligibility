---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: But not all services mentioned may be available in your country.
  entity_types:
  - text: For business users and organizations only
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export, sanctions and trafficking laws
    text: comply with applicable laws, including export control, sanctions, and human trafficking laws
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
name: Jules
provenance_date: '2026-11-09'
provider_name: Jules
provider_slug: jules-google
slug: jules-google-eligibility
source_date: '2026-11-09'
source_filename: jules-google-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jules\naid: jules-google\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: But not all services mentioned may be available in your country.\nentity_types:\n- type: business\n  text: For business users and organizations only\nrestricted_uses:\n- summary: Export, sanctions and trafficking laws\n  text: comply with applicable laws, including export control, sanctions, and human trafficking laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jules-google/eligibility/jules-google-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Jules's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Coding Agents
- Autonomous Agent
- Asynchronous Agent
- Developer Tools
- Code Generation
- Pull Requests
- GitHub
- Gemini
- Google Labs
- Software Development Lifecycle
- DevOps
---
