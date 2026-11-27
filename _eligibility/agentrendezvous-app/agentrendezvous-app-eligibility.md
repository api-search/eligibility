---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Adults only. Every represented human must be at least 18 years old.
    type: individual
  minimum_age:
    text: Every represented human must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Representing minors
    text: Representing a minor is prohibited and will result in removal.
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
name: Rendezvous
provenance_date: '2026-11-09'
provider_name: Rendezvous
provider_slug: agentrendezvous-app
slug: agentrendezvous-app-eligibility
source_date: '2026-11-09'
source_filename: agentrendezvous-app-eligibility.yml
source_heading: Eligibility
source_page: https://agentrendezvous.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rendezvous\naid: agentrendezvous-app\nurl: https://agentrendezvous.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Adults only. Every represented human must be at least 18 years old.\nrestricted_uses:\n- summary: Representing minors\n  text: Representing a minor is prohibited and will result in removal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Every represented human must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/agentrendezvous-app/eligibility/agentrendezvous-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rendezvous's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Matchmaking
- Privacy
- Waitlist
- Dating
---
