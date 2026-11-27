---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is operated from the United States but accessible worldwide.
  entity_types:
  - text: Users must be at least eighteen (18) years old and have legal capacity to contract.
    type: individual
  - text: a marketplace where businesses may post projects or describe AI-related needs
    type: business
  minimum_age:
    text: Users must be at least eighteen (18) years old and have legal capacity to contract.
    value: '18'
  restricted_uses:
  - summary: Impersonation and misrepresentation
    text: Use of the Service to impersonate individuals, misrepresent affiliations, or violate messaging or data-protection laws is prohibited.
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
name: Testmyprompt
provenance_date: '2026-11-09'
provider_name: Testmyprompt
provider_slug: buildmyagent
slug: buildmyagent-eligibility
source_date: '2026-11-09'
source_filename: buildmyagent-eligibility.yml
source_heading: Eligibility
source_page: https://buildmyagent.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Testmyprompt\naid: buildmyagent\nurl: https://buildmyagent.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is operated from the United States but accessible worldwide.\nentity_types:\n- type: individual\n  text: Users must be at least eighteen (18) years old and have legal capacity to contract.\n- type: business\n  text: a marketplace where businesses may post projects or describe AI-related needs\nrestricted_uses:\n- summary: Impersonation and misrepresentation\n  text: Use of the Service to impersonate individuals, misrepresent affiliations, or violate messaging\
  \ or data-protection\n    laws is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least eighteen (18) years old and have legal capacity to contract.\n"
source_yaml_url: https://artifacts.apis.io/buildmyagent/eligibility/buildmyagent-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Testmyprompt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Platform
- Integration
- Bots
---
